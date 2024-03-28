# 为了提升形式化定理证明能力，我们构建了一个全面的数据集，专为训练 AI 模型以解析和理解 Coq 代码而设计。

发布时间：2024年03月19日

`LLM应用` `软件工程`

> Enhancing Formal Theorem Proving: A Comprehensive Dataset for Training AI Models on Coq Code

# 摘要

> 在严谨的定理证明世界里，Coq 证明助手以精准验证数学陈述和软件正确性的特性独树一帜，然而其专业化的语法与语义却给大型语言模型（LLMs）带来了特殊的难题。为解决这一问题，我们精心构建了一个专用于提升 LLMs 对 Coq 代码理解和生成能力的综合性数据集。该数据集源自逾万个 Coq 源文件，包罗万象，包括各式命题、证明和定义，并辅以来源参考和授权信息等丰富元数据。我们旨在通过这一数据集推动研发能生成语法规范且语义合理的 Coq 结构的 LLMs，进而推动自动化定理证明技术的发展边界。初期实验已揭示出此数据集的强大潜能：受训于该数据的模型在 Coq 代码生成准确度上有显著提升。其中一项实验尤为突出，显示经微调后的 LLM 能成功为一条基础引理生成 141 份有效证明，生动展现了此数据集在发掘多样化且正确的证明策略中的实用价值。本文详述了该数据集的内容构成、其创建所采用的方法及对我们对未来形式验证中机器学习发展方向的启示。此数据集现开放供进一步探究与研究：https://huggingface.co/datasets/florath/coq-facts-props-proofs-gen0-v1

> In the realm of formal theorem proving, the Coq proof assistant stands out for its rigorous approach to verifying mathematical assertions and software correctness. Despite the advances in artificial intelligence and machine learning, the specialized nature of Coq syntax and semantics poses unique challenges for Large Language Models (LLMs). Addressing this gap, we present a comprehensive dataset specifically designed to enhance LLMs' proficiency in interpreting and generating Coq code. This dataset, derived from a collection of over 10,000 Coq source files, encompasses a wide array of propositions, proofs, and definitions, enriched with metadata including source references and licensing information. Our primary aim is to facilitate the development of LLMs capable of generating syntactically correct and semantically meaningful Coq constructs, thereby advancing the frontier of automated theorem proving. Initial experiments with this dataset have showcased its significant potential; models trained on this data exhibited enhanced accuracy in Coq code generation. Notably, a particular experiment revealed that a fine-tuned LLM was capable of generating 141 valid proofs for a basic lemma, highlighting the dataset's utility in facilitating the discovery of diverse and valid proof strategies. This paper discusses the dataset's composition, the methodology behind its creation, and the implications of our findings for the future of machine learning in formal verification. The dataset is accessible for further research and exploration: https://huggingface.co/datasets/florath/coq-facts-props-proofs-gen0-v1

![为了提升形式化定理证明能力，我们构建了一个全面的数据集，专为训练 AI 模型以解析和理解 Coq 代码而设计。](../../../paper_images/2403.12627/proof_string_length_distribution_excluding_outliers.png)

[Arxiv](https://arxiv.org/abs/2403.12627)