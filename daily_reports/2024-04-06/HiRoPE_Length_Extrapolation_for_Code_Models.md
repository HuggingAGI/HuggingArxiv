# HiRoPE：针对代码模型的长度扩展技术
`动手训练`
> 本研究致力于突破大型语言模型在代码相关任务中所面临的上下文长度局限。现有模型因预设的上下文长度而受限，难以驾驭冗长的复杂代码。借鉴程序员处理代码的策略，我们提出了分层旋转位置嵌入（HiRoPE）技术，该技术根据源代码的层级结构，将传统的位置嵌入升级为分层架构。HiRoPE能够无缝融入现有模型且无需额外训练。经过多种模型的广泛测试，该方法在语言建模和长代码补全等任务中展现出稳定的性能。此外，我们还推出了一项新的长代码理解任务，并结合真实世界代码项目，旨在推动代码领域的进一步研究。理论与实践证明，HiRoPE有效解决了位置编码的分布外问题，并显著提升了LLM的上下文处理能力，推理长度远超训练长度。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.19115/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.19115/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.19115/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.19115/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.19115/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.19115/x6.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/8855811854552882](https://wx.zsxq.com/dweb2/index/topic_detail/8855811854552882)

[https://arxiv.org/abs/2403.19115](https://arxiv.org/abs/2403.19115)