# [本研究探讨如何训练多个语言模型协同解码，以提升整体的解码效果和性能。]

发布时间：2024年03月06日

`Agent`

> Learning to Decode Collaboratively with Multiple Language Models

> 我们创新了一种让多个大型语言模型（LLM）在令牌层级上交替协同生成的方法，并将“由谁生成下一个令牌”的决策视为一个潜在变量。在对训练集边缘似然性进行优化的过程中，基础LLM能在无需直接指导的情况下自主掌握何时独立生成以及何时调动“辅助”语言模型接力生成。这种解码阶段的令牌级协同工作方式，能灵活地结合各模型在特定任务上的优势。尤其在跨领域的场景中，通用型基础LLM学会了如何调动领域专家模型，从而显著提升系统性能。实验证明，在执行指令、处理特定领域问题和推理任务时，联合系统的效能超过了单个模型的表现。进一步通过对所学潜在决策的质性分析，我们发现运用此方法训练出的模型展现出诸如模板填充等多种有趣的协同模式。相关代码已开源，访问地址为https://github.com/clinicalml/co-llm。

> We propose a method to teach multiple large language models (LLM) to collaborate by interleaving their generations at the token level. We model the decision of which LLM generates the next token as a latent variable. By optimizing the marginal likelihood of a training set under our latent variable model, the base LLM automatically learns when to generate itself and when to call on one of the ``assistant'' language models to generate, all without direct supervision. Token-level collaboration during decoding allows for a fusion of each model's expertise in a manner tailored to the specific task at hand. Our collaborative decoding is especially useful in cross-domain settings where a generalist base LLM learns to invoke domain expert models. On instruction-following, domain-specific QA, and reasoning tasks, we show that the performance of the joint system exceeds that of the individual models. Through qualitative analysis of the learned latent decisions, we show models trained with our method exhibit several interesting collaboration patterns, e.g., template-filling. Our code is available at https://github.com/clinicalml/co-llm.

[Arxiv](https://arxiv.org/abs/2403.03870)