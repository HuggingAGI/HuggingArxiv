# 大型语言模型中的代码生成：多编程语言集成

发布时间：2024年09月06日

`LLM应用` `软件开发` `人工智能`

> Multi-Programming Language Ensemble for Code Generation in Large Language Model

# 摘要

> 大型语言模型 (LLM) 在单次代码生成方面表现出色，但现有方法多局限于单一编程语言，忽略了 LLM 的多语言潜力。LLM 在不同语言中的错误模式各异，提示我们通过整合多语言输出，可以开发出更稳健的代码生成方法。为此，我们提出了多编程语言集成 (MPLE)，一种利用多种编程语言生成代码的集成方法，通过将每种语言的代码生成视为“弱专家”，并整合其输出，有效减少语言特定错误。MPLE 利用不同编程语言的互补优势，生成更准确、更稳健的代码。此外，MPLE 可与反射算法和蒙特卡罗树搜索等常用技术无缝结合，进一步提升代码质量。实验表明，MPLE 在 HumanEval 和 HumanEval-plus 基准测试中，性能提升高达 17.92%，HumanEval 基准准确率达到 96.25%，刷新了 LLM 模型的最佳表现。代码将在 https://github.com/NinjaTech-AI/MPLE 发布。

> Large language models (LLMs) have significantly improved code generation, particularly in one-pass code generation. However, most existing approaches focus solely on generating code in a single programming language, overlooking the potential of leveraging the multi-language capabilities of LLMs. LLMs have varying patterns of errors across different languages, suggesting that a more robust approach could be developed by leveraging these multi-language outputs. In this study, we propose Multi-Programming Language Ensemble (MPLE), a novel ensemble-based method that utilizes code generation across multiple programming languages to enhance overall performance. By treating each language-specific code generation process as an individual "weak expert" and effectively integrating their outputs, our method mitigates language-specific errors and biases. This multi-language ensemble strategy leverages the complementary strengths of different programming languages, enabling the model to produce more accurate and robust code. Our approach can be seamlessly integrated with commonly used techniques such as the reflection algorithm and Monte Carlo tree search to improve code generation quality further. Experimental results show that our framework consistently enhances baseline performance by up to 17.92% on existing benchmarks (HumanEval and HumanEval-plus), with a standout result of 96.25% accuracy on the HumanEval benchmark, achieving new state-of-the-art results across various LLM models. The code will be released at https://github.com/NinjaTech-AI/MPLE

[Arxiv](https://arxiv.org/abs/2409.04114)