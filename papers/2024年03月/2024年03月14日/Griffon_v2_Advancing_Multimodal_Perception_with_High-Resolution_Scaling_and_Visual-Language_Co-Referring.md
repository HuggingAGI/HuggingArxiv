# [Griffon v2 引领创新，借助高分辨率缩放技术和视觉-语言协同参照机制，大幅提升多模态感知性能。](https://arxiv.org/abs/2403.09333)

发布时间：2024年03月14日

`Agent`

`GUI界面理解`

`计数任务`

> Griffon v2: Advancing Multimodal Perception with High-Resolution Scaling and Visual-Language Co-Referring

> 尽管大型视觉语言模型已在细微物体感知领域崭露头角，但在复杂密集场景下，受限于图像分辨率，其性能仍难以超越针对特定任务优化的专家模型。这一局限性阻碍了模型在GUI界面理解、计数等领域的深入应用。因此，我们推出了新一代高分辨率通用模型 Griffon v2，借助视觉和文本提示实现对各类对象的灵活指代。为解决分辨率问题，我们创新设计了一款简洁高效的下采样投影器，突破了大型语言模型输入令牌数目的瓶颈，同时保持了图像的完整环境信息和微小细节，极大地增强了模型对多种模态的感知能力，特别是在识别小型物体方面。在此基础之上，我们通过一个即插即用的视觉分词模块赋能Griffon v2具备视觉与语言协同指代功能，让用户能够轻松地使用各种目标图像、自由格式文本甚至是坐标进行互动。实验证明，Griffon v2无论是在视觉或文本指引下都能精准定位任何关注对象，在REC、短语定位以及REG等任务上均取得业界领先的成绩，甚至在目标检测和计数任务上超越了专业模型。相关数据、代码及模型已开放至GitHub仓库：<https://github.com/jefferyZhan/Griffon>。

> Large Vision Language Models have achieved fine-grained object perception, but the limitation of image resolution remains a significant obstacle to surpass the performance of task-specific experts in complex and dense scenarios. Such limitation further restricts the model's potential to achieve nuanced visual and language referring in domains such as GUI Agents, Counting and \etc. To address this issue, we introduce a unified high-resolution generalist model, Griffon v2, enabling flexible object referring with visual and textual prompts. To efficiently scaling up image resolution, we design a simple and lightweight down-sampling projector to overcome the input tokens constraint in Large Language Models. This design inherently preserves the complete contexts and fine details, and significantly improves multimodal perception ability especially for small objects. Building upon this, we further equip the model with visual-language co-referring capabilities through a plug-and-play visual tokenizer. It enables user-friendly interaction with flexible target images, free-form texts and even coordinates. Experiments demonstrate that Griffon v2 can localize any objects of interest with visual and textual referring, achieve state-of-the-art performance on REC, phrase grounding, and REG tasks, and outperform expert models in object detection and object counting. Data, codes and models will be released at https://github.com/jefferyZhan/Griffon.

![Griffon v2 引领创新，借助高分辨率缩放技术和视觉-语言协同参照机制，大幅提升多模态感知性能。](../../../paper_images/2403.09333/x1.png)

![Griffon v2 引领创新，借助高分辨率缩放技术和视觉-语言协同参照机制，大幅提升多模态感知性能。](../../../paper_images/2403.09333/x2.png)

![Griffon v2 引领创新，借助高分辨率缩放技术和视觉-语言协同参照机制，大幅提升多模态感知性能。](../../../paper_images/2403.09333/resolution.png)

![Griffon v2 引领创新，借助高分辨率缩放技术和视觉-语言协同参照机制，大幅提升多模态感知性能。](../../../paper_images/2403.09333/x3.png)

![Griffon v2 引领创新，借助高分辨率缩放技术和视觉-语言协同参照机制，大幅提升多模态感知性能。](../../../paper_images/2403.09333/x4.png)