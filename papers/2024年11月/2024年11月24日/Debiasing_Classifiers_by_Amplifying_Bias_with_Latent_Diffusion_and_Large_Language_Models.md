# 利用潜在扩散和大型语言模型放大偏差以消除分类器的偏差

发布时间：2024年11月24日

`其他` `图像分类` `生成模型`

> Debiasing Classifiers by Amplifying Bias with Latent Diffusion and Large Language Models

# 摘要

> 神经网络一旦学到偏差并被误导产生相关性，在图像分类时就会遭遇困境，进而影响其泛化能力和性能表现。以往的方法要么需要属性标签（比如背景、颜色），要么借助生成对抗网络（GANs）来降低偏差。我们推出了 DiffuBias，这是一种用于文本到图像生成的全新流程，它通过生成偏差冲突样本增强分类器的稳健性，且生成阶段无需训练。借助预训练的扩散和图像描述模型，DiffuBias 生成能够挑战分类器偏差的图像，利用有偏差的分类器（$f_B$）的前$K$个损失来创建更具代表性的数据样本。该方法不仅能有效去偏差，还能提升分类器的泛化能力。据我们了解，DiffuBias 是首个在去偏差任务中运用稳定扩散模型生成偏差冲突样本的方法。我们全面的实验评估显示，DiffuBias 在基准数据集上取得了最先进的性能。我们还针对碳排放和能源消耗对各类生成模型进行了对比分析，以突显计算效率的重要性。

> Neural networks struggle with image classification when biases are learned and misleads correlations, affecting their generalization and performance. Previous methods require attribute labels (e.g. background, color) or utilizes Generative Adversarial Networks (GANs) to mitigate biases. We introduce DiffuBias, a novel pipeline for text-to-image generation that enhances classifier robustness by generating bias-conflict samples, without requiring training during the generation phase. Utilizing pretrained diffusion and image captioning models, DiffuBias generates images that challenge the biases of classifiers, using the top-$K$ losses from a biased classifier ($f_B$) to create more representative data samples. This method not only debiases effectively but also boosts classifier generalization capabilities. To the best of our knowledge, DiffuBias is the first approach leveraging a stable diffusion model to generate bias-conflict samples in debiasing tasks. Our comprehensive experimental evaluations demonstrate that DiffuBias achieves state-of-the-art performance on benchmark datasets. We also conduct a comparative analysis of various generative models in terms of carbon emissions and energy consumption to highlight the significance of computational efficiency.

[Arxiv](https://arxiv.org/abs/2411.16079)