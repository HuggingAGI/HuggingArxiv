# NYK-MS：一款精心标注的卡通字幕数据集，专为多模态隐喻与讽刺理解而设的基准测试

发布时间：2024年09月02日

`LLM应用` `社交媒体`

> NYK-MS: A Well-annotated Multi-modal Metaphor and Sarcasm Understanding Benchmark on Cartoon-Caption Dataset

# 摘要

> 隐喻与讽刺，这两种修辞手法在日常交流中屡见不鲜，尤其在网络文化和青少年热衷的模因中更为常见。为此，我们精心打造了 NYK-MS 基准，内含 1,583 个隐喻理解样本和 1,578 个讽刺理解样本。这些任务涵盖了识别、定位、解析隐喻与讽刺的各个方面，且每项任务均经过至少三位专家的细致标注。为确保数据质量，我们进行了多轮标注，并借助 GUI 和 GPT-4V 提升效率。实验表明，尽管大型语言模型（LLM）和大型多模态模型（LMM）在零-shot 分类任务上表现平平，但随着模型规模的扩大，其在其他任务上的表现有所提升。此外，通过增强与校准技术，我们验证了 NYK-MS 基准与先前数据集的一致性，并强调了模型对这两种模态理解的重要性。

> Metaphor and sarcasm are common figurative expressions in people's communication, especially on the Internet or the memes popular among teenagers. We create a new benchmark named NYK-MS (NewYorKer for Metaphor and Sarcasm), which contains 1,583 samples for metaphor understanding tasks and 1,578 samples for sarcasm understanding tasks. These tasks include whether it contains metaphor/sarcasm, which word or object contains metaphor/sarcasm, what does it satirize and why does it contains metaphor/sarcasm, all of the 7 tasks are well-annotated by at least 3 annotators. We annotate the dataset for several rounds to improve the consistency and quality, and use GUI and GPT-4V to raise our efficiency. Based on the benchmark, we conduct plenty of experiments. In the zero-shot experiments, we show that Large Language Models (LLM) and Large Multi-modal Models (LMM) can't do classification task well, and as the scale increases, the performance on other 5 tasks improves. In the experiments on traditional pre-train models, we show the enhancement with augment and alignment methods, which prove our benchmark is consistent with previous dataset and requires the model to understand both of the two modalities.

[Arxiv](https://arxiv.org/abs/2409.01037)