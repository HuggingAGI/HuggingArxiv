# 借助 RAG 增强的 LLM，实现从特征重要性到自然语言解释的转变
发布时间：2024年07月30日

`RAG`
> From Feature Importance to Natural Language Explanations Using LLMs with RAG
>
> 随着机器学习在人类交互的自主决策中扮演越来越重要的角色，通过对话理解模型输出的需求日益增长。最新研究探索了基础模型作为事后解释者的潜力，为揭示预测模型的决策机制开辟了新途径。本研究引入了一种可追踪的问答机制，借助外部知识库为大型语言模型（LLM）在场景理解任务中的用户查询提供精准响应。知识库详细记录了模型输出的上下文信息，包括高级特征、特征重要性及替代概率。通过减法反事实推理，我们计算特征重要性，分析语义特征分解导致的输出变化。为确保对话连贯，我们将社会科学中的四大解释特征——社会性、因果性、选择性和对比性——融入单次提示，引导响应生成。评估结果显示，LLM生成的解释成功融合了这些要素，有效弥合了模型复杂输出与自然语言表达之间的鸿沟。
>
> https://arxiv.org/abs/2407.20990

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20990/Tracable_RAG.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20990/merge.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.20990](https://arxiv.org/abs/2407.20990)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)