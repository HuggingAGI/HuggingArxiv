# [AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](https://arxiv.org/abs/2403.09346)

发布时间：2024年03月14日

`Agent`

`计算机视觉`

``

> AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions

> LVLM 在响应用户的视觉指令上展现出了重大突破，然而这类融合图像与文本的指令在面对有意或无心的攻击时较为脆弱。尽管强化 LVLM 抵御此类风险的鲁棒性极其关键，但相关研究却相对匮乏。为此，我们推出 AVIBench 框架，专用于分析 LVLM 在应对各类对抗性视觉指令（AVI）时的稳定性，其中包括四类图像型 AVI、十类文本型 AVI 以及九类含有性别、暴力、文化、种族等偏见的内容型 AVI。我们构建了包含五个跨模态能力类别（共九项任务）及内容偏见在内的260K条 AVI 数据。之后，我们对14款开源 LVLM 进行了详尽评估以考察其性能表现。AVIBench 同时作为一款实用工具，方便从业人员检测 LVLM 对 AVI 的防御力。通过深入研究与广泛实验数据，我们揭示了 LVLM 存在的薄弱环节，甚至发现在诸如 GeminiProVision 和 GPT-4V 等高级闭源 LVLM 中也潜藏固有偏见。这进一步强调了提升 LVLM 鲁棒性、安全性和公正性的重要意义。未来，我们将公开此项目的源代码及基准测试数据。

> Large Vision-Language Models (LVLMs) have shown significant progress in well responding to visual-instructions from users. However, these instructions, encompassing images and text, are susceptible to both intentional and inadvertent attacks. Despite the critical importance of LVLMs' robustness against such threats, current research in this area remains limited. To bridge this gap, we introduce AVIBench, a framework designed to analyze the robustness of LVLMs when facing various adversarial visual-instructions (AVIs), including four types of image-based AVIs, ten types of text-based AVIs, and nine types of content bias AVIs (such as gender, violence, cultural, and racial biases, among others). We generate 260K AVIs encompassing five categories of multimodal capabilities (nine tasks) and content bias. We then conduct a comprehensive evaluation involving 14 open-source LVLMs to assess their performance. AVIBench also serves as a convenient tool for practitioners to evaluate the robustness of LVLMs against AVIs. Our findings and extensive experimental results shed light on the vulnerabilities of LVLMs, and highlight that inherent biases exist even in advanced closed-source LVLMs like GeminiProVision and GPT-4V. This underscores the importance of enhancing the robustness, security, and fairness of LVLMs. The source code and benchmark will be made publicly available.

![AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](../../../paper_images/2403.09346/x2.png)

![AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](../../../paper_images/2403.09346/x3.png)

![AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](../../../paper_images/2403.09346/x4.png)

![AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](../../../paper_images/2403.09346/x5.png)

![AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](../../../paper_images/2403.09346/x6.png)

![AVIBench 是一个研究项目，专注于检验大型视觉-语言模型在面对对抗性视觉指令时的稳健性表现。](../../../paper_images/2403.09346/x7.png)