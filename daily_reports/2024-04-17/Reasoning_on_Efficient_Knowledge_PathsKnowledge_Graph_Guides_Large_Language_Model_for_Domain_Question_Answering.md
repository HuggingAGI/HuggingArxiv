# 高效知识路径推理：知识图谱助力大型语言模型解答领域问题
发布时间：2024年04月16日
`知识图谱`
> 像 GPT3.5、GPT4 和 LLAMA2 这样的大型语言模型在众多任务上展现出超越人类专家的能力。但在特定领域的测试中，它们往往因为缺乏充分的专业训练而产生幻觉现象。微调这些模型也面临挑战，例如模型不开源或难以构建高质量的指导信息。因此，知识图谱等结构化知识库能更有效地为 LLMs 提供领域知识支持，发挥其推理分析的潜力。在以往的研究中，通过问题检索子图时，会反复调用 LLM 来判断三元组是否适宜。对于需要复杂推理的问题，频繁的模型调用会导致巨大的计算消耗。而且，每选择一个推理步骤就会调用一次 LLM，一旦选错，便会累积错误。本文提出了一个优化的流程，通过基于 LLM 的知识图谱推理路径选择，降低了对 LLM 的依赖。同时，我们引入了一种结合思维链和页面排名的高效子图检索方法，能够锁定最可能的答案路径。我们在 GenMedGPT-5k、WebQuestions 和 CMCQA 三个数据集上进行了验证。RoK 实验结果表明，减少 LLM 调用次数仍可达到先进模型的性能水平。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10384/x7.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/8855288524225142](https://wx.zsxq.com/dweb2/index/topic_detail/8855288524225142)

[https://arxiv.org/abs/2404.10384](https://arxiv.org/abs/2404.10384)