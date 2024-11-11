# 通过后门在检索增强生成中的数据提取攻击

发布时间：2024年11月03日

`RAG` `信息安全` `数据库`

> Data Extraction Attacks in Retrieval-Augmented Generation via Backdoors

# 摘要

> 尽管取得了显著进展，但大型语言模型（LLM）在缺乏特定领域或最新知识时仍难以提供准确答案。检索增强生成（RAG）通过结合外部知识库解决了这一限制，但它也引入了新的攻击面。在本文中，我们研究了针对 RAG 系统知识数据库的数据提取攻击。我们证明，之前对 RAG 的攻击在很大程度上依赖于 LLM 的指令遵循能力，并且简单的微调可以将此类攻击的成功率降低到几乎为零。这使得这些攻击不切实际，因为在特定领域部署 LLM 时微调是常见做法。为了进一步揭示漏洞，我们提议对 RAG 进行后门攻击，即在微调阶段注入一小部分中毒数据，在 LLM 内创建一个后门。当这个受损的 LLM 集成到 RAG 系统中时，攻击者可以利用提示中的特定触发因素来操纵 LLM 从检索数据库中泄露文档。通过精心设计中毒数据，我们实现了原文和改写的文档提取。我们表明，仅使用 3％的中毒数据，我们的方法在 Llama2-7B 上的原文提取平均成功率达到 79.7％，ROUGE-L 分数为 64.21，改写提取的平均成功率为 68.6％，四个数据集的平均 ROUGE 分数为 52.6。这些结果强调了部署 RAG 系统时供应链相关的隐私风险。

> Despite significant advancements, large language models (LLMs) still struggle with providing accurate answers when lacking domain-specific or up-to-date knowledge. Retrieval-Augmented Generation (RAG) addresses this limitation by incorporating external knowledge bases, but it also introduces new attack surfaces. In this paper, we investigate data extraction attacks targeting the knowledge databases of RAG systems. We demonstrate that previous attacks on RAG largely depend on the instruction-following capabilities of LLMs, and that simple fine-tuning can reduce the success rate of such attacks to nearly zero. This makes these attacks impractical since fine-tuning is a common practice when deploying LLMs in specific domains. To further reveal the vulnerability, we propose to backdoor RAG, where a small portion of poisoned data is injected during the fine-tuning phase to create a backdoor within the LLM. When this compromised LLM is integrated into a RAG system, attackers can exploit specific triggers in prompts to manipulate the LLM to leak documents from the retrieval database. By carefully designing the poisoned data, we achieve both verbatim and paraphrased document extraction. We show that with only 3\% poisoned data, our method achieves an average success rate of 79.7\% in verbatim extraction on Llama2-7B, with a ROUGE-L score of 64.21, and a 68.6\% average success rate in paraphrased extraction, with an average ROUGE score of 52.6 across four datasets. These results underscore the privacy risks associated with the supply chain when deploying RAG systems.

[Arxiv](https://arxiv.org/abs/2411.01705)