# 当大型视觉语言模型与人员再识别相遇

发布时间：2024年11月27日

`LLM应用` `行人重识别` `计算机视觉`

> When Large Vision-Language Models Meet Person Re-Identification

# 摘要

> 大型视觉语言模型（LVLMs）融合了视觉模型与大型语言模型（LLMs），在各类跨模态理解和推理任务中成绩斐然。近些年来，行人重识别（ReID）也开始探索跨模态语义，以提升身份识别的精准度。然而，如何将 LVLMs 有效应用于 ReID 仍是一个难题。尽管 LVLMs 基于生成范式，通过预测下一个输出词来运作，但 ReID 需要提取具有判别力的身份特征，以匹配不同摄像机中的行人。在本文中，我们提出了 LVLM-ReID 这一全新框架，旨在借助 LVLMs 的优势推动 ReID 发展。具体而言，我们运用指令引导 LVLM 生成一个行人语义标记，该标记从人员图像中涵盖了关键的外观语义。此标记通过我们的语义引导交互（SGI）模块进一步优化，在语义标记和视觉标记之间构建了相互作用。最终，强化后的语义标记充当行人身份的表征。我们的框架将 LVLMs 的语义理解和生成能力融入端到端的 ReID 训练，让 LVLMs 在训练和推理过程中都能从行人图像中获取丰富的语义线索。我们的方法在多个基准测试中取得了出色的成绩，且无需额外的图像 - 文本注释，展现了 LVLM 生成的语义在促进行人 ReID 方面的潜力，为未来的研究指明了一个充满希望的方向。

> Large Vision-Language Models (LVLMs) that incorporate visual models and Large Language Models (LLMs) have achieved impressive results across various cross-modal understanding and reasoning tasks. In recent years, person re-identification (ReID) has also started to explore cross-modal semantics to improve the accuracy of identity recognition. However, effectively utilizing LVLMs for ReID remains an open challenge. While LVLMs operate under a generative paradigm by predicting the next output word, ReID requires the extraction of discriminative identity features to match pedestrians across cameras. In this paper, we propose LVLM-ReID, a novel framework that harnesses the strengths of LVLMs to promote ReID. Specifically, we employ instructions to guide the LVLM in generating one pedestrian semantic token that encapsulates key appearance semantics from the person image. This token is further refined through our Semantic-Guided Interaction (SGI) module, establishing a reciprocal interaction between the semantic token and visual tokens. Ultimately, the reinforced semantic token serves as the pedestrian identity representation. Our framework integrates the semantic understanding and generation capabilities of LVLMs into end-to-end ReID training, allowing LVLMs to capture rich semantic cues from pedestrian images during both training and inference. Our method achieves competitive results on multiple benchmarks without additional image-text annotations, demonstrating the potential of LVLM-generated semantics to advance person ReID and offering a promising direction for future research.

[Arxiv](https://arxiv.org/abs/2411.18111)