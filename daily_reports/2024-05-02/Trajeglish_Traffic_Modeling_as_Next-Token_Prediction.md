![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# Trajeglish：视交通建模为继绀令牌预测的艺术
发布时间：2024年04月14日

`应用案例`
> 自动驾驶技术发展中的一项长期挑战是如何基于记录的驾驶日志模拟动态驾驶情境。为此，我们采用了离散序列建模的工具来模拟车辆、行人和骑行者在驾驶情境中的相互作用。通过一个简洁的数据驱动标记化方法，我们将轨迹细化至厘米级精度，并利用有限的词汇库进行编码。接着，我们利用类似GPT的编码器-解码器架构，对离散运动标记的序列进行建模，该架构在时间上具有自回归特性，并能够捕捉智能体间的时间步内互动。我们模型生成的情境在真实感上达到了先进水平；在Waymo Sim Agents基准测试中，我们的模型超越了先前的研究，在真实感指标上提升了3.3%，在交互指标上提升了9.9%。我们还全面探讨了在完全自动驾驶和部分自动驾驶环境下的建模决策，并证明了我们模型学习到的表征能够迅速适应并提升在nuScenes上的表现。此外，我们还评估了模型在参数数量和数据集规模上的扩展性，并利用模型的密度估计来量化交通建模任务中上下文长度和时间步内交互的重要性。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/demoplot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/demoplot3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/manytrial.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/diagram.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/demoplot2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/demoplot4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/compare0004.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/compare0005.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/compare0007.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2312.04535/compare0016.png)


- 论文原文: [https://arxiv.org/abs/2312.04535](https://arxiv.org/abs/2312.04535)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)