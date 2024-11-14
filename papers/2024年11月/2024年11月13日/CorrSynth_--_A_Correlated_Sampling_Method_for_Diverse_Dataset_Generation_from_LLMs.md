# CorrSynth -- 一种用于从大型语言模型生成多样化数据集的相关采样方法

发布时间：2024年11月13日

`LLM应用` `语言模型` `数据合成`

> CorrSynth -- A Correlated Sampling Method for Diverse Dataset Generation from LLMs

# 摘要

> 大型语言模型（LLMs）在使用零样本和少样本提示的各种任务中表现出了显著的性能。尽管近年来对它们的数据合成能力进行了深入研究，但生成的数据存在多样性不足、对提示的遵循度较低以及从生成器模型潜入数据的潜在偏差等问题。在这项工作中，我们应对生成具有高多样性数据集的挑战，基于此训练学生模型以用于下游任务。通过采用基于解码时间指导的方法，我们提出了 CorrSynth，它使用相关采样策略生成更具多样性且更忠实于输入提示的数据。此外，我们的方法克服了其他一些基于指导的技术（如基于分类器的指导）的复杂性缺陷。通过大量实验，我们展示了我们方法的有效性并证实了我们的主张。特别是，我们进行了内在评估以展示多样性方面的改进。我们的实验表明，CorrSynth 在四个数据集上相对于竞争基线提高了学生指标和内在指标，显示了我们方法的内在优势。

> Large language models (LLMs) have demonstrated remarkable performance in diverse tasks using zero-shot and few-shot prompting. Even though their capabilities of data synthesis have been studied well in recent years, the generated data suffers from a lack of diversity, less adherence to the prompt, and potential biases that creep into the data from the generator model. In this work, we tackle the challenge of generating datasets with high diversity, upon which a student model is trained for downstream tasks. Taking the route of decoding-time guidance-based approaches, we propose CorrSynth, which generates data that is more diverse and faithful to the input prompt using a correlated sampling strategy. Further, our method overcomes the complexity drawbacks of some other guidance-based techniques like classifier-based guidance. With extensive experiments, we show the effectiveness of our approach and substantiate our claims. In particular, we perform intrinsic evaluation to show the improvements in diversity. Our experiments show that CorrSynth improves both student metrics and intrinsic metrics upon competitive baselines across four datasets, showing the innate advantage of our method.

[Arxiv](https://arxiv.org/abs/2411.08553)