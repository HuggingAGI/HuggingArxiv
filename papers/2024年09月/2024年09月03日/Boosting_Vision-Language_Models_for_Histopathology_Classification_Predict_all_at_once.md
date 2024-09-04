# 增强组织病理学分类中视觉-语言模型的能力：一网打尽式预测

发布时间：2024年09月03日

`LLM应用` `计算机视觉`

> Boosting Vision-Language Models for Histopathology Classification: Predict all at once

# 摘要

> 组织病理学领域的视觉-语言模型 (VLMs) 展现出令人鼓舞的新应用和零-shot 性能。然而，现有方法将大图像分割成小片段，仅进行独立预测的归纳分类。我们通过引入传导方法，利用文本预测和片段间关系，在不增加标签的情况下，充分发挥这些新 VLMs 的零-shot 能力。实验涵盖四个数据集和五种 VLMs，我们的方法在嵌入空间内高效运作，快速处理大量片段，显著提升零-shot 分类准确性。代码已公开，详见 https://github.com/FereshteShakeri/Histo-TransCLIP。

> The development of vision-language models (VLMs) for histo-pathology has shown promising new usages and zero-shot performances. However, current approaches, which decompose large slides into smaller patches, focus solely on inductive classification, i.e., prediction for each patch is made independently of the other patches in the target test data. We extend the capability of these large models by introducing a transductive approach. By using text-based predictions and affinity relationships among patches, our approach leverages the strong zero-shot capabilities of these new VLMs without any additional labels. Our experiments cover four histopathology datasets and five different VLMs. Operating solely in the embedding space (i.e., in a black-box setting), our approach is highly efficient, processing $10^5$ patches in just a few seconds, and shows significant accuracy improvements over inductive zero-shot classification. Code available at https://github.com/FereshteShakeri/Histo-TransCLIP.

[Arxiv](https://arxiv.org/abs/2409.01883)