# SPARK：为大规模视觉-语言模型打造的多视觉传感器感知与推理基准

发布时间：2024年08月21日

`LLM应用` `计算机视觉` `自动驾驶`

> SPARK: Multi-Vision Sensor Perception and Reasoning Benchmark for Large-scale Vision-Language Models

# 摘要

> 随着与文本对齐的视觉输入，大规模视觉-语言模型（LVLMs）在计算机视觉领域取得了显著进步。然而，当前的LVLMs未能充分考虑多视觉传感器的物理特性，导致在处理复杂传感器相关问题时存在局限。为此，我们提出了SPARK基准，旨在缩小图像与多视觉传感器间的信息鸿沟。通过自动生成6,248个测试样本，我们评估了十个领先模型，发现它们在多视觉感官推理方面普遍存在不足。详细代码和数据已公开在https://github.com/top-yun/SPARK。

> Large-scale Vision-Language Models (LVLMs) have significantly advanced with text-aligned vision inputs. They have made remarkable progress in computer vision tasks by aligning text modality with vision inputs. There are also endeavors to incorporate multi-vision sensors beyond RGB, including thermal, depth, and medical X-ray images. However, we observe that current LVLMs view images taken from multi-vision sensors as if they were in the same RGB domain without considering the physical characteristics of multi-vision sensors. They fail to convey the fundamental multi-vision sensor information from the dataset and the corresponding contextual knowledge properly. Consequently, alignment between the information from the actual physical environment and the text is not achieved correctly, making it difficult to answer complex sensor-related questions that consider the physical environment. In this paper, we aim to establish a multi-vision Sensor Perception And Reasoning benchmarK called SPARK that can reduce the fundamental multi-vision sensor information gap between images and multi-vision sensors. We generated 6,248 vision-language test samples automatically to investigate multi-vision sensory perception and multi-vision sensory reasoning on physical sensor knowledge proficiency across different formats, covering different types of sensor-related questions. We utilized these samples to assess ten leading LVLMs. The results showed that most models displayed deficiencies in multi-vision sensory reasoning to varying extents. Codes and data are available at https://github.com/top-yun/SPARK

[Arxiv](https://arxiv.org/abs/2408.12114)