# 分散再融合：通过降低对齐成本，拓展指令调优的边界

发布时间：2024年05月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在监督微调（SFT）过程中的问题，即知识和推理能力的下降，并提出了一种新的分散-合并框架来解决这一问题。这涉及到对LLMs内部机制和训练过程的深入分析，属于理论研究的范畴，因此应归类为LLM理论。` `人工智能` `语言模型`

> Disperse-Then-Merge: Pushing the Limits of Instruction Tuning via Alignment Tax Reduction

# 摘要

> 监督微调（SFT）是让大型语言模型（LLMs）遵循指令的关键步骤，但后期常导致知识和推理能力下降，这被称为对齐税。我们的初步研究发现，数据偏差可能是罪魁祸首。为此，我们提出了一种简单却高效的分散-合并框架：首先将指令数据分割，训练多个子模型，再通过模型合并技术整合它们。这一策略在多个知识和推理测试中，轻松超越了复杂的数据处理和训练方法。

> Supervised fine-tuning (SFT) on instruction-following corpus is a crucial approach toward the alignment of large language models (LLMs). However, the performance of LLMs on standard knowledge and reasoning benchmarks tends to suffer from deterioration at the latter stage of the SFT process, echoing the phenomenon of alignment tax. Through our pilot study, we put a hypothesis that the data biases are probably one cause behind the phenomenon. To address the issue, we introduce a simple disperse-then-merge framework. To be concrete, we disperse the instruction-following data into portions and train multiple sub-models using different data portions. Then we merge multiple models into a single one via model merging techniques. Despite its simplicity, our framework outperforms various sophisticated methods such as data curation and training regularization on a series of standard knowledge and reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2405.13432)