# 针对 CLIP 的联合视觉语言社会偏差去除

发布时间：2024年11月19日

`LLM应用` `计算机视觉` `多模态`

> Joint Vision-Language Social Bias Removal for CLIP

# 摘要

> 视觉语言（V-L）预训练模型，比如 CLIP，在各类下游任务中表现出色。但 V-L 模型一直受固有社会偏见所限。典型的情况是，V-L 模型常对特定人群做出有偏差的预测，严重影响其在现实中的应用。现有的方法试图从模型嵌入中剔除有偏差的属性信息，以减轻 V-L 模型的社会偏见问题。然而，我们重新审视这些方法后发现，去偏往往伴随着 V-L 对齐能力的大幅降低。接着我们指出，这种性能下降是由于图像和文本嵌入的去偏不平衡导致的。为解决此问题，我们提出了一个新颖的 V-L 去偏框架，先对齐图像和文本的偏差，再将其从两种模态中去除。如此一来，我们的方法在减轻多模态偏差的同时，能在去偏嵌入中保持 V-L 对齐。另外，我们倡导一种新的评估协议，它能够 1）全面量化模型的去偏和 V-L 对齐能力，2）评估社会偏差去除模型的泛化性。我们相信，这项工作会为未来解决 CLIP 中的社会偏见问题的研究带来新的启发和指引。

> Vision-Language (V-L) pre-trained models such as CLIP show prominent capabilities in various downstream tasks. Despite this promise, V-L models are notoriously limited by their inherent social biases. A typical demonstration is that V-L models often produce biased predictions against specific groups of people, significantly undermining their real-world applicability. Existing approaches endeavor to mitigate the social bias problem in V-L models by removing biased attribute information from model embeddings. However, after our revisiting of these methods, we find that their bias removal is frequently accompanied by greatly compromised V-L alignment capabilities. We then reveal that this performance degradation stems from the unbalanced debiasing in image and text embeddings. To address this issue, we propose a novel V-L debiasing framework to align image and text biases followed by removing them from both modalities. By doing so, our method achieves multi-modal bias mitigation while maintaining the V-L alignment in the debiased embeddings. Additionally, we advocate a new evaluation protocol that can 1) holistically quantify the model debiasing and V-L alignment ability, and 2) evaluate the generalization of social bias removal models. We believe this work will offer new insights and guidance for future studies addressing the social bias problem in CLIP.

[Arxiv](https://arxiv.org/abs/2411.12785)