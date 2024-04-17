# 本文探讨了如何对大型视觉-语言模型在自动驾驶领域的边缘案例中进行自动化评估。

发布时间：2024年04月16日

`LLM应用` `自动驾驶` `视觉-语言模型`

> Automated Evaluation of Large Vision-Language Models on Self-driving Corner Cases

# 摘要

> 由于具备卓越的视觉推理能力，大型视觉-语言模型（LVLMs）在理解图像和视频方面表现突出，因此在自动驾驶领域引起了广泛关注，显著推动了可解释的端到端自动驾驶技术的进步。不过，目前对LVLMs的性能评估多聚焦于常规情境下的多功能性，缺少针对自动驾驶场景的量化和自动化评价体系，对于连最尖端自动驾驶感知系统也难以应对的复杂路况更是如此。本文提出了CODA-LM，这是一个创新的自动驾驶视觉-语言基准，首次为LVLMs在可解释自动驾驶方面提供了自动化和量化的评估方法，涵盖常规感知、局部感知和驾驶建议等多个维度。CODA-LM通过文本描述道路图像，借助无需图像输入的强大文本型大型语言模型（LLMs），来评估LVLMs在自动驾驶情境下的表现，这种方式更贴近人类的偏好。实验结果揭示，即便是市面上的闭源商业LVLMs，如GPT-4V，也难以妥善处理复杂的道路情况，这表明我们距离拥有一个强大的LVLM驱动的智能驾驶代理还有较长的路要走。我们期望CODA-LM能够激发并推动未来技术的发展。

> Large Vision-Language Models (LVLMs), due to the remarkable visual reasoning ability to understand images and videos, have received widespread attention in the autonomous driving domain, which significantly advances the development of interpretable end-to-end autonomous driving. However, current evaluations of LVLMs primarily focus on the multi-faceted capabilities in common scenarios, lacking quantifiable and automated assessment in autonomous driving contexts, let alone severe road corner cases that even the state-of-the-art autonomous driving perception systems struggle to handle. In this paper, we propose CODA-LM, a novel vision-language benchmark for self-driving, which provides the first automatic and quantitative evaluation of LVLMs for interpretable autonomous driving including general perception, regional perception, and driving suggestions. CODA-LM utilizes the texts to describe the road images, exploiting powerful text-only large language models (LLMs) without image inputs to assess the capabilities of LVLMs in autonomous driving scenarios, which reveals stronger alignment with human preferences than LVLM judges. Experiments demonstrate that even the closed-sourced commercial LVLMs like GPT-4V cannot deal with road corner cases well, suggesting that we are still far from a strong LVLM-powered intelligent driving agent, and we hope our CODA-LM can become the catalyst to promote future development.

[Arxiv](https://arxiv.org/abs/2404.10595)