# MobileFlow：专为移动界面代理设计的多模态大型语言模型

发布时间：2024年07月05日

`LLM应用` `移动应用` `人工智能`

> MobileFlow: A Multimodal LLM For Mobile GUI Agent

# 摘要

> 移动图形用户界面（GUIs）已深入人们的日常生活。随着GPT-4v、Qwen-VL-Max等多模态大型模型的进步，智能GUI助手的潜力日益凸显。然而，现有GUI代理通过系统API获取布局信息的方式存在隐私隐患，且低分辨率固定可能导致细节丢失。此外，这些模型对中文GUI的理解和决策能力不足，难以广泛应用。为此，我们推出了MobileFlow，一款专为移动GUI代理设计的多模态大型语言模型。基于Qwen-VL-Chat，MobileFlow拥有约210亿参数，并引入混合视觉编码器，支持多语言和可变分辨率图像输入。通过专家混合（MoE）扩展及创新训练策略，MobileFlow能精准解读图像并理解用户指令，优化GUI交互。在评估中，MobileFlow超越了Qwen-VL-Max和GPT-4v，并已在实际商业场景中成功应用，展现了其强大的实用价值。

> Currently, the integration of mobile Graphical User Interfaces (GUIs) is ubiquitous in most people's daily lives. And the ongoing evolution of multimodal large-scale models, such as GPT-4v, Qwen-VL-Max, has significantly bolstered the capabilities of GUI comprehension and user action analysis, showcasing the potentiality of intelligent GUI assistants. However, current GUI Agents often need to access page layout information through calling system APIs, which may pose privacy risks. Fixing GUI (such as mobile interfaces) to a certain low resolution might result in the loss of fine-grained image details. At the same time, the multimodal large models built for GUI Agents currently have poor understanding and decision-making abilities for Chinese GUI interfaces, making them difficult to apply to a large number of Chinese apps. This paper introduces MobileFlow, a multimodal large language model meticulously crafted for mobile GUI agents. Transforming from the open-source model Qwen-VL-Chat into GUI domain, MobileFlow contains approximately 21 billion parameters and is equipped with novel hybrid visual encoders, making it possible for variable resolutions of image inputs and good support for multilingual GUI. By incorporating Mixture of Experts (MoE) expansions and pioneering alignment training strategies, MobileFlow has the capacity to fully interpret image data and comprehend user instructions for GUI interaction tasks. Finally, MobileFlow outperforms Qwen-VL-Max and GPT-4v in terms of task execution by GUI agents on both public and our proposed evaluation metrics, and has been successfully deployed in real-world business contexts, proving its effectiveness for practical applications.

[Arxiv](https://arxiv.org/abs/2407.04346)