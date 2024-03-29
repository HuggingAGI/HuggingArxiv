# 探索视觉大型语言模型中的互动式区域理解

发布时间：2024年03月27日

`Agent` `分类：交互式对话系统` `区域理解`

> Toward Interactive Regional Understanding in Vision-Large Language Models

# 摘要

> 最新的 Vision-Language Pre-training (VLP) 模型取得了重大进展。但这些模型过分依赖图像-文本对，仅能获取图像的粗略和全局信息，限制了它们对图像区域的理解。本研究提出了 \textbf{RegionVLM}，它具备明确的区域识别能力，能够精准理解用户指定的图像区域。我们设计了一个简洁而创新的架构，无需改变原有的模型架构或目标函数。同时，我们利用了一个被以往 VLP 研究所忽视的新数据源——局部叙述。实验证明，我们的通用模型不仅构建了交互式对话系统，还在多个零样本区域理解任务上展现了卓越性能，且不影响其全局图像理解能力。

> Recent Vision-Language Pre-training (VLP) models have demonstrated significant advancements. Nevertheless, these models heavily rely on image-text pairs that capture only coarse and global information of an image, leading to a limitation in their regional understanding ability. In this work, we introduce \textbf{RegionVLM}, equipped with explicit regional modeling capabilities, allowing them to understand user-indicated image regions. To achieve this, we design a simple yet innovative architecture, requiring no modifications to the model architecture or objective function. Additionally, we leverage a dataset that contains a novel source of information, namely Localized Narratives, which has been overlooked in previous VLP research. Our experiments demonstrate that our single generalist model not only achieves an interactive dialogue system but also exhibits superior performance on various zero-shot region understanding tasks, without compromising its ability for global image understanding.

[Arxiv](https://arxiv.org/abs/2403.18260)