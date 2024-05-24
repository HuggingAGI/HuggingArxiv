# TrojanRAG：大型语言模型中的检索增强生成可能潜藏后门风险
发布时间：2024年05月22日

`RAG`
> TrojanRAG: Retrieval-Augmented Generation Can Be Backdoor Driver in Large Language Models
>
> 尽管大型语言模型（LLMs）在自然语言处理（NLP）领域表现卓越，但其潜在的安全威胁也引起了广泛关注。后门攻击虽证实了LLMs在各阶段造成的损害，但其高昂的成本和脆弱性备受诟病。攻击LLMs不仅风险重重，且成本巨大。随着LLMs的不断迭代，后门的鲁棒性亦随之下降。本文提出的TrojanRAG，巧妙地在检索增强生成中实施联合后门攻击，操控LLMs于各种攻击场景。攻击者精心设计目标上下文与触发集，通过对比学习优化多个后门快捷方式，确保触发条件精准匹配于参数子空间。为提升RAG对目标上下文的识别率，我们借助知识图谱构建结构化数据，实现细粒度的精确匹配。此外，我们标准化了LLMs中的后门场景，从攻击者与用户的双重视角审视后门带来的实际危害，并探讨上下文是否为解锁模型的有效手段。实验结果显示，TrojanRAG在保持正常查询检索能力的同时，展现出广泛的安全威胁。
>
> https://arxiv.org/abs/2405.13401


<hr />

- 论文原文: [https://arxiv.org/abs/2405.13401](https://arxiv.org/abs/2405.13401)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 8855214518158442