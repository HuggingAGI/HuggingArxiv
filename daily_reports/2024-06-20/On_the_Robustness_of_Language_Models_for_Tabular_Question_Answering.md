# 语言模型在表格问答中的稳健性探讨
发布时间：2024年06月18日

`图表问答`
> On the Robustness of Language Models for Tabular Question Answering
>
> 大型语言模型（LLMs）不仅在文本理解任务中表现卓越，最近也展现出无需专门训练即可应对表格理解任务的能力。我们的研究深入探讨了“情境学习”、“模型规模”、“指令调优”及“领域偏见”对表格问答（TQA）的影响。通过在WTQ和TAT-QA数据集上测试LLMs的鲁棒性，我们发现指令调优显著提升了性能，尤其是新模型Llama3比旧版本更为稳健。尽管如此，数据污染和实际可靠性问题，尤其是在WTQ数据集上，仍需关注。我们呼吁采用更先进的方法，如结构感知自注意力机制，并优化处理特定领域表格数据的策略，以打造更可靠的LLMs，助力表格理解任务。
>
> https://arxiv.org/abs/2406.12719

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/avg_fewshot_operation.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/small_vs_large_fewshot_3_table_aug.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/original_vs_finedtuned_fewshot_3_table_aug.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/original_vs_finedtuned_fewshot_3_table_aug.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12719/avg_fewshot_model.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.12719](https://arxiv.org/abs/2406.12719)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2