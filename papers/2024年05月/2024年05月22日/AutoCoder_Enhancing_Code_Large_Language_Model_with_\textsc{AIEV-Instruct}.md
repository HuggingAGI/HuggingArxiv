# AutoCoder：借助 \textsc{AIEV-Instruct} 提升大型语言模型的编程能力

发布时间：2024年05月22日

`Agent

理由：这篇论文介绍的AutoCoder模型不仅在性能上超越了其他大型语言模型，特别是在Human Eval基准测试中表现出色，而且其特点在于结合了代理交互（Agent interaction）和代码执行验证。这种结合体现了Agent的概念，即模型能够与外部环境交互并执行任务，如安装外部包和验证代码执行的有效性。因此，这篇论文更符合Agent分类，因为它展示了模型作为代理在实际应用中的能力和效果。` `软件开发` `人工智能`

> AutoCoder: Enhancing Code Large Language Model with \textsc{AIEV-Instruct}

# 摘要

> 我们推出了AutoCoder，这是首个在Human Eval基准测试的pass@1上超越GPT-4 Turbo和GPT-4o的大型语言模型，其通过率达到了$\mathbf{90.9\%}$，略胜一筹。AutoCoder的代码解释器更为灵活，能安装外部包，不再局限于内置包。其训练数据集\textbf{\textsc{AIEV-Instruct}}结合了代理交互与代码执行验证，不仅减少了对大型专有模型的依赖，还确保了代码数据的执行有效性。相关代码和演示视频已发布于\url{https://github.com/bin123apple/AutoCoder}。

> We introduce AutoCoder, the first Large Language Model to surpass GPT-4 Turbo (April 2024) and GPT-4o in pass@1 on the Human Eval benchmark test ($\mathbf{90.9\%}$ vs. $\mathbf{90.2\%}$). In addition, AutoCoder offers a more versatile code interpreter compared to GPT-4 Turbo and GPT-4o. It's code interpreter can install external packages instead of limiting to built-in packages. AutoCoder's training data is a multi-turn dialogue dataset created by a system combining agent interaction and external code execution verification, a method we term \textbf{\textsc{AIEV-Instruct}} (Instruction Tuning with Agent-Interaction and Execution-Verified). Compared to previous large-scale code dataset generation methods, \textsc{AIEV-Instruct} reduces dependence on proprietary large models and provides execution-validated code dataset. The code and the demo video is available in \url{https://github.com/bin123apple/AutoCoder}.

[Arxiv](https://arxiv.org/abs/2405.14906)