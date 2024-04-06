# LC-LLM：借助大型语言模型，实现车道变换意图与轨迹预测的可解释性分析
`应用案例`
> 自动驾驶车辆要在多变的路况中确保行车安全，必须能够准确预判周围车辆的变道动向并预测它们的行驶轨迹。目前的运动预测方法还有很大的提升空间，尤其是在提高长期预测的精确度和解释性方面。本研究提出了LC-LLM模型，这是一个基于大型语言模型（LLMs）的可解释变道预测模型，充分利用了LLMs出色的推理和自我解释能力。我们将变道预测问题转化为语言建模任务，将复杂的驾驶场景信息转换为自然语言提示，输入到LLM中，并采用监督微调技术，使LLM专门针对变道预测任务进行优化。这样，我们就能利用LLM的常识推理能力来理解复杂的交互信息，进而提升长期预测的准确度。此外，我们还为推理阶段的提示加入了解释性要求。因此，LC-LLM模型不仅能预测变道意图和轨迹，还能提供预测的解释，增强了模型的可解释性。通过在大规模高D数据集上的广泛实验，我们证明了LC-LLM在变道预测任务上的优越性能和解释性。这是首次尝试利用LLMs预测变道行为，我们的研究显示LLMs能够编码全面的交互信息，以深入理解驾驶行为。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18344/x9.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855811855825521](https://wx.zsxq.com/dweb2/index/topic_detail/2855811855825521)

[https://arxiv.org/abs/2403.18344](https://arxiv.org/abs/2403.18344)