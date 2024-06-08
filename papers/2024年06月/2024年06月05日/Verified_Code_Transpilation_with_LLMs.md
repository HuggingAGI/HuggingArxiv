# 大型语言模型（LLMs）助力验证代码转译

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLMs）来构建一个名为LLMLift的验证提升工具，该工具能够将源程序转换为目标语言中的等效程序，并生成功能等效性的证明。这种方法特别适用于领域特定语言（DSLs）的转换，旨在提高转换效率和速度，并简化构建过程。因此，这篇论文的内容与LLM的实际应用紧密相关，特别是在软件开发和代码转换领域，属于LLM应用分类。` `软件开发` `程序验证`

> Verified Code Transpilation with LLMs

# 摘要

> 领域特定语言（DSLs）在软件开发中扮演着关键角色，它们通过提供特定领域的优化和抽象，增强了代码的可读性和维护性。然而，为了利用这些语言，开发者必须通过特定DSL的API重写现有代码。尽管大型语言模型（LLMs）在自动代码转换上取得了进展，但它们并未保证转换后的代码功能正确。另一种方法是验证提升，它通过程序合成在目标语言中寻找与源程序功能等效的程序。虽然已有多种验证提升工具针对不同领域，但它们通常针对特定语言对，或者需要深厚的领域知识以优化搜索。本文中，我们借助LLMs的最新进展，提出了一种名为LLMLift的基于LLM的验证提升工具构建方法。我们利用LLM进行程序推理，将源程序转换为目标语言中的等效程序，并使用LLMs生成功能等效性的证明。我们为四个不同领域的DSL开发了基于提升的编译器。我们的方法不仅在转换效率和速度上超越了以往的符号工具，而且构建过程也更为简便。

> Domain-specific languages (DSLs) are integral to various software workflows. Such languages offer domain-specific optimizations and abstractions that improve code readability and maintainability. However, leveraging these languages requires developers to rewrite existing code using the specific DSL's API. While large language models (LLMs) have shown some success in automatic code transpilation, none of them provide any functional correctness guarantees on the transpiled code. Another approach for automating this task is verified lifting, which relies on program synthesis to find programs in the target language that are functionally equivalent to the source language program. While several verified lifting tools have been developed for various application domains, they are specialized for specific source-target languages or require significant expertise in domain knowledge to make the search efficient. In this paper, leveraging recent advances in LLMs, we propose an LLM-based approach (LLMLift) to building verified lifting tools. We use the LLM's capabilities to reason about programs to translate a given program into its corresponding equivalent in the target language. Additionally, we use LLMs to generate proofs for functional equivalence. We develop lifting-based compilers for {\em four different} DSLs targeting different application domains. Our approach not only outperforms previous symbolic-based tools in both the number of benchmarks transpiled and transpilation time, but also requires significantly less effort to build.

![大型语言模型（LLMs）助力验证代码转译](../../../paper_images/2406.03003/x1.png)

![大型语言模型（LLMs）助力验证代码转译](../../../paper_images/2406.03003/e2e_lifting.png)

![大型语言模型（LLMs）助力验证代码转译](../../../paper_images/2406.03003/x2.png)

![大型语言模型（LLMs）助力验证代码转译](../../../paper_images/2406.03003/x3.png)

![大型语言模型（LLMs）助力验证代码转译](../../../paper_images/2406.03003/x4.png)

[Arxiv](https://arxiv.org/abs/2406.03003)