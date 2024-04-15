# 为了加快变换模型的训练速度，我们提出了一个多层次的框架。
`动手训练`
> 像Bert、GPT和ViT这样的大规模深度学习模型正引领着自然语言处理和计算机视觉等领域的革命。但这些模型的训练对计算资源的巨大需求，也带来了能源消耗和碳排放的急剧上升。因此，寻求高效的训练方法以降低成本显得尤为迫切。我们从训练过程中发现的特征图和注意力的相似性出发，提出了一个多层次的训练加速框架。该框架采用合并、解合并和插值三种基本操作，通过V型循环训练过程，逐步调整模型大小，并通过这些操作在不同层级间传递参数。核心思想是，小模型快速训练得到的参数，能为更大网络的下一层提供高质量的中间解。插值操作则有助于打破解合并后的神经元对称性，优化收敛效果。实验表明，这一框架在保持性能的同时，能将BERT/GPT-Base模型的训练计算成本降低约20%，BERT-Large模型的训练成本更是大幅减少至51.6%。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x20.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x21.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.07999/x22.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/4844584584548858](https://wx.zsxq.com/dweb2/index/topic_detail/4844584584548858)

[https://arxiv.org/abs/2404.07999](https://arxiv.org/abs/2404.07999)