# CPR：结合检索技术的生成模型，助力版权保护
`RAG`
> 检索增强生成（RAG）技术正崭露头角，它能够在无需训练的情况下，让模型适配私人用户数据，处理版权问题，并实现大规模的高效机器遗忘。然而，在图像生成方面，RAG可能导致模型输出中复制了检索样本的部分内容。为了降低私有信息泄露的风险，我们提出了一种新型方法——复制保护生成（CPR），它为扩散模型在混合私有环境中提供了严格的版权保护。CPR能够在一组检索图像的基础上生成输出，同时确保不会泄露这些示例的独特可识别信息。它通过在推理阶段合并公共和私有分布的扩散分数，从两者的混合分布中进行采样。我们证实，CPR符合近无访问性（NAF）原则，有效限制了潜在攻击者从生成图像中提取信息的能力。我们提供了两种版权保护算法：CPR-KL和CPR-Choose。与以往的基于拒绝采样的NAF方法不同，我们的方法通过单次反向扩散过程，高效实现了版权保护采样。我们的方法适用于任何预训练的条件扩散模型，例如Stable Diffusion或unCLIP。实际上，我们在unCLIP上应用CPR后，不仅提升了生成图像的质量和文本对图像的准确对齐（TIFA基准测试得分从81.4提升至83.17），还实现了版权归属、保护以及确定性、快速的遗忘功能。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/log_prob_ratio_new.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/Rebuttal_figure.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18920/x6.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/4844811841454218](https://wx.zsxq.com/dweb2/index/topic_detail/4844811841454218)

[https://arxiv.org/abs/2403.18920](https://arxiv.org/abs/2403.18920)