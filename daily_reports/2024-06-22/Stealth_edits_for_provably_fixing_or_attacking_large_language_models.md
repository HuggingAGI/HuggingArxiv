# 巧妙编辑：验证大型语言模型的修复与攻击之道
发布时间：2024年06月18日

`模型安全`
> Stealth edits for provably fixing or attacking large language models
>
> 我们揭示了编辑大型语言模型的新技术和理论基础，并展示了如何利用这些理论来评估模型的可编辑性，以及它们对未知恶意攻击的脆弱性。我们的研究发现，一个特定的内在维度度量是预测流行编辑方法成功与否的关键，并架起了不同编辑技术之间的桥梁。这些方法被称为隐秘编辑，因为它们旨在不重新训练的情况下，直接且经济地更新模型权重，以纠正对特定幻觉提示的响应。基于这些理论洞察，我们开发了一种名为“喷气背包块”的新网络模块，它专为精细的模型编辑设计，可无缝集成到现有网络中。此外，我们的研究还揭示了语言模型对隐秘攻击的脆弱性，这种攻击通过微调模型权重来改变其对特定提示的响应，且无需访问训练数据，构成了一种新型的安全威胁。实验结果充分支持了我们的方法和理论。编辑语言模型的演示和源代码已发布于 https://github.com/qinghua-zhou/stealth-edits。
>
> https://arxiv.org/abs/2406.12670

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/t1_dims.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/in-place.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/jetpacks9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/prompt.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/wikipedia.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/context.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/params.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12670/zero_neuron.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.12670](https://arxiv.org/abs/2406.12670)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2