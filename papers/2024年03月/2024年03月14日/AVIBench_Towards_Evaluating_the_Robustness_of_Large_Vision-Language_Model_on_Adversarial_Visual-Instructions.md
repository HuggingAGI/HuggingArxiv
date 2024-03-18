# AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。

发布时间：2024年03月14日

`Agent` `人工智能` `安全防护`

> AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions

> LVLM在处理用户视觉指令上取得了重大突破，但这种结合图文的指令易遭受有意无意的攻击。尽管强化LVLM应对这类风险的鲁棒性至关重要，相关研究却相对匮乏。为此，我们推出了AVIBench框架，旨在深入探究LVLM在面临各类对抗性视觉指令（AVI）时的防御能力，涵盖了四大类基于图像、十大类基于文本以及九类含有性别、暴力、文化与种族等偏见的内容型AVI。我们构建了包含五个多模态能力领域（九大任务）和内容偏见在内的260K个AVI样本。随后，我们对14款开源LVLM展开了全面性能评估。AVIBench还便于从业者评估自家LVLM对于AVI的抗干扰性。通过广泛而详尽的实验证据，我们揭示了LVLM存在的安全隐患，并指出即使是高端闭源产品如GeminiProVision和GPT-4V也存在内在偏见问题，从而突显了强化LVLM鲁棒性、安全性及公平性的迫切需求。未来我们将公开发布此项目的源代码和基准测试数据。

> Large Vision-Language Models (LVLMs) have shown significant progress in well responding to visual-instructions from users. However, these instructions, encompassing images and text, are susceptible to both intentional and inadvertent attacks. Despite the critical importance of LVLMs' robustness against such threats, current research in this area remains limited. To bridge this gap, we introduce AVIBench, a framework designed to analyze the robustness of LVLMs when facing various adversarial visual-instructions (AVIs), including four types of image-based AVIs, ten types of text-based AVIs, and nine types of content bias AVIs (such as gender, violence, cultural, and racial biases, among others). We generate 260K AVIs encompassing five categories of multimodal capabilities (nine tasks) and content bias. We then conduct a comprehensive evaluation involving 14 open-source LVLMs to assess their performance. AVIBench also serves as a convenient tool for practitioners to evaluate the robustness of LVLMs against AVIs. Our findings and extensive experimental results shed light on the vulnerabilities of LVLMs, and highlight that inherent biases exist even in advanced closed-source LVLMs like GeminiProVision and GPT-4V. This underscores the importance of enhancing the robustness, security, and fairness of LVLMs. The source code and benchmark will be made publicly available.

![AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。](../../../paper_images/2403.09346/x2.png)

![AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。](../../../paper_images/2403.09346/x3.png)

![AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。](../../../paper_images/2403.09346/x4.png)

![AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。](../../../paper_images/2403.09346/x5.png)

![AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。](../../../paper_images/2403.09346/x6.png)

![AVIBench 是一个专注于评估大型视觉-语言模型在面对对抗性视觉指令时的稳健性的研究项目，旨在揭示模型在此挑战性场景下的表现和适应能力。](../../../paper_images/2403.09346/x7.png)

[Arxiv](https://arxiv.org/abs/2403.09346)