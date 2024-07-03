# 精炼学习：借助细粒度自然语言反馈

发布时间：2024年07月02日

`LLM应用` `人工智能`

> Learning to Refine with Fine-Grained Natural Language Feedback

# 摘要

> 近期研究探索了大型语言模型（LLM）在识别并修正自身生成内容中的错误方面的能力。尽管这些改进策略常聚焦于模型大小与问题类型的匹配，却较少关注何种反馈形式最为有效。本研究将反馈驱动的改进分解为三项LLM核心技能：（1）不良生成识别；（2）细致入微的自然语言反馈构建；（3）基于精细反馈的优化。首项技能可由高效判别模型实现，后两项则可通过提示或微调LLM达成。此法之精髓在于，第二步的批评模型能提供针对错误的细致反馈，得益于第一步将判别任务独立处理。实证表明，不同性能级别的模型均能通过此法在提升文档摘要的事实一致性上获益。总体而言，我们所提方法在性能上持续超越传统端到端改进及未专门针对事实核查微调的现存模型。

> Recent work has explored the capability of large language models (LLMs) to identify and correct errors in LLM-generated responses. These refinement approaches frequently evaluate what sizes of models are able to do refinement for what problems, but less attention is paid to what effective feedback for refinement looks like. In this work, we propose looking at refinement with feedback as a composition of three distinct LLM competencies: (1) identification of bad generations; (2) fine-grained natural language feedback generation; (3) refining with fine-grained feedback. The first step can be implemented with a high-performing discriminative model and steps 2 and 3 can be implemented either via prompted or fine-tuned LLMs. A key property of this approach is that the step 2 critique model can give fine-grained feedback about errors, made possible by offloading the discrimination to a separate model in step 1. We show that models of different capabilities benefit from refining with this approach on the task of improving factual consistency of document grounded summaries. Overall, our proposed method consistently outperforms existing end-to-end refinement approaches and current trained models not fine-tuned for factuality critiquing.

[Arxiv](https://arxiv.org/abs/2407.02397)