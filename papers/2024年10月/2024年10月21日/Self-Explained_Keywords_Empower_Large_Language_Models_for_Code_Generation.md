# 自我解释的关键词助力大型语言模型实现代码生成

发布时间：2024年10月21日

`LLM应用` `软件开发` `人工智能`

> Self-Explained Keywords Empower Large Language Models for Code Generation

# 摘要

> 大型语言模型（LLM）在代码生成方面表现出色，但由于训练数据的长尾分布，低频词汇往往被忽视。这导致 LLM 在生成代码时容易误解或忽略特定问题的低频关键词，影响代码准确性。为此，我们提出了 SEK（自我解释关键词）技术，通过 LLM 自身提取并解释问题描述中的关键术语，并按频率排序，从而提升代码生成质量。实验结果显示，SEK 在 HumanEval(+)、MBPP(+) 和 APPS 三个基准测试中，显著提升了五个代表性 LLM 的代码生成能力，例如，DeepSeek-Coder-V2-Instruct 的 Pass@1 从 85.4% 提升至 93.3%。进一步分析表明，SEK 帮助 LLM 更有效地关注高频关键词，从而提高代码生成的准确性。

> Large language models (LLMs) have achieved impressive performance in code generation. However, due to the long-tail distribution of LLMs' training data, low-frequency terms are typically underrepresented in the training process. Consequently, LLMs often misunderstand or overlook problem-specific, low-frequency keywords during code generation, compromising the accuracy of the generated code. To address this, we propose a novel technique named SEK(\textbf{S}elf-\textbf{E}xplained \textbf{K}eywords), which empowers an LLM for better code generation by extracting and explaining the key terms in the problem description with the LLM itself and ranking them based on frequency. Comprehensive experiments across three benchmarks, i.e., HumanEval(+), MBPP(+), and APPS, with five representative LLMs, show that SEK can significantly improve LLMs in code generation, yielding substantial and consistent gains. For instance, SEK improves the Pass@1 of DeepSeek-Coder-V2-Instruct from 85.4\% to 93.3\% on the Humaneval benchmark. Further analysis confirms that SEK enables the LLMs to shift their attention from low-frequency keywords to their corresponding high-frequency counterparts.

[Arxiv](https://arxiv.org/abs/2410.15966)