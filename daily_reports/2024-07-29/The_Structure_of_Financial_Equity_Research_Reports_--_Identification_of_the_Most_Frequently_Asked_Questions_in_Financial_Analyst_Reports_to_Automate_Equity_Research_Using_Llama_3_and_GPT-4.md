# 金融股权研究报告的结构：通过识别分析师报告中常见问题，利用 Llama 3 和 GPT-4 实现股权研究自动化。
发布时间：2024年07月04日


> The Structure of Financial Equity Research Reports -- Identification of the Most Frequently Asked Questions in Financial Analyst Reports to Automate Equity Research Using Llama 3 and GPT-4
>
> 本研究深入分析了财务权益研究报告（ERRs），通过将其内容分类来揭示其结构。尽管ERRs中回答的问题缺乏实证分析，特别是关于信息频率、关键信息和需要人类判断的信息，我们的研究填补了这一空白。我们逐句分析了72份ERRs，识别出169个独特的问题原型，且这些问题均源自报告本身，确保了分析的无偏性。进一步地，我们评估了这些问题的自动化潜力，发现78.7%的问题可自动化，其中48.2%适合大型语言模型处理，30.5%可从数据库提取，仅21.3%需要人类判断。通过使用Llama-3-70B和GPT-4-turbo-2024-04-09模型，我们实证验证了约80%的ERRs陈述可自动化，且这些模型在功能上互补。研究结果表明，ERRs的撰写过程有望通过更多自动化提升质量和效率，同时也量化了引入大型语言模型的潜在效益。完整的问题原型及其频率列表将在同行评审后公开。
>
> https://arxiv.org/abs/2407.18327

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/statement_counts_histogram_binned.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/histogram_grouped_by_question_category_x_type_of_display_y_occurrences.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/venn_diagram_modalities_in_equity_research_reports.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/share_of_question_representations_in_equity_research_reports.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/evaluation_gpt4_llama3__pie_charts_correct_incorrect.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/evaluation_gpt4_llama3__bar_charts_correct_incorrect_counts_with_either_model_and_color.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/evaluation_gpt4_llama3__grid_chart_correctness_when_both_models_used_in_conjunction.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/question_categories_bars.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18327/page_counts_histogram.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.18327](https://arxiv.org/abs/2407.18327)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1