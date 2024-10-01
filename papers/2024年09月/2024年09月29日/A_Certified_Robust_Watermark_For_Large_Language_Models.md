# 大型语言模型的认证鲁棒水印技术

发布时间：2024年09月29日

`LLM应用` `网络安全` `人工智能`

> A Certified Robust Watermark For Large Language Models

# 摘要

> AI生成文本识别中的水印算法备受瞩目，众多算法被提出以抵御各种攻击。然而，这些算法仍易受新型攻击。为此，我们首创了基于随机平滑的大语言模型认证鲁棒水印算法，为水印文本提供坚实保障。我们采用双模型分别负责生成与检测，并在训练与推理阶段分别引入高斯与均匀噪声，以强化认证鲁棒性并推导认证半径。实验结果显示，我们的算法不仅性能媲美基线，更能在显著改动下保持水印的稳固。

> The effectiveness of watermark algorithms in AI-generated text identification has garnered significant attention. Concurrently, an increasing number of watermark algorithms have been proposed to enhance the robustness against various watermark attacks. However, these watermark algorithms remain susceptible to adaptive or unseen attacks. To address this issue, to our best knowledge, we propose the first certified robust watermark algorithm for large language models based on randomized smoothing, which can provide provable guarantees for watermarked text. Specifically, we utilize two different models respectively for watermark generation and detection and add Gaussian and Uniform noise respectively in the embedding and permutation space during the training and inference stages of the watermark detector to enhance the certified robustness of our watermark detector and derive certified radius. To evaluate the empirical robustness and certified robustness of our watermark algorithm, we conducted comprehensive experiments. The results indicate that our watermark algorithm shows comparable performance to baseline algorithms while our algorithm can derive substantial certified robustness, which means that our watermark can not be removed even under significant alterations.

[Arxiv](https://arxiv.org/abs/2409.19708)