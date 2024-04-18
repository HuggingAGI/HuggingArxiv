# MM-PhyQA：运用多张图片的 CoT 提示技术，实现多模态物理问答功能。
发布时间：2024年04月11日
`多模态大模型`
> 尽管大型语言模型（LLMs）在众多任务上展现出类人的表现，但在处理复杂的多步骤物理推理问题时仍显不足。为此，我们精心打造了一个新的数据集MM-PhyQA，收集了一系列高中难度的多模态物理问题。通过对比分析现有的LLMs在含多模态元素和不含多模态元素的问题上的表现，我们期望更深入地理解这些模型的潜力。对于包含图像和文本的多模态问题，我们运用了GPT-4的零次预测技术来生成答案，并对LLaVA（包括LLaVA和LLaVA-1.5）进行了微调，以适应我们的测试数据集。在纯文本输入的LLMs性能评估方面，我们对Mistral-7B和LLaMA2-7b模型的原始和微调版本进行了测试。此外，我们还展示了创新的多图像思维链（MI-CoT）提示技术，该技术在训练LLaVA-1.5 13b时表现出色，在我们的数据集测试中取得了最佳成绩，多数指标得分领先，测试集准确度高达71.65%。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/flow.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/example_qq.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/cosine_similarity_heatmap.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/micot_sample.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/Figure_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/Figure_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/conceptual.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/grounding.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.08704/computational.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/8855288511425222](https://wx.zsxq.com/dweb2/index/topic_detail/8855288511425222)

[https://arxiv.org/abs/2404.08704](https://arxiv.org/abs/2404.08704)