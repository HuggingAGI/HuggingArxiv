# AstroMLab 2：探索 AstroLLaMA-2-70B 模型及天文学专用 LLM 的性能基准

发布时间：2024年09月29日

`LLM应用` `天文学` `人工智能`

> AstroMLab 2: AstroLLaMA-2-70B Model and Benchmarking Specialised LLMs for Astronomy

# 摘要

> 在特定领域数据上持续预训练大型语言模型，旨在提升其在下游任务中的表现。然而，在天文学领域，缺乏专门的基准测试，使得对这些专业模型的评估变得困难。本研究利用近期的高质量天文学 MCQ 数据，对专业 LLM 进行量化评估。结果显示，基于 LLaMA-2-7B 的 AstroLLaMA 系列性能不及基础模型。通过使用高质量数据进行持续预训练，如 arXiv 的摘要文本，可以部分缓解这一问题。尽管小模型中存在灾难性遗忘现象，但在 70B 模型上的持续预训练仍能带来显著提升。然而，当前的监督微调数据集仍限制了指导模型的性能。为此，我们推出了 AstroLLaMA-3-8B 和 AstroLLaMA-2-70B 新模型，进一步优化了天文学领域的 LLM 性能。

> Continual pretraining of large language models on domain-specific data has been proposed to enhance performance on downstream tasks. In astronomy, the previous absence of astronomy-focused benchmarks has hindered objective evaluation of these specialized LLM models. Leveraging a recent initiative to curate high-quality astronomical MCQs, this study aims to quantitatively assess specialized LLMs in astronomy. We find that the previously released AstroLLaMA series, based on LLaMA-2-7B, underperforms compared to the base model. We demonstrate that this performance degradation can be partially mitigated by utilizing high-quality data for continual pretraining, such as summarized text from arXiv. Despite the observed catastrophic forgetting in smaller models, our results indicate that continual pretraining on the 70B model can yield significant improvements. However, the current supervised fine-tuning dataset still constrains the performance of instruct models. In conjunction with this study, we introduce a new set of models, AstroLLaMA-3-8B and AstroLLaMA-2-70B, building upon the previous AstroLLaMA series.

[Arxiv](https://arxiv.org/abs/2409.19750)