# 利用滑动生成与自一致性技术，提升大型语言模型在摘要任务中的忠实表现。
发布时间：2024年07月31日

`提示工程`
> Improving Faithfulness of Large Language Models in Summarization via Sliding Generation and Self-Consistency
>
> 尽管 LLMs 在多项任务中表现出色，但仍面临事实不一致的“幻觉”问题。例如，在长文档摘要中，LLMs 有时会偏离原文，更偏爱提取首尾信息。为此，我们提出 SliSum 策略，通过滑动窗口和自一致性原则，促使 LLMs 更公正地处理全文，生成局部摘要后，利用聚类和多数投票算法整合，产出更忠实的全文摘要。实验证明，SliSum 有效提升 LLaMA-2、Claude-2 和 GPT-3.5 等模型在长短文本摘要中的忠实度，同时保持流畅与信息量，无需额外微调或资源。此外，我们还通过定性和定量研究，深入分析了 SliSum 的有效性及其超参数的影响。
>
> https://arxiv.org/abs/2407.21443

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21443/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21443/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21443/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21443/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.21443](https://arxiv.org/abs/2407.21443)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)