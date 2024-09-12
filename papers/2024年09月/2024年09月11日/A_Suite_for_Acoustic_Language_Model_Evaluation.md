# 声学语言模型评估工具集

发布时间：2024年09月11日

`LLM应用` `语音处理` `人工智能`

> A Suite for Acoustic Language Model Evaluation

# 摘要

> 语音语言模型近期展现出成为通用语音处理系统的巨大潜力，能够捕捉音频信号中的丰富声学信息，如情感和背景噪音。然而，现有的评估基准未能全面考量这些声学特征。为此，我们推出了 SALMon，一个涵盖背景噪音、情感、说话者身份和房间脉冲响应的综合评估套件。SALMon 不仅评估模型对声学特征的捕捉能力，还检验其与口语内容的匹配度。我们采用基于模型的方法，通过比较正确与错误样本的得分，快速评估大型模型的性能。在 SALMon 上测试多个语音语言模型后，我们揭示了各方法的优劣。代码和数据已公开，访问地址为 https://pages.cs.huji.ac.il/adiyoss-lab/salmon/。

> Speech language models have recently demonstrated great potential as universal speech processing systems. Such models have the ability to model the rich acoustic information existing in audio signals, beyond spoken content, such as emotion, background noise, etc. Despite this, evaluation benchmarks which evaluate awareness to a wide range of acoustic aspects, are lacking. To help bridge this gap, we introduce SALMon, a novel evaluation suite encompassing background noise, emotion, speaker identity and room impulse response. The proposed benchmarks both evaluate the consistency of the inspected element and how much it matches the spoken text. We follow a modelling based approach, measuring whether a model gives correct samples higher scores than incorrect ones. This approach makes the benchmark fast to compute even for large models. We evaluated several speech language models on SALMon, thus highlighting the strengths and weaknesses of each evaluated method. Code and data are publicly available at https://pages.cs.huji.ac.il/adiyoss-lab/salmon/ .

[Arxiv](https://arxiv.org/abs/2409.07437)