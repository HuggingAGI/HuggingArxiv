# 大型语言模型面临的问题：是多语言指令调优的数据质量不佳，还是多语言评估本身存在缺陷？

发布时间：2024年06月18日

`LLM理论

这篇论文主要探讨了大型多语言模型在训练和评估过程中使用翻译数据的问题，以及这些数据如何影响模型的性能。研究通过实验比较了使用母语数据和翻译数据在模型训练和评估中的效果，并探讨了正则化技术在不同任务类型中的应用效果。这些问题和实验结果对于理解大型语言模型（LLM）的理论基础和性能优化具有重要意义，因此将其归类为LLM理论。` `语言模型` `机器翻译`

> Is It Good Data for Multilingual Instruction Tuning or Just Bad Multilingual Evaluation for Large Language Models?

# 摘要

> 大型多语言模型本应服务于各种语言的母语者，但当前的微调和评估方法可能因过度依赖翻译而偏离初衷，导致翻译瑕疵影响模型表现。我们尚不清楚指令数据的性质如何影响模型输出，也质疑翻译测试集能否准确捕捉细微差别。由于在模型训练和评估中频繁使用翻译数据，这些潜在问题可能被忽略。本研究通过在指令调整和评估阶段使用受控的母语或翻译数据，并观察模型表现，来探讨这些问题。实验涵盖八个基础模型和八个基准，发现当模型性能较高时，母语或生成基准能明显区分母语和翻译指令数据，而其他测试集则不然。最后，我们发现正则化在结构化任务中有效弥合了这一差距，但在生成任务中效果有限。

> Large language models, particularly multilingual ones, are designed, claimed, and expected to cater to native speakers of varied languages. We hypothesise that the current practices of fine-tuning and evaluating these models may mismatch this intention owing to a heavy reliance on translation, which can introduce translation artefacts and defects. It remains unknown whether the nature of the instruction data has an impact on the model output; on the other hand, it remains questionable whether translated test sets can capture such nuances. Due to the often coupled practices of using translated data in both stages, such imperfections could have been overlooked. This work investigates these issues by using controlled native or translated data during instruction tuning and evaluation stages and observing model results. Experiments on eight base models and eight different benchmarks reveal that native or generation benchmarks display a notable difference between native and translated instruction data especially when model performance is high, whereas other types of test sets cannot. Finally, we demonstrate that regularization is beneficial to bridging this gap on structured but not generative tasks.

[Arxiv](https://arxiv.org/abs/2406.12822)