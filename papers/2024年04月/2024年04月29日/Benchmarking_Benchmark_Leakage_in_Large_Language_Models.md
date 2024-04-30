# 在大型语言模型中，对基准测试泄露问题进行评估

发布时间：2024年04月29日

`LLM理论` `基准测试`

> Benchmarking Benchmark Leakage in Large Language Models

# 摘要

> 随着预训练数据的广泛应用，基准数据集泄露的问题日益凸显，尤其是在大型语言模型（LLMs）的训练过程中，监督数据的不透明使用加剧了这一现象。这不仅影响了基准测试的公正性，也可能导致不公平的比较，从而阻碍了语言模型领域的进步。为此，我们提出了一种基于困惑度和N-gram精确度的检测流程，用以评估模型在基准测试上的预测精度，并识别可能的数据泄露问题。通过对31个LLMs在数学推理任务中的分析，我们发现了大量的训练集甚至测试集的不当使用情况，这些问题可能导致不公平的比较结果。基于这些发现，我们提出了一系列建议，涉及模型文档编制、基准测试设置以及未来评估方法。特别地，我们建议引入“基准透明度卡”，以促进对基准测试使用情况的清晰记录，增强LLMs的透明度和健康发展。我们还公开了排行榜、检测流程的实现以及模型预测结果，以支持未来的研究工作。

> Amid the expanding use of pre-training data, the phenomenon of benchmark dataset leakage has become increasingly prominent, exacerbated by opaque training processes and the often undisclosed inclusion of supervised data in contemporary Large Language Models (LLMs). This issue skews benchmark effectiveness and fosters potentially unfair comparisons, impeding the field's healthy development. To address this, we introduce a detection pipeline utilizing Perplexity and N-gram accuracy, two simple and scalable metrics that gauge a model's prediction precision on benchmark, to identify potential data leakages. By analyzing 31 LLMs under the context of mathematical reasoning, we reveal substantial instances of training even test set misuse, resulting in potentially unfair comparisons. These findings prompt us to offer several recommendations regarding model documentation, benchmark setup, and future evaluations. Notably, we propose the "Benchmark Transparency Card" to encourage clear documentation of benchmark utilization, promoting transparency and healthy developments of LLMs. we have made our leaderboard, pipeline implementation, and model predictions publicly available, fostering future research.

[Arxiv](https://arxiv.org/abs/2404.18824)