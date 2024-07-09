# 探究表格型LLM在模型多样性下的预测一致性
发布时间：2024年07月04日

`图表问答`
> Quantifying Prediction Consistency Under Model Multiplicity in Tabular LLMs
>
> 在分类任务中，对大型语言模型进行有限表格数据的微调可能导致“微调多重性”，即不同训练过程下的模型对相同输入做出不同预测。这引发了关于表格 LLM 在高风险决策中的稳健性和可靠性的担忧。为此，我们正式化了这一挑战，并提出了一种新指标，通过分析模型在嵌入空间中的局部行为，无需重新训练模型即可量化预测的稳健性。我们利用伯恩斯坦不等式，证明了高稳健性预测将以高概率保持一致，并通过实证评估支持了这一理论。我们的工作强调了解决微调不稳定性的重要性，以确保 LLM 在高风险和安全关键应用中的可信部署。
>
> https://arxiv.org/abs/2407.04173

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.04173/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.04173/rolling_stats_plot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.04173/diabetes_512.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.04173/creditg_512.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.04173](https://arxiv.org/abs/2407.04173)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1