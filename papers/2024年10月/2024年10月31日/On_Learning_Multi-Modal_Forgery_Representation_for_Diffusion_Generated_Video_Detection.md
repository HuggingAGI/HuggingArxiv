# 关于扩散生成视频检测的多模态伪造表示学习

发布时间：2024年10月31日

`LLM应用` `信息安全`

> On Learning Multi-Modal Forgery Representation for Diffusion Generated Video Detection

# 摘要

> 大量由扩散模型生成的合成视频给信息安全和真实性带来威胁，致使对生成内容检测的需求日益增长。然而，现有的视频级检测算法主要着眼于检测面部造假，常常难以识别各种语义的扩散生成内容。为推动视频取证领域的进步，我们提出了一种创新算法——多模态检测（MM-Det），用于检测扩散生成的视频。MM-Det 借助大型多模态模型（LMMs）的深度感知和综合能力，从 LMM 的多模态空间生成多模态伪造表示（MMFR），提升检测未曾见过的伪造内容的能力。另外，MM-Det 运用帧内和帧间注意力（IAFA）机制在时空域进行特征增强。动态融合策略有助于优化伪造表示以实现融合。而且，我们构建了一个涵盖广泛伪造视频的综合性扩散视频数据集，名为扩散视频取证（DVF）。MM-Det 在 DVF 中展现出了最先进的性能，证明了我们算法的有效性。源代码和 DVF 均可在 https://github.com/SparkleXFantasy/MM-Det 获取。

> Large numbers of synthesized videos from diffusion models pose threats to information security and authenticity, leading to an increasing demand for generated content detection. However, existing video-level detection algorithms primarily focus on detecting facial forgeries and often fail to identify diffusion-generated content with a diverse range of semantics. To advance the field of video forensics, we propose an innovative algorithm named Multi-Modal Detection(MM-Det) for detecting diffusion-generated videos. MM-Det utilizes the profound perceptual and comprehensive abilities of Large Multi-modal Models (LMMs) by generating a Multi-Modal Forgery Representation (MMFR) from LMM's multi-modal space, enhancing its ability to detect unseen forgery content. Besides, MM-Det leverages an In-and-Across Frame Attention (IAFA) mechanism for feature augmentation in the spatio-temporal domain. A dynamic fusion strategy helps refine forgery representations for the fusion. Moreover, we construct a comprehensive diffusion video dataset, called Diffusion Video Forensics (DVF), across a wide range of forgery videos. MM-Det achieves state-of-the-art performance in DVF, demonstrating the effectiveness of our algorithm. Both source code and DVF are available at https://github.com/SparkleXFantasy/MM-Det.

[Arxiv](https://arxiv.org/abs/2410.23623)