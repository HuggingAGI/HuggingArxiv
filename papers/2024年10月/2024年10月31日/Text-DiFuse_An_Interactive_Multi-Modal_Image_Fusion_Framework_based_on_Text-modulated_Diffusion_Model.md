# Text-DiFuse：一个基于文本调制扩散模型的交互式多模态图像融合框架

发布时间：2024年10月31日

`其他` `图像融合` `计算机视觉`

> Text-DiFuse: An Interactive Multi-Modal Image Fusion Framework based on Text-modulated Diffusion Model

# 摘要

> 现有的多模态图像融合方法难以应对源图像中的复合退化现象，致使融合图像被噪声、颜色偏差、曝光不当等问题所困扰。而且，这些方法常常忽视前景对象的独特性，降低了融合图像中感兴趣对象的显著度。为应对这些难题，本研究提出了一个基于文本调制扩散模型的新型交互式多模态图像融合框架，名为 Text-DiFuse。其一，该框架把特征级信息整合进扩散流程，实现自适应的退化消除和多模态信息融合。这是首次深度且明确地在扩散过程中嵌入信息融合，有效解决了图像融合中的复合退化问题。其二，通过将文本与零样本定位模型的结合嵌入扩散融合过程，研发出一种文本控制的融合再调制策略。这使得用户能够定制文本控制，提升融合性能，并突出融合图像中的前景对象。在众多公共数据集上开展的大量实验表明，我们的 Text-DiFuse 在各种存在复杂退化的场景中达到了最先进的融合性能。此外，语义分割实验验证了我们的文本控制融合再调制策略在语义性能方面的显著提升。代码在 https://github.com/Leiii-Cao/Text-DiFuse 上可公开获取。

> Existing multi-modal image fusion methods fail to address the compound degradations presented in source images, resulting in fusion images plagued by noise, color bias, improper exposure, \textit{etc}. Additionally, these methods often overlook the specificity of foreground objects, weakening the salience of the objects of interest within the fused images. To address these challenges, this study proposes a novel interactive multi-modal image fusion framework based on the text-modulated diffusion model, called Text-DiFuse. First, this framework integrates feature-level information integration into the diffusion process, allowing adaptive degradation removal and multi-modal information fusion. This is the first attempt to deeply and explicitly embed information fusion within the diffusion process, effectively addressing compound degradation in image fusion. Second, by embedding the combination of the text and zero-shot location model into the diffusion fusion process, a text-controlled fusion re-modulation strategy is developed. This enables user-customized text control to improve fusion performance and highlight foreground objects in the fused images. Extensive experiments on diverse public datasets show that our Text-DiFuse achieves state-of-the-art fusion performance across various scenarios with complex degradation. Moreover, the semantic segmentation experiment validates the significant enhancement in semantic performance achieved by our text-controlled fusion re-modulation strategy. The code is publicly available at https://github.com/Leiii-Cao/Text-DiFuse.

[Arxiv](https://arxiv.org/abs/2410.23905)