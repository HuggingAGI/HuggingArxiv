# 在大型语言模型驱动的推荐系统中，实现精确而高效的“忘却”机制显得尤为关键。
发布时间：2024年04月16日
`推荐系统`
> 大型语言模型驱动的推荐系统（LLMRec）通过参数高效微调（PEFT）技术，利用推荐数据定制化大型语言模型（LLMs）。然而，将用户数据融入LLMs可能引发隐私泄露的风险。为此，LLMRec中的“遗忘”过程显得尤为重要，即从成熟的推荐模型中移除无用数据（如历史行为记录）。现有遗忘技术难以满足LLM-Rec的特殊需求，主要受限于计算成本高昂和数据擦除不彻底。本研究提出了适配器分割与聚合（APA）框架，它能够在维持推荐效果的同时，精确且高效地实现数据的遗忘。APA框架通过为分割后的训练数据建立独立适配器，仅对受无用数据影响的适配器进行更新，从而实现遗忘。此外，为了保持推荐质量并降低推断成本，APA采用参数级别的适配器聚合和样本自适应注意力机制。大量实验验证了该框架的有效性和高效性。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10327/sample-franklin)

[https://wx.zsxq.com/dweb2/index/topic_detail/5122511258112144](https://wx.zsxq.com/dweb2/index/topic_detail/5122511258112144)

[https://arxiv.org/abs/2404.10327](https://arxiv.org/abs/2404.10327)