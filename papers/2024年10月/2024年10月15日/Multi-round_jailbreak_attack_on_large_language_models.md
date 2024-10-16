# 大型语言模型面临多轮越狱攻击

发布时间：2024年10月15日

`LLM应用` `网络安全` `人工智能`

> Multi-round jailbreak attack on large language models

# 摘要

> 确保 LLM 与人类价值观的安全一致至关重要。尽管 LLM 能识别并避免有害查询，但仍易受“越狱”攻击，精心设计的提示可诱导生成有毒内容。传统单轮越狱攻击如 GCG 和 AutoDAN 不改变危险提示中的敏感词，虽能通过提示工程暂时绕过模型安全措施，但随着 LLM 进一步微调，成功率显著下降，且无法有效绕过删除危险词汇的静态规则过滤器。本研究引入多轮越狱方法，重写危险提示为危害较小的子问题，绕过 LLM 安全检查。首先使用 LLM 将自然语言问题分解为渐进子问题，微调 Llama3-8B 模型以分解危险提示。微调后模型分解问题提示，生成的子问题依次询问受害者模型。若受害者模型拒绝子问题，则生成新分解并重复，直至达成目标。实验结果显示，在 llama2-7B 上的成功率为 94%，证明该方法在绕过静态规则过滤器方面的有效性。

> Ensuring the safety and alignment of large language models (LLMs) with human values is crucial for generating responses that are beneficial to humanity. While LLMs have the capability to identify and avoid harmful queries, they remain vulnerable to "jailbreak" attacks, where carefully crafted prompts can induce the generation of toxic content. Traditional single-round jailbreak attacks, such as GCG and AutoDAN, do not alter the sensitive words in the dangerous prompts. Although they can temporarily bypass the model's safeguards through prompt engineering, their success rate drops significantly as the LLM is further fine-tuned, and they cannot effectively circumvent static rule-based filters that remove the hazardous vocabulary.
  In this study, to better understand jailbreak attacks, we introduce a multi-round jailbreak approach. This method can rewrite the dangerous prompts, decomposing them into a series of less harmful sub-questions to bypass the LLM's safety checks. We first use the LLM to perform a decomposition task, breaking down a set of natural language questions into a sequence of progressive sub-questions, which are then used to fine-tune the Llama3-8B model, enabling it to decompose hazardous prompts. The fine-tuned model is then used to break down the problematic prompt, and the resulting sub-questions are sequentially asked to the victim model. If the victim model rejects a sub-question, a new decomposition is generated, and the process is repeated until the final objective is achieved. Our experimental results show a 94\% success rate on the llama2-7B and demonstrate the effectiveness of this approach in circumventing static rule-based filters.

[Arxiv](https://arxiv.org/abs/2410.11533)