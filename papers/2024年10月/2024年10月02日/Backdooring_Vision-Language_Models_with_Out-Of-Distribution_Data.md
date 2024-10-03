# 利用分布外数据对视觉-语言模型实施后门攻击

发布时间：2024年10月02日

`LLM应用` `计算机视觉` `网络安全`

> Backdooring Vision-Language Models with Out-Of-Distribution Data

# 摘要

> 视觉-语言模型 (VLM) 的崛起，标志着计算机视觉与大型语言模型 (LLM) 的深度融合，能够从视觉输入中生成详尽的文本描述。然而，随着其重要性的提升，VLM 的安全性，尤其是抵御后门攻击的能力，却鲜有研究。以往的研究往往假设攻击者能接触到原始训练数据，这在现实中极不现实。本文探讨了一个更为实际且更具挑战性的场景：攻击者仅能利用分布外 (OOD) 数据。我们提出了 VLOOD（利用分布外数据对视觉-语言模型进行后门攻击），该方法有两大创新：(1) 在复杂图像到文本任务中实施后门攻击，同时尽量减少受污染输入对原始语义的影响；(2) 开发无需访问原始训练数据的后门注入技术。通过对图像字幕和视觉问答 (VQA) 任务的评估，我们验证了 VLOOD 的有效性，揭示了 VLM 中的重大安全漏洞，并为未来研究如何保护多模态模型免受复杂威胁提供了基础。

> The emergence of Vision-Language Models (VLMs) represents a significant advancement in integrating computer vision with Large Language Models (LLMs) to generate detailed text descriptions from visual inputs. Despite their growing importance, the security of VLMs, particularly against backdoor attacks, is under explored. Moreover, prior works often assume attackers have access to the original training data, which is often unrealistic. In this paper, we address a more practical and challenging scenario where attackers must rely solely on Out-Of-Distribution (OOD) data. We introduce VLOOD (Backdooring Vision-Language Models with Out-of-Distribution Data), a novel approach with two key contributions: (1) demonstrating backdoor attacks on VLMs in complex image-to-text tasks while minimizing degradation of the original semantics under poisoned inputs, and (2) proposing innovative techniques for backdoor injection without requiring any access to the original training data. Our evaluation on image captioning and visual question answering (VQA) tasks confirms the effectiveness of VLOOD, revealing a critical security vulnerability in VLMs and laying the foundation for future research on securing multimodal models against sophisticated threats.

[Arxiv](https://arxiv.org/abs/2410.01264)