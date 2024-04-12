# RULER: 长语境语言模型的实际上下文容量究竟有多大？
`动手训练`
> 针堆测试，一种在冗长干扰文本中寻找特定信息的挑战，虽被广泛用于评估长篇语言模型，但这种测试只能反映对长篇内容的浅层理解。为此，我们推出了全新基准测试RULER，它具有可调整的设置，以适应不同序列长度和任务难度。RULER在经典针堆测试基础上进行了扩展，涵盖了更多种类和数量的“针”。此外，RULER新增了多跳追踪和聚合等任务类别，以评估超出简单搜索的复杂行为。我们利用RULER对十种长篇语言模型进行了13项任务的评估。结果发现，尽管这些模型在经典测试中准确度近乎完美，但在处理更长文本时，性能均有显著下降。尽管这些模型声称能处理32K个以上标记的上下文，实际上只有GPT-4、Command-R、Yi-34B和Mixtral四种模型能在32K长度上维持较佳性能。对能处理200K长度的Yi-34B进行深入分析后，我们发现随着输入长度和任务复杂度的提升，模型性能仍有大幅提升的空间。我们已将RULER开源，旨在推动对长篇语言模型的深度评估。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06654/x15.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855251521455851](https://wx.zsxq.com/dweb2/index/topic_detail/2855251521455851)

[https://arxiv.org/abs/2404.06654](https://arxiv.org/abs/2404.06654)