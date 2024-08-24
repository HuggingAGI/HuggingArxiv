# Xinyu：一款基于大型语言模型的高效系统，专为评论生成而设计。

发布时间：2024年08月21日

`LLM应用` `新闻传媒` `教育培训`

> Xinyu: An Efficient LLM-based System for Commentary Generation

# 摘要

> 评论通过呈现多元论据，助读者深入洞察事件。然而，评论创作对熟练者亦显耗时。大型语言模型虽简化语言生成，但直用于评论仍遇挑战，因其独特需求：基本需结构严谨、逻辑连贯；高级需优质论点、有力证据。本文推出Xinyu系统，基于LLM，助评论员高效产中文评论。为达基本要求，我们细分生成流程，定制策略与监督微调。针对高级要求，我们创论点排序模型，建含最新事件与经典书籍的证据库，以检索增强生成技术强化证据支撑。为公正评评论，我们设综合指标，涵盖五维视角。实验证系统效能，评论员实操效率大增，创作时间由四小时缩至二十分钟，且质量未损。

> Commentary provides readers with a deep understanding of events by presenting diverse arguments and evidence. However, creating commentary is a time-consuming task, even for skilled commentators. Large language models (LLMs) have simplified the process of natural language generation, but their direct application in commentary creation still faces challenges due to unique task requirements. These requirements can be categorized into two levels: 1) fundamental requirements, which include creating well-structured and logically consistent narratives, and 2) advanced requirements, which involve generating quality arguments and providing convincing evidence. In this paper, we introduce Xinyu, an efficient LLM-based system designed to assist commentators in generating Chinese commentaries. To meet the fundamental requirements, we deconstruct the generation process into sequential steps, proposing targeted strategies and supervised fine-tuning (SFT) for each step. To address the advanced requirements, we present an argument ranking model for arguments and establish a comprehensive evidence database that includes up-to-date events and classic books, thereby strengthening the substantiation of the evidence with retrieval augmented generation (RAG) technology. To evaluate the generated commentaries more fairly, corresponding to the two-level requirements, we introduce a comprehensive evaluation metric that considers five distinct perspectives in commentary generation. Our experiments confirm the effectiveness of our proposed system. We also observe a significant increase in the efficiency of commentators in real-world scenarios, with the average time spent on creating a commentary dropping from 4 hours to 20 minutes. Importantly, such an increase in efficiency does not compromise the quality of the commentaries.

[Arxiv](https://arxiv.org/abs/2408.11609)