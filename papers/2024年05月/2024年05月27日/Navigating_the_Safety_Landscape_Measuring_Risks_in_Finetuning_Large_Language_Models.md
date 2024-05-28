# 探索安全领域：评估微调大型语言模型中的风险

发布时间：2024年05月27日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在微调过程中的安全性问题，并提出了一个新的安全指标——VISAGE，用于评估LLM微调的安全性。研究内容涉及模型参数空间中的“安全盆地”现象，以及微调对模型安全性的影响。这些研究内容更偏向于LLM的理论分析和模型安全性的深入探讨，因此归类为LLM理论。` `人工智能安全` `模型微调`

> Navigating the Safety Landscape: Measuring Risks in Finetuning Large Language Models

# 摘要

> 安全对齐是确保大型语言模型（LLMs）行为符合人类偏好并限制有害行为的关键，但近期研究发现，仅通过少数对抗性设计的训练样本进行微调，就可能轻易破坏这一安全机制。我们旨在通过探索LLM的安全景观来评估微调过程中的风险。我们发现了一个普遍存在于流行开源LLMs模型参数空间中的新现象——“安全盆地”：随机改变模型权重在局部范围内仍能维持原始模型的安全水平。这一发现促使我们提出了新的VISAGE安全指标，通过分析安全景观来评估LLM微调的安全性。通过可视化安全景观，我们得以洞察微调如何通过将模型拖离安全盆地而影响其安全性。此外，LLM的安全景观凸显了系统提示在保护模型中的关键作用，并且这种保护在安全盆地内的扰动模型中得以延续。这些发现为未来LLM安全领域的研究提供了新的视角。

> Safety alignment is the key to guiding the behaviors of large language models (LLMs) that are in line with human preferences and restrict harmful behaviors at inference time, but recent studies show that it can be easily compromised by finetuning with only a few adversarially designed training examples. We aim to measure the risks in finetuning LLMs through navigating the LLM safety landscape. We discover a new phenomenon observed universally in the model parameter space of popular open-source LLMs, termed as "safety basin": randomly perturbing model weights maintains the safety level of the original aligned model in its local neighborhood. Our discovery inspires us to propose the new VISAGE safety metric that measures the safety in LLM finetuning by probing its safety landscape. Visualizing the safety landscape of the aligned model enables us to understand how finetuning compromises safety by dragging the model away from the safety basin. LLM safety landscape also highlights the system prompt's critical role in protecting a model, and that such protection transfers to its perturbed variants within the safety basin. These observations from our safety landscape research provide new insights for future work on LLM safety community.

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x1.png)

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x2.png)

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x3.png)

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x4.png)

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x5.png)

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x6.png)

![探索安全领域：评估微调大型语言模型中的风险](../../../paper_images/2405.17374/x7.png)

[Arxiv](https://arxiv.org/abs/2405.17374)