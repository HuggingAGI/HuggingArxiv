# SpreadsheetLLM：将电子表格编码以供大型语言模型使用
发布时间：2024年07月12日

`图表问答`
> SpreadsheetLLM: Encoding Spreadsheets for Large Language Models
>
> 电子表格因其复杂的两维网格、多变的布局和丰富的格式选项，对大型语言模型（LLMs）构成了挑战。为此，我们推出了SpreadsheetLLM，采用一种高效编码方法，旨在充分发挥LLMs在电子表格上的理解和推理能力。我们最初尝试了一种简单的序列化方法，结合单元格地址、值和格式，但受限于LLMs的标记限制，实用性有限。为解决这一问题，我们创新性地开发了SheetCompressor框架，通过三个模块——基于结构锚的压缩、逆索引转换和数据格式感知的聚合，有效压缩电子表格，显著提升了表格检测任务的性能，在GPT4的上下文学习设置中，性能比简单方法高出25.6%。此外，经过SheetCompressor微调的LLM，平均压缩比达25倍，F1分数高达78.9%，超越了现有最佳模型12.3%。最后，我们提出了电子表格链（Chain of Spreadsheet），用于电子表格理解和验证的新颖且具有挑战性的电子表格QA任务，系统地利用了电子表格的固有布局和结构，证明了SpreadsheetLLM在各种电子表格任务中的高效性。
>
> https://arxiv.org/abs/2407.09025

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/overview.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/GPT-4-1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/GPT-4-2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/traditional_enc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/heu.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/case1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/case2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/case3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09025/case_compare1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.09025](https://arxiv.org/abs/2407.09025)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1