# LongVILA：扩展长上下文视觉语言模型以适应长视频处理
发布时间：2024年08月19日

`多模态大模型`
> LongVILA: Scaling Long-Context Visual Language Models for Long Videos
>
> 长上下文能力是多模态基础模型的关键。我们推出的LongVILA，是一个全面的长上下文视觉语言模型解决方案，涵盖系统架构、模型训练和数据集构建。在系统层面，我们首创了多模态序列并行（MM-SP）技术，支持大规模长上下文训练与推理，实现256个GPU上2M上下文长度的训练。MM-SP技术高效，比传统环形序列并行快2.1至5.7倍，在纯文本环境下比Megatron-LM快1.1至1.4倍，并完美兼容Hugging Face Transformers。模型训练方面，我们设计了五阶段流程，包括对齐、预训练、上下文扩展及长短联合微调。数据集方面，我们精心打造了大规模视觉语言预训练数据集和长视频指令数据集，以支撑多阶段训练需求。LongVILA的全栈方案将视觉语言模型处理帧数提升128倍，从8帧增至1024帧，显著提升长视频描述得分至3.26，实现1400帧视频中高达99.5%的精准度。LongVILA-8B在VideoMME基准测试中，随着视频帧数增加，长视频处理性能稳步提升。
>
> https://arxiv.org/abs/2408.10188

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/TrainingPipeline2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/Longvideo-data.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.10188/x14.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.10188](https://arxiv.org/abs/2408.10188)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)