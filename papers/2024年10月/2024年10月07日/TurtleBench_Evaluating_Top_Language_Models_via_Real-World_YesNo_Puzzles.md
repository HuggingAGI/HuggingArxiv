# TurtleBench：用现实中的 Yes/No 谜题来检验顶级语言模型的实力

发布时间：2024年10月07日

`LLM应用` `人工智能`

> TurtleBench: Evaluating Top Language Models via Real-World Yes/No Puzzles

# 摘要

> 随着 LLM 应用的扩展，对可靠评估的需求日益增长。现有评估基准多依赖静态数据集，难以在动态用户交互中准确评估模型性能。此外，这些基准常依赖特定背景知识，使得逻辑推理能力的测量变得复杂。其他动态评估方法虽基于强模型或人工努力，但可能引入偏见，且成本高昂、耗时，限制了大规模应用。为此，我们提出 TurtleBench，通过收集在线 Turtle Soup Puzzle 平台的真实用户猜测，实现相对动态的评估数据集生成，减少模型作弊风险，更贴近用户对推理能力的真实需求，提升评估可靠性。TurtleBench 包含 1,532 个用户猜测及其正确性。我们使用此数据集评估了九个最先进的 LLM，发现 OpenAI 的 o1 系列模型并未领先。我们提出多个研究假设，如“o1 的潜在推理依赖简单链式思维 (CoT) 技术”和“增加 CoT 长度虽提升推理能力，但也引入噪声成本”。

> As the application of Large Language Models (LLMs) expands, the demand for reliable evaluations increases. Existing LLM evaluation benchmarks primarily rely on static datasets, making it challenging to assess model performance in dynamic interactions with users. Moreover, these benchmarks often depend on specific background knowledge, complicating the measurement of a model's logical reasoning capabilities. Other dynamic evaluation methods based on strong models or manual efforts may introduce biases and incur high costs and time demands, hindering large-scale application. To address these issues, we propose TurtleBench. TurtleBench collects real user guesses from our online Turtle Soup Puzzle platform that we developed. This approach allows for the relatively dynamic generation of evaluation datasets, mitigating the risk of model cheating while aligning assessments more closely with genuine user needs for reasoning capabilities, thus enhancing the reliability of evaluations. TurtleBench includes 1,532 user guesses along with the correctness of guesses after annotation. Using this dataset, we thoroughly evaluated nine of the most advanced LLMs available today. Notably, the OpenAI o1 series models did not achieve leading results in these evaluations. We propose several hypotheses for further research, such as "the latent reasoning of o1 utilizes trivial Chain-of-Thought (CoT) techniques" and "increasing CoT length not only provides reasoning benefits but also incurs noise costs."

[Arxiv](https://arxiv.org/abs/2410.05262)