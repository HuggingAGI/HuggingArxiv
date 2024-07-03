# GPTCast：一款专为降水实时预报设计的天气语言模型

发布时间：2024年07月02日

`LLM应用` `气象学`

> GPTCast: a weather language model for precipitation nowcasting

# 摘要

> GPTCast 是一种创新的深度学习方法，用于基于雷达的降水集合临近预报，灵感源自大型语言模型的进步。我们利用 GPT 模型通过标记化的雷达图像学习降水的时空动态。标记器采用量化变分自编码器，并引入一种新的重建损失，专门针对降水的偏斜分布，确保对高降雨率的准确重建。该方法不仅生成逼真的集合预报，还提供精确的不确定性估计。模型训练完全基于数据，无需随机性，所有变异性均从数据中学习并在推理时展现，以生成集合。通过在意大利北部艾米利亚-罗马涅地区 6 年的雷达数据集上训练和测试，GPTCast 展现出超越现有集合外推方法的优越性能。

> This work introduces GPTCast, a generative deep-learning method for ensemble nowcast of radar-based precipitation, inspired by advancements in large language models (LLMs). We employ a GPT model as a forecaster to learn spatiotemporal precipitation dynamics using tokenized radar images. The tokenizer is based on a Quantized Variational Autoencoder featuring a novel reconstruction loss tailored for the skewed distribution of precipitation that promotes faithful reconstruction of high rainfall rates. The approach produces realistic ensemble forecasts and provides probabilistic outputs with accurate uncertainty estimation. The model is trained without resorting to randomness, all variability is learned solely from the data and exposed by model at inference for ensemble generation. We train and test GPTCast using a 6-year radar dataset over the Emilia-Romagna region in Northern Italy, showing superior results compared to state-of-the-art ensemble extrapolation methods.

[Arxiv](https://arxiv.org/abs/2407.02089)