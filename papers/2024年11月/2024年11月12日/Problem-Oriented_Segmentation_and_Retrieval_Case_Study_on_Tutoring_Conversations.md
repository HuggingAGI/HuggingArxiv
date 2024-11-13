# 面向问题的分割和检索：关于辅导对话的案例研究

发布时间：2024年11月12日

`LLM应用` `对话结构`

> Problem-Oriented Segmentation and Retrieval: Case Study on Tutoring Conversations

# 摘要

> 许多开放式对话（例如，辅导课程或商务会议）都围绕着预先定义的参考资料，如工作表或会议要点。为了为研究这种对话结构提供一个框架，我们引入了面向问题的分割和检索（POSR），即共同将对话分解为段，并将每个段与相关的参考项目链接的任务。作为一个案例研究，我们将 POSR 应用于教育领域，在那里围绕问题有效地构建课程至关重要但又困难。我们提出了 LessonLink，这是第一个真实世界辅导课程的数据集，具有 3500 个段，涵盖 24300 分钟的教学，并与 116 个 SAT 数学问题相关联。我们为 POSR 定义和评估了几种联合和独立的方法，包括分割（例如，TextTiling）、检索（例如，ColBERT）和大型语言模型（LLM）方法。我们的结果强调，将 POSR 建模为一个联合任务是必不可少的：POSR 方法在联合指标上比独立的分割和检索管道高出多达 +76％，在分割指标上比传统的分割方法高出多达 +78％。我们展示了 POSR 对下游教育应用的实际影响，得出了关于现实世界课程结构中语言和时间使用的新见解。

> Many open-ended conversations (e.g., tutoring lessons or business meetings) revolve around pre-defined reference materials, like worksheets or meeting bullets. To provide a framework for studying such conversation structure, we introduce Problem-Oriented Segmentation & Retrieval (POSR), the task of jointly breaking down conversations into segments and linking each segment to the relevant reference item. As a case study, we apply POSR to education where effectively structuring lessons around problems is critical yet difficult. We present LessonLink, the first dataset of real-world tutoring lessons, featuring 3,500 segments, spanning 24,300 minutes of instruction and linked to 116 SAT math problems. We define and evaluate several joint and independent approaches for POSR, including segmentation (e.g., TextTiling), retrieval (e.g., ColBERT), and large language models (LLMs) methods. Our results highlight that modeling POSR as one joint task is essential: POSR methods outperform independent segmentation and retrieval pipelines by up to +76% on joint metrics and surpass traditional segmentation methods by up to +78% on segmentation metrics. We demonstrate POSR's practical impact on downstream education applications, deriving new insights on the language and time use in real-world lesson structures.

[Arxiv](https://arxiv.org/abs/2411.07598)