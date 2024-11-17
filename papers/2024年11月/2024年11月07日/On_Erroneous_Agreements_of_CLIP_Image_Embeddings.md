# 有关 CLIP 图像嵌入的错误协定

发布时间：2024年11月07日

`LLM应用` `计算机视觉` `多模态模型`

> On Erroneous Agreements of CLIP Image Embeddings

# 摘要

> 近期研究显示，视觉语言模型（VLMs）在视觉推理上的失败往往源于错误的一致性，即语义不同的图像被CLIP图像编码器模糊编码为具有高余弦相似度的嵌入。在本文中，我们指出错误的一致性并非总是主因，因为多模态大型语言模型（MLLMs）仍能从中提取出不同信息。比如，在What'sUp基准中区分左右物体时，左右对的CLIP图像嵌入平均余弦相似度大于0.99，CLIP表现随机；但使用相同CLIP图像编码器的LLaVA-1.5-7B准确率近乎100%。我们发现CLIP图像嵌入中可提取的信息可能被其不充分的视觉语言对齐所遮蔽：通过对比目标学习的匹配分数或许无法涵盖所有不同的图像与文本对应关系。我们还对MMVP基准进行了研究，此前的工作表明LLaVA-1.5无法区分具有高余弦相似度的图像对。我们观察到通过替代解码算法更关注视觉输入能带来性能提升。另外，如果模型能将两张图像作为输入以突出它们的细微差别，准确率会显著提高。这两项发现均表明LLaVA-1.5未充分利用提取的视觉信息。总之，我们的研究结果表明，虽然改进图像编码器对VLMs有益，但通过采用更优的策略来提取和利用视觉信息，对于拥有固定图像编码器的模型仍有提升空间。

> Recent research suggests that the failures of Vision-Language Models (VLMs) at visual reasoning often stem from erroneous agreements -- when semantically distinct images are ambiguously encoded by the CLIP image encoder into embeddings with high cosine similarity. In this paper, we show that erroneous agreements are not always the main culprit, as Multimodal Large Language Models (MLLMs) can still extract distinct information from them. For instance, when distinguishing objects on the left vs right in the What'sUp benchmark, the CLIP image embeddings of the left/right pairs have an average cosine similarity $>0.99$, and CLIP performs at random chance; but LLaVA-1.5-7B, which uses the same CLIP image encoder, achieves nearly $100\%$ accuracy. We find that the extractable information in CLIP image embeddings is likely obscured by CLIP's inadequate vision-language alignment: Its matching score learned by the contrastive objective might not capture all diverse image-text correspondences. We also study the MMVP benchmark, on which prior work has shown that LLaVA-1.5 cannot distinguish image pairs with high cosine similarity. We observe a performance gain brought by attending more to visual input through an alternative decoding algorithm. Further, the accuracy significantly increases if the model can take both images as input to emphasize their nuanced differences. Both findings indicate that LLaVA-1.5 did not utilize extracted visual information sufficiently. In conclusion, our findings suggest that while improving image encoders could benefit VLMs, there is still room to enhance models with a fixed image encoder by applying better strategies for extracting and utilizing visual information.

[Arxiv](https://arxiv.org/abs/2411.05195)