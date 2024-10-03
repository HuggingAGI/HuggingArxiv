# 知识追踪中的自动概念注释与问题表示学习

发布时间：2024年10月02日

`LLM应用` `人工智能`

> Automated Knowledge Concept Annotation and Question Representation Learning for Knowledge Tracing

# 摘要

> 知识追踪 (KT) 是跟踪学生学习进度的一种流行方法，有助于实现更个性化的学习体验。然而，现有 KT 方法存在两大局限：一是过度依赖专家定义的知识概念 (KCs)，耗时且易错；二是忽视了问题和 KCs 的语义。为此，我们提出了 KCQRL 框架，通过自动化知识概念注释和问题表示学习，提升现有 KT 模型的效果。首先，我们利用大型语言模型 (LLMs) 自动生成问题解决方案并注释 KCs。其次，采用对比学习方法生成语义丰富的嵌入，通过定制的假负例消除方法与 KCs 对齐。这些嵌入可直接替代现有 KT 模型中的随机初始化嵌入。实验证明，KCQRL 在两个大型数学学习数据集上的 15 种 KT 算法中均表现出色，性能显著提升。

> Knowledge tracing (KT) is a popular approach for modeling students' learning progress over time, which can enable more personalized and adaptive learning. However, existing KT approaches face two major limitations: (1) they rely heavily on expert-defined knowledge concepts (KCs) in questions, which is time-consuming and prone to errors; and (2) KT methods tend to overlook the semantics of both questions and the given KCs. In this work, we address these challenges and present KCQRL, a framework for automated knowledge concept annotation and question representation learning that can improve the effectiveness of any existing KT model. First, we propose an automated KC annotation process using large language models (LLMs), which generates question solutions and then annotates KCs in each solution step of the questions. Second, we introduce a contrastive learning approach to generate semantically rich embeddings for questions and solution steps, aligning them with their associated KCs via a tailored false negative elimination approach. These embeddings can be readily integrated into existing KT models, replacing their randomly initialized embeddings. We demonstrate the effectiveness of KCQRL across 15 KT algorithms on two large real-world Math learning datasets, where we achieve consistent performance improvements.

[Arxiv](https://arxiv.org/abs/2410.01727)