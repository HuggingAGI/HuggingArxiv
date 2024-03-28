# 本研究利用教师-学生架构的大型语言模型，针对具有多重约束条件的指令，实现精准的分子生成任务。

发布时间：2024年03月19日

`LLM应用` `药物研发` `材料科学`

> Instruction Multi-Constraint Molecular Generation Using a Teacher-Student Large Language Model

# 摘要

> 尽管已有众多针对分子结构与性质分析的模型与计算工具，但要生成完全符合预期结构和性质的分子依然是个难题。现在我们引入一款名为TSMMG的多约束分子生成大型语言模型，该模型犹如一名博采众长的学生，整合了各类小型模型及工具（称为“教师”）的知识。我们采用自“教师”们汲取的分子知识，构造了一个大规模的文本-分子配对集合，以此来训练TSMMG，使其能够依据不同文本提示创造出符合理论描述的新分子。实验证明，TSMMG在处理包含两至四个约束条件的复杂自然语言描述性质的任务时表现卓越，分子有效率均值超过99%，成功率分别达到88.08%、65.27%和61.44%。不仅如此，TSMMG还能通过零样本测试展示其对新性质组合的理解与适应能力，并且经验证，它可以灵活应对各种语言风格的文本输入，突破预设提示框架。同时，TSMMG利用知识蒸馏技术促进小型模型的不断优化，而其创新的数据集构建方式也有效缓解了数据匮乏与质量问题，从而将TSMMG打造成在药物研发和材料科学领域极具潜力的应用工具，相关代码已在GitHub平台（https://github.com/HHW-zhou/TSMMG）开源。

> While various models and computational tools have been proposed for structure and property analysis of molecules, generating molecules that conform to all desired structures and properties remains a challenge. Here, we introduce a multi-constraint molecular generation large language model, TSMMG, which, akin to a student, incorporates knowledge from various small models and tools, namely, the 'teachers'. To train TSMMG, we construct a large set of text-molecule pairs by extracting molecular knowledge from these 'teachers', enabling it to generate novel molecules that conform to the descriptions through various text prompts. We experimentally show that TSMMG remarkably performs in generating molecules meeting complex, natural language-described property requirements across two-, three-, and four-constraint tasks, with an average molecular validity of over 99% and success ratio of 88.08%, 65.27%, and 61.44%, respectively. The model also exhibits adaptability through zero-shot testing, creating molecules that satisfy combinations of properties that have not been encountered. It can comprehend text inputs with various language styles, extending beyond the confines of outlined prompts, as confirmed through empirical validation. Additionally, the knowledge distillation feature of TSMMG contributes to the continuous enhancement of small models, while the innovative approach to dataset construction effectively addresses the issues of data scarcity and quality, which positions TSMMG as a promising tool in the domains of drug discovery and materials science. Code is available at https://github.com/HHW-zhou/TSMMG.

[Arxiv](https://arxiv.org/abs/2403.13244)