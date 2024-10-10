# 深度学习中的二阶优化器，具备自适应梯度缩放功能

发布时间：2024年10月08日

`LLM理论` `机器学习`

> A second-order-like optimizer with adaptive gradient scaling for deep learning

# 摘要

> 本文介绍了一种名为 INNAprop 的优化算法，它融合了 INNA 方法与 RMSprop 的自适应梯度缩放，既利用了二阶信息和重缩放，又保持了与 AdamW 或带动量的 SGD 等标准深度学习方法相当的内存需求。在回顾了其几何原理后，我们进行了广泛的实验。结果显示，在图像分类（如 CIFAR-10 和 ImageNet）和语言建模（如 GPT-2）任务中，INNAprop 在训练速度和准确性上均不逊色于甚至超越了 AdamW，且在大规模应用中仅需微调少量超参数。代码已公开，详见 \url{https://github.com/innaprop/innaprop}。

> In this empirical article, we introduce INNAprop, an optimization algorithm that combines the INNA method with the RMSprop adaptive gradient scaling. It leverages second-order information and rescaling while keeping the memory requirements of standard DL methods as AdamW or SGD with momentum.After having recalled our geometrical motivations, we provide quite extensive experiments. On image classification (CIFAR-10, ImageNet) and language modeling (GPT-2), INNAprop consistently matches or outperforms AdamW both in training speed and accuracy, with minimal hyperparameter tuning in large-scale settings. Our code is publicly available at \url{https://github.com/innaprop/innaprop}.

[Arxiv](https://arxiv.org/abs/2410.05871)