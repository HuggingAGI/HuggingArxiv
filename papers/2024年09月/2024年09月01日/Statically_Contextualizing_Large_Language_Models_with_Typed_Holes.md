# 通过类型化孔洞技术，静态地增强大型语言模型的上下文理解能力

发布时间：2024年09月01日

`LLM应用` `软件开发` `人工智能`

> Statically Contextualizing Large Language Models with Typed Holes

# 摘要

> 大型语言模型 (LLM) 已经彻底改变了程序合成的领域。然而，基于 LLM 的代码补全系统往往因缺乏适当上下文而生成错误代码，尤其是在处理训练数据中未包含或远离光标的定义时。本文提出，通过与语言的类型和绑定结构紧密集成，可以高效解决这一问题。我们坚信，AI 同样需要集成开发环境 (IDE)。具体来说，我们将 LLM 代码生成融入 Hazel 实时程序草图环境，通过 Hazel 语言服务器识别类型和上下文，即使在错误存在的情况下，也能确保提供有意义的程序草图。这使得我们能够利用与开发者目标语义相关的代码库范围上下文信息进行提示，并通过与语言服务器的进一步交互迭代优化补全代码。为评估这些技术，我们创建了 MVUBench 数据集，包含依赖特定数据结构的 MVU 网络应用程序，发现类型定义的上下文化尤为关键。在 Hazel 环境中验证我们的方法后，我们将技术移植到 TypeScript，以证明其对资源更丰富的语言的适用性。最后，我们提出了 ChatLSP，一种对语言服务器协议 (LSP) 的保守扩展，旨在增强 AI 代码补全系统在生成提示时纳入静态上下文的能力。

> Large language models (LLMs) have reshaped the landscape of program synthesis. However, contemporary LLM-based code completion systems often hallucinate broken code because they lack appropriate context, particularly when working with definitions not in the training data nor near the cursor. This paper demonstrates that tight integration with the type and binding structure of a language, as exposed by its language server, can address this contextualization problem in a token-efficient manner. In short, we contend that AIs need IDEs, too! In particular, we integrate LLM code generation into the Hazel live program sketching environment. The Hazel Language Server identifies the type and typing context of the hole being filled, even in the presence of errors, ensuring that a meaningful program sketch is always available. This allows prompting with codebase-wide contextual information not lexically local to the cursor, nor necessarily in the same file, but that is likely to be semantically local to the developer's goal. Completions synthesized by the LLM are then iteratively refined via further dialog with the language server. To evaluate these techniques, we introduce MVUBench, a dataset of model-view-update (MVU) web applications. These applications serve as challenge problems due to their reliance on application-specific data structures. We find that contextualization with type definitions is particularly impactful. After introducing our ideas in the context of Hazel we duplicate our techniques and port MVUBench to TypeScript in order to validate the applicability of these methods to higher-resource languages. Finally, we outline ChatLSP, a conservative extension to the Language Server Protocol (LSP) that language servers can implement to expose capabilities that AI code completion systems of various designs can use to incorporate static context when generating prompts for an LLM.

[Arxiv](https://arxiv.org/abs/2409.00921)