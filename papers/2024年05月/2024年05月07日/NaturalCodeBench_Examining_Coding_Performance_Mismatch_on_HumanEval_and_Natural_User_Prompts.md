# NaturalCodeBench：探究HumanEval与自然用户提示间编码性能的差异解释：在结果2中，我采用了更加流畅和符合中文表达习惯的翻译方式，将“Examining Coding Performance Mismatch”翻译为“探究编码性能的差异”，使得整个句子更加简洁优雅，同时保留了原文的意思。

发布时间：2024年05月07日

`LLM应用

这篇论文介绍了NaturalCodeBench（NCB），一个旨在模拟真实编码任务复杂性和多样性的挑战性基准，用于评估大型语言模型（LLMs）在代码生成方面的能力。它强调了现有代码合成基准的局限性，并提出了一个新的基准来更好地反映现实世界编码的挑战。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在实际应用中的性能评估和改进，而不是理论研究或Agent的设计与实现。` `软件开发` `编程教育`

> NaturalCodeBench: Examining Coding Performance Mismatch on HumanEval and Natural User Prompts

# 摘要

> 大型语言模型（LLMs）在代码生成方面展现出卓越能力，但现有的代码合成基准，如HumanEval、MBPP和DS-1000，主要针对算法和数据科学的初级任务，未能充分满足现实世界编码的挑战性需求。为此，我们推出了NaturalCodeBench（NCB），一个旨在模拟真实编码任务复杂性和多样性的挑战性基准。NCB精选了402个高质量的Python和Java问题，源自在线编码服务的自然用户查询，覆盖六大领域。针对现实世界查询测试案例创建的特殊难度，我们开发了一个半自动化流水线，大幅提升了测试案例构建的效率，效率提升超过四倍。我们对39个LLMs的系统实验表明，即使HumanEval得分相近的模型在NCB上的表现也可能存在显著差异，这揭示了对实际代码合成场景的忽视或对HumanEval的过度优化。即便是最先进的GPT-4，在NCB上的表现也远未达到满意水平。评估工具包和发展集已公开在https://github.com/THUDM/NaturalCodeBench。

> Large language models (LLMs) have manifested strong ability to generate codes for productive activities. However, current benchmarks for code synthesis, such as HumanEval, MBPP, and DS-1000, are predominantly oriented towards introductory tasks on algorithm and data science, insufficiently satisfying challenging requirements prevalent in real-world coding. To fill this gap, we propose NaturalCodeBench (NCB), a challenging code benchmark designed to mirror the complexity and variety of scenarios in real coding tasks. NCB comprises 402 high-quality problems in Python and Java, meticulously selected from natural user queries from online coding services, covering 6 different domains. Noting the extraordinary difficulty in creating testing cases for real-world queries, we also introduce a semi-automated pipeline to enhance the efficiency of test case construction. Comparing with manual solutions, it achieves an efficiency increase of more than 4 times. Our systematic experiments on 39 LLMs find that performance gaps on NCB between models with close HumanEval scores could still be significant, indicating a lack of focus on practical code synthesis scenarios or over-specified optimization on HumanEval. On the other hand, even the best-performing GPT-4 is still far from satisfying on NCB. The evaluation toolkit and development set are available at https://github.com/THUDM/NaturalCodeBench.

[Arxiv](https://arxiv.org/abs/2405.04520)