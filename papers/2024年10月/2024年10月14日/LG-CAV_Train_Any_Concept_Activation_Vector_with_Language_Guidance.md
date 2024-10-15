# LG-CAV：借助语言指导，轻松训练任意概念激活向量

发布时间：2024年10月14日

`LLM应用` `人工智能` `计算机视觉`

> LG-CAV: Train Any Concept Activation Vector with Language Guidance

# 摘要

> 概念激活向量 (CAV) 通过将模型预测归因于特定概念，在可解释 AI 领域备受关注。然而，CAV 的训练需要大量高质量图像，这些图像的收集成本高昂，限制了其应用范围。为此，我们提出语言引导的 CAV (LG-CAV)，利用预训练视觉-语言模型 (如 CLIP) 中的丰富概念知识，无需标签数据即可训练 CAV。通过计算概念描述在共同图像池上的激活值，我们将其作为语言指导来训练 LG-CAV，从而弥合视觉-语言模型与目标模型之间的差距。此外，我们还提出激活样本重加权 (ASR)，作为一种模型校正技术，进一步提升目标模型性能。实验证明，LG-CAV 在任何概念下均显著优于以往方法，且我们的模型校正方法达到了最先进水平。代码已开源，详见 https://github.com/hqhQAQ/LG-CAV。

> Concept activation vector (CAV) has attracted broad research interest in explainable AI, by elegantly attributing model predictions to specific concepts. However, the training of CAV often necessitates a large number of high-quality images, which are expensive to curate and thus limited to a predefined set of concepts. To address this issue, we propose Language-Guided CAV (LG-CAV) to harness the abundant concept knowledge within the certain pre-trained vision-language models (e.g., CLIP). This method allows training any CAV without labeled data, by utilizing the corresponding concept descriptions as guidance. To bridge the gap between vision-language model and the target model, we calculate the activation values of concept descriptions on a common pool of images (probe images) with vision-language model and utilize them as language guidance to train the LG-CAV. Furthermore, after training high-quality LG-CAVs related to all the predicted classes in the target model, we propose the activation sample reweighting (ASR), serving as a model correction technique, to improve the performance of the target model in return. Experiments on four datasets across nine architectures demonstrate that LG-CAV achieves significantly superior quality to previous CAV methods given any concept, and our model correction method achieves state-of-the-art performance compared to existing concept-based methods. Our code is available at https://github.com/hqhQAQ/LG-CAV.

[Arxiv](https://arxiv.org/abs/2410.10308)