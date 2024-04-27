# 本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。

发布时间：2024年04月16日

`Agent` `自动驾驶` `人工智能`

> Automated Evaluation of Large Vision-Language Models on Self-driving Corner Cases

# 摘要

> 大型视觉-语言模型（LVLMs）因其卓越的图像和视频理解能力，在自动驾驶领域引起了广泛关注，显著推动了可解释的端到端自动驾驶技术的进步。但目前对LVLMs的评估多聚焦于常规情境下的多维能力，缺少对自动驾驶场景的量化和自动化评估，尤其是对于那些即使是最尖端的自动驾驶感知系统也难以应对的极端路况。本文提出了CODA-LM，这是一个创新的自动驾驶视觉-语言基准测试，首次为LVLMs在可解释自动驾驶中的应用提供了自动化和量化的评估，涵盖常规感知、区域感知和驾驶建议等方面。CODA-LM通过文本描述道路图像，借助仅使用文本的大型语言模型（LLMs）来评估LVLMs在自动驾驶情境下的表现，这种方式更能反映人类的偏好。实验结果揭示，即便是市面上的闭源商业LVLMs，如GPT-4V，也难以妥善处理极端路况，这表明我们距离拥有一个强大的LVLM驱动的智能驾驶代理还有很长的路要走。我们期望CODA-LM能够成为推动未来技术发展的催化剂。

> Large Vision-Language Models (LVLMs), due to the remarkable visual reasoning ability to understand images and videos, have received widespread attention in the autonomous driving domain, which significantly advances the development of interpretable end-to-end autonomous driving. However, current evaluations of LVLMs primarily focus on the multi-faceted capabilities in common scenarios, lacking quantifiable and automated assessment in autonomous driving contexts, let alone severe road corner cases that even the state-of-the-art autonomous driving perception systems struggle to handle. In this paper, we propose CODA-LM, a novel vision-language benchmark for self-driving, which provides the first automatic and quantitative evaluation of LVLMs for interpretable autonomous driving including general perception, regional perception, and driving suggestions. CODA-LM utilizes the texts to describe the road images, exploiting powerful text-only large language models (LLMs) without image inputs to assess the capabilities of LVLMs in autonomous driving scenarios, which reveals stronger alignment with human preferences than LVLM judges. Experiments demonstrate that even the closed-sourced commercial LVLMs like GPT-4V cannot deal with road corner cases well, suggesting that we are still far from a strong LVLM-powered intelligent driving agent, and we hope our CODA-LM can become the catalyst to promote future development.

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x1.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x2.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x3.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x4.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x5.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x6.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x7.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x8.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x9.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x10.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x11.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x12.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x13.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x14.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x15.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x16.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x17.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x18.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x19.png)

![本文探讨了如何对大型视觉-语言模型在自动驾驶领域的特殊情况下进行自动化评估。](../../../paper_images/2404.10595/x20.png)

[Arxiv](https://arxiv.org/abs/2404.10595)