# 借助本体论，提升大型语言模型在问答任务中的精准度！
发布时间：2024年05月19日

`应用案例`
> Increasing the LLM Accuracy for Question Answering: Ontologies to the Rescue!
>
> 越来越多的证据显示，采用知识图谱（Text-to-SPARQL）的大型语言模型（LLMs）问答系统，其准确性超越了直接基于SQL数据库的系统（Text-to-SQL）。我们之前的研究已证实，知识图谱的使用将准确率从16%提升至54%。然而，如何进一步提升准确性并减少错误率仍是一个挑战。基于先前研究中发现的LLM生成的SPARQL查询路径错误问题，我们提出了一种新方法：1）基于本体的查询检查（OBQC），利用知识图谱的本体来验证查询的语义正确性；2）LLM修复，通过LLM解释错误并修正SPARQL查询。在与数据对话的基准测试中，我们发现这种方法将总体准确率提升至72%，并增加了8%的“未知”回答，总体错误率降至20%。这些发现再次印证了，投资于知识图谱，尤其是本体，能够显著提升LLM问答系统的准确性。
>
> https://arxiv.org/abs/2405.11706

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11706/Overview.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11706/OverallResultsWithPrevious.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11706/QuadrantResultsWithPrevious.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.11706](https://arxiv.org/abs/2405.11706)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 2855212855452281