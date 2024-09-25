# 利用特定领域检索增强生成技术，提升大型语言模型在眼科长篇消费者健康问答中的表现。
发布时间：2024年09月20日

`RAG`
> Enhancing Large Language Models with Domain-specific Retrieval Augment Generation: A Case Study on Long-form Consumer Health Question Answering in Ophthalmology
>
> 尽管 LLM 在医学领域潜力巨大，但其生成的回答可能缺乏证据支持或基于虚幻信息。虽然 RAG 是解决此问题的热门方法，但在特定领域应用中的实施和评估却鲜有研究。我们构建了一个包含 70,000 份眼科文档的 RAG 系统，在推理时为 LLM 提供相关文档支持。在一项针对长篇健康问题的研究中，我们对比了 100 个问题在有无 RAG 情况下的回答，由 10 位医疗专家评估。评估涵盖证据的真实性、选择与排序、归属以及答案的准确性和完整性。未使用 RAG 的 LLM 提供了 252 个参考，其中 45.3% 为虚幻信息，34.1% 有小错误，20.6% 正确。而使用 RAG 的 LLM 准确率提升至 54.5%，错误率降至 18.8% 轻微幻觉和 26.7% 错误。RAG 检索的前 10 个文档中有 62.5% 被选为最佳参考，平均排名 4.9。RAG 还显著改善了证据归属（5 分制下从 1.85 提升至 2.49，P<0.001），尽管在准确性和完整性上略有下降。研究显示，LLM 在医学应用中常出现虚幻和错误证据，RAG 虽大幅减少此类问题，但仍需克服挑战。
>
> https://arxiv.org/abs/2409.13902

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.13902](https://arxiv.org/abs/2409.13902)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)