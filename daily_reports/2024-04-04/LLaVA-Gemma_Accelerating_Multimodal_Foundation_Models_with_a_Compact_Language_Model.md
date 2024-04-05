# LLaVA-Gemma：借助轻量级语言模型，快速推进多模态基础模型发展
`多模态大模型`
> 通过LLaVA框架搭配新推出的Gemma系列大型语言模型，我们训练了一组多模态基础模型（MMFM）。引人注目的是2B参数的Gemma模型，它为打造高效的小型MMFMs创造了可能。参照同类研究，我们探究了三个设计要素的影响：预训练连接器、采用更强的图像处理网络以及扩充语言网络的规模。这些被称为LLaVA-Gemma的模型在多项评测中表现尚可，但并未超越现有的同等规模顶尖模型。进一步分析揭示了复杂的影响：省略预训练可能削弱性能，更大规模的视觉模型时而能提升性能，而语言模型规模的扩大则效果参差不齐。我们已将这些模型的训练方案、代码和权重公之于众，供大家使用。
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01331/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01331/x2.png)
