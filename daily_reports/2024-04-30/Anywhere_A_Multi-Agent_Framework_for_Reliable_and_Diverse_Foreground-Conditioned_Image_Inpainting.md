![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# Anywhere：一种多智能体框架，旨在实现可靠且多样化的前景条件图像修复
发布时间：2024年04月29日

`Agent应用`
> 图像修复技术的最新进展，尤其是扩散模型的应用，已经带来了令人鼓舞的成果。但在基于前景对象完成图像的场景下，现有端到端图像修复方法面临诸多挑战，如过度想象、前景背景不一致和多样性不足。为此，我们推出了Anywhere，这是一个创新的多代理框架，专门设计来应对这些挑战。Anywhere采用了一个包含视觉语言模型（VLM）、大型语言模型（LLM）和图像生成模型的复杂流水线框架。该框架包括三个核心组件：提示生成模块、图像生成模块和结果分析器。提示生成模块通过VLM进行语义分析，预测相关语言描述，并利用LLM推荐最佳语言提示。图像生成模块使用文本引导的canny到图像生成模型，基于前景图像的边缘图和语言提示创建模板图像，并通过图像细化器融合输入前景和模板图像生成最终结果。结果分析器利用VLM评估图像内容的合理性、审美评分和前景背景的相关性，并在必要时触发提示和图像的重新生成。大量实验证明，Anywhere框架在前景条件图像修复任务上表现卓越，有效减少了过度想象，解决了前景背景不一致的问题，并提升了结果的多样性。它成功地推动了前景条件图像修复技术的发展，产生了更可靠和多样化的图像修复结果。



- 论文原文 [https://arxiv.org/abs/2404.18598](https://arxiv.org/abs/2404.18598)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)