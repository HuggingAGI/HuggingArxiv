# 大型语言模型驱动的因果代理

发布时间：2024年08月13日

`Agent` `人工智能` `数据科学`

> Causal Agent based on Large Language Model

# 摘要

> 大型语言模型（LLM）在多领域取得了显著成就，但因果问题的复杂性及因果理论的描述难度，使得 LLM 在理解和应用因果关系上遇到挑战。因果方法难以通过自然语言传达，且因果数据集与 LLM 擅长的自然语言数据结构不匹配，影响了因果推理能力的发展。为此，我们开发了名为“因果代理”的框架，内含因果工具、记忆和推理模块，帮助 LLM 处理因果问题。通过将表格数据与自然语言对齐，并利用 ReAct 框架进行多轮推理，因果代理在记忆模块中存储因果图，有效提升了因果问题的解决能力。我们设立了包含四个难度级别的因果问题基准，并使用 ChatGPT-3.5 生成了 1.3K 测试数据集进行验证，结果显示因果代理在各级别问题上的准确率均超过 80%。更多详情和代码实现，请访问 GitHub 仓库 https://github.com/Kairong-Han/Causal_Agent。

> Large language models (LLMs) have achieved significant success across various domains. However, the inherent complexity of causal problems and causal theory poses challenges in accurately describing them in natural language, making it difficult for LLMs to comprehend and use them effectively. Causal methods are not easily conveyed through natural language, which hinders LLMs' ability to apply them accurately. Additionally, causal datasets are typically tabular, while LLMs excel in handling natural language data, creating a structural mismatch that impedes effective reasoning with tabular data. This lack of causal reasoning capability limits the development of LLMs. To address these challenges, we have equipped the LLM with causal tools within an agent framework, named the Causal Agent, enabling it to tackle causal problems. The causal agent comprises tools, memory, and reasoning modules. In the tools module, the causal agent applies causal methods to align tabular data with natural language. In the reasoning module, the causal agent employs the ReAct framework to perform reasoning through multiple iterations with the tools. In the memory module, the causal agent maintains a dictionary instance where the keys are unique names and the values are causal graphs. To verify the causal ability of the causal agent, we established a benchmark consisting of four levels of causal problems: variable level, edge level, causal graph level, and causal effect level. We generated a test dataset of 1.3K using ChatGPT-3.5 for these four levels of issues and tested the causal agent on the datasets. Our methodology demonstrates remarkable efficacy on the four-level causal problems, with accuracy rates all above 80%. For further insights and implementation details, our code is accessible via the GitHub repository https://github.com/Kairong-Han/Causal_Agent.

[Arxiv](https://arxiv.org/abs/2408.06849)