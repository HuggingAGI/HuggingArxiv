# 大型语言模型面临的问题：是多语言指令调优的数据质量不佳，还是多语言评估本身存在缺陷？

发布时间：2024年06月18日

`LLM理论

这篇论文主要探讨了大型多语言模型在微调和评估过程中对翻译数据的依赖性及其对模型性能的影响。研究通过实验比较了使用母语数据和翻译数据在指令调整和评估阶段的效果，并探讨了正则化技术在不同类型任务中的作用。这些问题和实验设计更多地关注于LLM的理论层面，即如何优化和理解模型的内部机制和性能，而不是直接应用或Agent的行为。因此，将其归类为LLM理论是合适的。` `语言模型`

> Is It Good Data for Multilingual Instruction Tuning or Just Bad Multilingual Evaluation for Large Language Models?

# 摘要

> 大型多语言模型本应服务于各语言母语者，但当前的微调和评估方法可能因过度依赖翻译而偏离初衷，导致翻译瑕疵影响模型表现。我们尚不清楚指令数据的性质如何影响模型输出，也质疑翻译测试集能否准确捕捉细微差别。由于两阶段频繁使用翻译数据，这些问题可能被忽视。本研究通过控制使用母语或翻译数据，在指令调整和评估阶段进行实验，观察模型表现。对八个模型和八个基准的测试显示，在模型性能较高时，母语或生成基准能明显区分母语与翻译指令数据的差异，而其他测试集则不然。最后，我们发现正则化有助于在结构化任务而非生成任务中缩小这一差距。

> Large language models, particularly multilingual ones, are designed, claimed, and expected to cater to native speakers of varied languages. We hypothesise that the current practices of fine-tuning and evaluating these models may mismatch this intention owing to a heavy reliance on translation, which can introduce translation artefacts and defects. It remains unknown whether the nature of the instruction data has an impact on the model output; on the other hand, it remains questionable whether translated test sets can capture such nuances. Due to the often coupled practices of using translated data in both stages, such imperfections could have been overlooked. This work investigates these issues by using controlled native or translated data during instruction tuning and evaluation stages and observing model results. Experiments on eight base models and eight different benchmarks reveal that native or generation benchmarks display a notable difference between native and translated instruction data especially when model performance is high, whereas other types of test sets cannot. Finally, we demonstrate that regularization is beneficial to bridging this gap on structured but not generative tasks.

[Arxiv](https://arxiv.org/abs/2406.12822)