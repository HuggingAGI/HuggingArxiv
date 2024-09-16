# 在大型语言模型中，上下文虽能引领方向，但参数化记忆却紧随其后。

发布时间：2024年09月12日

`LLM理论` `人工智能`

> When Context Leads but Parametric Memory Follows in Large Language Models

# 摘要

> 大型语言模型 (LLM) 在利用多样化知识源方面取得了显著进展。本研究探讨了九种常用 LLM 在回答开放性问题时，如何在本地上下文和全局参数之间分配知识。我们引入了新数据集 WikiAtomic，并系统调整上下文大小，分析 LLM 在知识一致性场景中如何利用信息和参数化知识。此外，我们还研究了不同上下文大小下的幻觉倾向。研究发现，模型普遍依赖约70%的上下文和30%的参数化知识，且幻觉随上下文增加而减少。这些发现强调了优化上下文组织和开发更确定性使用输入的模型的重要性。

> Large language models (LLMs) have demonstrated remarkable progress in leveraging diverse knowledge sources. This study investigates how nine widely used LLMs allocate knowledge between local context and global parameters when answering open-ended questions in knowledge-consistent scenarios. We introduce a novel dataset, WikiAtomic, and systematically vary context sizes to analyze how LLMs prioritize and utilize the provided information and their parametric knowledge in knowledge-consistent scenarios. Additionally, we also study their tendency to hallucinate under varying context sizes. Our findings reveal consistent patterns across models, including a consistent reliance on both contextual (around 70%) and parametric (around 30%) knowledge, and a decrease in hallucinations with increasing context. These insights highlight the importance of more effective context organization and developing models that use input more deterministically for robust performance.

[Arxiv](https://arxiv.org/abs/2409.08435)