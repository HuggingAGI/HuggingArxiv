# 在存储库级别的代码编辑中，推理对于上下文检索的重要性不容忽视。

发布时间：2024年06月06日

`Agent

理由：这篇论文主要关注的是在仓库级别代码编辑任务中，大型语言模型（LLMs）如何进行高效的上下文检索。论文特别强调了将上下文检索任务独立出来进行研究，并探讨了推理在其中的作用。这种对特定任务环节的深入分析和对模型行为的探讨，更符合Agent类别的特征，即关注模型在特定任务中的行为和决策过程。此外，论文中提到的代码编辑任务和上下文检索，通常与智能Agent在复杂环境中的行为和决策相关联。因此，将这篇论文归类为Agent更为合适。` `软件开发` `人工智能`

> On The Importance of Reasoning for Context Retrieval in Repository-Level Code Editing

# 摘要

> 近期，代码流畅的大型语言模型（LLMs）的进步和创新，使得研究者们能够探索仓库级别的代码编辑任务。在这些任务中，模型需根据特定请求，对整个项目的代码库进行导航和修改。这要求模型具备高效的上下文检索能力，即在庞大的代码库中精准定位并收集相关信息。尽管上下文检索的重要性已被广泛认可，但现有研究多采用端到端的方法处理此类任务，导致复杂系统中各组件的具体影响尚不明确。在本研究中，我们特意将上下文检索任务从仓库级别代码编辑的其他环节中独立出来，通过一系列专注于上下文检索的实验，我们旨在揭示这一环节的优势与局限，并探讨推理在其中扮演的角色。实验结果表明，推理虽能提升上下文检索的准确性，但在判断上下文是否充分方面仍显不足。此外，我们还强调了专业工具在上下文收集过程中的关键作用。本文所涉及的代码已公开于 https://github.com/JetBrains-Research/ai-agents-code-editing。

> Recent advancements in code-fluent Large Language Models (LLMs) enabled the research on repository-level code editing. In such tasks, the model navigates and modifies the entire codebase of a project according to request. Hence, such tasks require efficient context retrieval, i.e., navigating vast codebases to gather relevant context. Despite the recognized importance of context retrieval, existing studies tend to approach repository-level coding tasks in an end-to-end manner, rendering the impact of individual components within these complicated systems unclear. In this work, we decouple the task of context retrieval from the other components of the repository-level code editing pipelines. We lay the groundwork to define the strengths and weaknesses of this component and the role that reasoning plays in it by conducting experiments that focus solely on context retrieval. We conclude that while the reasoning helps to improve the precision of the gathered context, it still lacks the ability to identify its sufficiency. We also outline the ultimate role of the specialized tools in the process of context gathering. The code supplementing this paper is available at https://github.com/JetBrains-Research/ai-agents-code-editing.

[Arxiv](https://arxiv.org/abs/2406.04464)