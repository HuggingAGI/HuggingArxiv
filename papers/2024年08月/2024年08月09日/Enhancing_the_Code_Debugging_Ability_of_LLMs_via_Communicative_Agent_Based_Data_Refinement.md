# 借助交流代理进行数据精炼，提升 LLMs 的代码调试能力

发布时间：2024年08月09日

`LLM应用` `软件开发` `人工智能`

> Enhancing the Code Debugging Ability of LLMs via Communicative Agent Based Data Refinement

# 摘要

> 调试在软件开发中至关重要，但大型语言模型（LLMs）的调试能力尚未充分探索。本文引入了DEBUGEVAL，一个全面基准，用于评估LLMs的调试技能，涵盖BUG定位、识别、代码审查和修复四项任务。为提升LLMs的代码调试能力，我们提出了MASTER框架，通过生成精炼数据进行监督微调。MASTER利用代码测验器生成数据，代码学习者筛选难题，代码教师提供详细解决方案。实验显示，7B规模的LLMs调试能力有限，而70B以上的模型则表现出色。MASTER通过合成数据，有效提升了LLMs的代码调试能力。

> Debugging is a vital aspect of software development, yet the debugging capabilities of Large Language Models (LLMs) remain largely unexplored. This paper first introduces DEBUGEVAL, a comprehensive benchmark designed to evaluate the debugging capabilities of LLMs. DEBUGEVAL collects data from existing high-quality datasets and designs four different tasks to evaluate the debugging effectiveness, including BUG Localization, BUG Identification, Code Review, and Code Repair. Additionally, to enhance the code debugging ability of LLMs, this paper proposes a CoMmunicative Agent BaSed DaTa REfinement FRamework (MASTER), which generates the refined code debugging data for supervised finetuning. Specifically, MASTER employs the Code Quizzer to generate refined data according to the defined tasks of DEBUGEVAL. Then the Code Learner acts as a critic and reserves the generated problems that it can not solve. Finally, the Code Teacher provides a detailed Chain-of-Thought based solution to deal with the generated problem. We collect the synthesized data and finetune the Code Learner to enhance the debugging ability and conduct the NeuDebugger model. Our experiments evaluate various LLMs and NeuDebugger in the zero-shot setting on DEBUGEVAL. Experimental results demonstrate that these 7B-scale LLMs have weaker debugging capabilities, even these code-oriented LLMs. On the contrary, these larger models (over 70B) show convincing debugging ability. Our further analyses illustrate that MASTER is an effective method to enhance the code debugging ability by synthesizing data for Supervised Fine-Tuning (SFT) LLMs.

[Arxiv](https://arxiv.org/abs/2408.05006)