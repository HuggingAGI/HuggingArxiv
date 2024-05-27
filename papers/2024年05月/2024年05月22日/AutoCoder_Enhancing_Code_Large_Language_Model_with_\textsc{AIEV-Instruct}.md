# AutoCoder：借助\textsc{AIEV-Instruct}，提升大型语言模型在代码领域的性能

发布时间：2024年05月22日

`Agent

理由：这篇论文介绍了一个名为AutoCoder的大型语言模型，它不仅在Human Eval测试中表现出色，还具备强大的代码解释器功能，能够安装外部包。更重要的是，其训练数据集结合了代理交互与代码执行验证，这表明模型在设计和应用中考虑了代理（Agent）的概念，即模型能够自主地与环境交互并执行任务。因此，这篇论文更符合Agent分类。` `软件开发` `人工智能`

> AutoCoder: Enhancing Code Large Language Model with \textsc{AIEV-Instruct}

# 摘要

> 我们推出了AutoCoder，这是首个在Human Eval测试中pass@1超越GPT-4 Turbo和GPT-4o的大型语言模型，其通过率高达$\mathbf{90.9\%}$。AutoCoder的代码解释器功能更为强大，能安装外部包，不再局限于内置包。其训练数据集\textbf{\textsc{AIEV-Instruct}}结合了代理交互与代码执行验证，减少了专有大模型的依赖，并确保了代码的执行有效性。代码及演示视频已发布于\url{https://github.com/bin123apple/AutoCoder}。

> We introduce AutoCoder, the first Large Language Model to surpass GPT-4 Turbo (April 2024) and GPT-4o in pass@1 on the Human Eval benchmark test ($\mathbf{90.9\%}$ vs. $\mathbf{90.2\%}$). In addition, AutoCoder offers a more versatile code interpreter compared to GPT-4 Turbo and GPT-4o. It's code interpreter can install external packages instead of limiting to built-in packages. AutoCoder's training data is a multi-turn dialogue dataset created by a system combining agent interaction and external code execution verification, a method we term \textbf{\textsc{AIEV-Instruct}} (Instruction Tuning with Agent-Interaction and Execution-Verified). Compared to previous large-scale code dataset generation methods, \textsc{AIEV-Instruct} reduces dependence on proprietary large models and provides execution-validated code dataset. The code and the demo video is available in \url{https://github.com/bin123apple/AutoCoder}.

[Arxiv](https://arxiv.org/abs/2405.14906)