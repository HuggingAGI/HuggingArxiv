# HijackRAG：针对检索增强型大型语言模型的劫持式攻击

发布时间：2024年10月30日

`RAG` `信息安全` `语言模型`

> HijackRAG: Hijacking Attacks against Retrieval-Augmented Large Language Models

# 摘要

> 检索增强生成（RAG）系统借助整合外部知识来强化大型语言模型（LLMs），让其能适应各类应用，且具备成本效益。但对这类系统不断增强的依赖，也引发了潜在的安全风险。在此次研究中，我们揭示了一种新的漏洞——检索提示劫持攻击（HijackRAG），它使得攻击者能够通过向知识数据库注入恶意文本，来操控 RAG 系统的检索机制。当 RAG 系统碰到目标问题时，它会生成攻击者预先设定的答案，而非正确答案，从而破坏了系统的完整性与可信度。我们将 HijackRAG 构建为一个优化问题，并针对攻击者不同的知识水平，提出了黑盒和白盒攻击策略。在多个基准数据集上开展的大量实验表明，HijackRAG 始终能取得很高的攻击成功率，优于现有的基线攻击。此外，我们证实该攻击在不同的检索器模型之间具有可迁移性，突出了其对 RAG 系统造成的广泛风险。最后，我们对各种防御机制的探索显示，它们难以应对 HijackRAG，强调了迫切需要更有力的安全措施，以保障 RAG 系统在实际部署中的安全。

> Retrieval-Augmented Generation (RAG) systems enhance large language models (LLMs) by integrating external knowledge, making them adaptable and cost-effective for various applications. However, the growing reliance on these systems also introduces potential security risks. In this work, we reveal a novel vulnerability, the retrieval prompt hijack attack (HijackRAG), which enables attackers to manipulate the retrieval mechanisms of RAG systems by injecting malicious texts into the knowledge database. When the RAG system encounters target questions, it generates the attacker's pre-determined answers instead of the correct ones, undermining the integrity and trustworthiness of the system. We formalize HijackRAG as an optimization problem and propose both black-box and white-box attack strategies tailored to different levels of the attacker's knowledge. Extensive experiments on multiple benchmark datasets show that HijackRAG consistently achieves high attack success rates, outperforming existing baseline attacks. Furthermore, we demonstrate that the attack is transferable across different retriever models, underscoring the widespread risk it poses to RAG systems. Lastly, our exploration of various defense mechanisms reveals that they are insufficient to counter HijackRAG, emphasizing the urgent need for more robust security measures to protect RAG systems in real-world deployments.

[Arxiv](https://arxiv.org/abs/2410.22832)