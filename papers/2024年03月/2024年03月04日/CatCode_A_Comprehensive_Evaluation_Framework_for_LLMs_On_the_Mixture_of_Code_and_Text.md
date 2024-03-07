# [CatCode 是一个综合性的评估框架，专为在混合代码与文本环境中的大型语言模型（LLMs）设计，旨在全方位测评其性能表现。](https://arxiv.org/abs/2403.01784)

发布时间：2024年03月04日

`LLM应用`

> CatCode: A Comprehensive Evaluation Framework for LLMs On the Mixture of Code and Text

> 随着 ChatGPT 等大规模语言模型在处理和创作代码与文本混合内容上的技艺日臻成熟，通过对此类“混合”内容的评估，有助于深入理解模型解决编程问题的整体实力。但目前，在这个领域中，现有的评估手段或是任务覆盖面不足，或是标准不一。因此，我们建议利用范畴论构建一个评估框架，其中，代码范畴内的态射可用于表示代码调试与转换过程，不同范畴间的函子代表代码翻译操作，而连接代码范畴与自然语言范畴的函子则对应于代码生成、解释及复现等功能。为此，我们推出了一款全面自动化的评估工具——$\textbf{CatCode}$（类别-代码），它能系统性地评判包括 ChatGPT、Text-Davinci 和 CodeGeeX 在内的 LLMs 在编码能力上的表现。

> Large language models (LLMs) such as ChatGPT are increasingly proficient in understanding and generating a mixture of code and text. Evaluation based on such $\textit{mixture}$ can lead to a more comprehensive understanding of the models' abilities in solving coding problems. However, in this context, current evaluation methods are either limited in task coverage or lack standardization. To address this issue, we propose using category theory as a framework for evaluation. Specifically, morphisms within a code category can represent code debugging and transformation, functors between two categories represent code translation, and functors between a code category and a natural language category represent code generation, explanation, and reproduction. We present an automatic evaluation framework called $\textbf{CatCode}$ ($\textbf{Cat}$egory $\textbf{Code}$) that can comprehensively assess the coding abilities of LLMs, including ChatGPT, Text-Davinci, and CodeGeeX.