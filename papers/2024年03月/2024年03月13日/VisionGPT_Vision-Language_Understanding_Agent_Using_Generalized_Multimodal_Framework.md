# VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。

发布时间：2024年03月13日

`LLM应用` `计算机视觉`

> VisionGPT: Vision-Language Understanding Agent Using Generalized Multimodal Framework

# 摘要

> 面对LLMs与视觉基础模型的崛起，如何结合二者的力量来破解开放世界的视觉感知难题尚待探索。在这篇论文中，我们引入VisionGPT，它巧妙地凝聚并自动化顶尖基础模型的融合过程，极大地推动了视觉与语言的理解以及视觉导向AI的发展。VisionGPT依托于一个通用化的多模态框架，凭借三大核心特性脱颖而出：(1) 以LLMs（例如LLaMA-2）为核心，将用户需求细化为具体动作建议，调用适宜的基础模型；(2) 自动整合多种来源的基础模型输出，为用户提供详尽周全的反馈；(3) 广泛适用于文本引导的图像理解/生成/编辑及视觉问答等多元场景。本论文勾勒出VisionGPT的架构和强大功能，展现其通过强化效能、普适性及泛化能力，有望颠覆计算机视觉领域的未来走向。我们的代码和模型将对公众开放。关键词：VisionGPT，开放世界视觉感知，视觉-语言理解，大型语言模型，基础模型。

> With the emergence of large language models (LLMs) and vision foundation models, how to combine the intelligence and capacity of these open-sourced or API-available models to achieve open-world visual perception remains an open question. In this paper, we introduce VisionGPT to consolidate and automate the integration of state-of-the-art foundation models, thereby facilitating vision-language understanding and the development of vision-oriented AI. VisionGPT builds upon a generalized multimodal framework that distinguishes itself through three key features: (1) utilizing LLMs (e.g., LLaMA-2) as the pivot to break down users' requests into detailed action proposals to call suitable foundation models; (2) integrating multi-source outputs from foundation models automatically and generating comprehensive responses for users; (3) adaptable to a wide range of applications such as text-conditioned image understanding/generation/editing and visual question answering. This paper outlines the architecture and capabilities of VisionGPT, demonstrating its potential to revolutionize the field of computer vision through enhanced efficiency, versatility, and generalization, and performance. Our code and models will be made publicly available. Keywords: VisionGPT, Open-world visual perception, Vision-language understanding, Large language model, and Foundation model

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/dinner_no_mask_no_seg.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/dinner_seg.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/dinner_mask_and_seg.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/visiongpt_overview.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/visiongpt_example.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/guitar_src.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/guitar_res.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/yellow_src.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/yellow_res.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/animal_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/animal_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/tower_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/tower_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/frogs_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/frogs_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/sheep_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/sheep_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/anomaly_src.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/anomaly_res.png)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/ano_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/ano_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_capacitor_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_capacitor_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_QRCode_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_QRCode_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_car_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_car_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_icyhw_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_icyhw_des.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_mountain_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_mountain_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_BigMountain_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_BigMountain_res.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_icyroad_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_icyroad_des.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_sky_src.jpg)

![VisionGPT 是一款基于通用多模态框架构建的视觉-语言理解利器，旨在高效融合视觉与语言信息，实现深度理解。](../../../paper_images/2403.09027/G_sky_res.jpg)

[Arxiv](https://arxiv.org/abs/2403.09027)