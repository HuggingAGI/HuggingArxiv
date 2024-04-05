# 为零-shot多标签分类打造多样化且针对性的图像生成方法。
`文本分类`
> 近期，零样本多标签分类因其在无需人工注释的情况下预测未知标签的能力而备受瞩目。但现有方法常将已知类别作为未知类别的代理，效果并不理想。我们从文本到图像生成模型创造逼真图像的成功中汲取灵感，提出了一个创新方案：创造合成数据，专为未见标签的无代理训练量身定制训练集。我们的方法推出了一个新颖的图像生成框架，为未见类别生成多标签合成图像，用于训练分类器。通过使用预训练的大型语言模型生成多样化的提示，我们增加了生成图像的多样性。利用预训练的多模态CLIP模型作为鉴别器，我们确保生成图像能准确反映目标类别，并通过自动过滤掉不准确的图像，确保分类器的准确度。为了更精确、高效地生成多标签目标，我们引入了基于CLIP分数的判别性损失，用以微调扩散模型中的文本编码器。同时，为了在目标任务中增强视觉特征，同时保持原始特征的泛化性并避免因微调整个视觉编码器而引发的灾难性遗忘，我们提出了一个受变换器注意力机制启发的特征融合模块，以更有效地捕捉多个对象间的全局依赖。大量实验结果证明，我们的方法有效性显著，相较于现有顶尖方法有重大提升。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03144/x8.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/8855811522841882](https://wx.zsxq.com/dweb2/index/topic_detail/8855811522841882)
