![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 利用知识图谱提升检索生成技术，优化客户服务中的问答环节。
发布时间：2024年04月26日

`知识图谱`
> 在客户服务的技术支持环节，迅速准确地调取与过往问题相关的信息对于迅速解决客户咨询极为关键。传统上，大型语言模型（LLMs）中用于增强检索生成（RAG）的方法将历史问题跟踪票据视为普通文本，忽略了问题内部结构和问题间的联系，这大大限制了其效能。我们提出了一种创新的客户服务问答方法，该方法将RAG与知识图谱（KG）相结合。此方法利用历史数据构建KG，以保留问题内部结构和问题间的联系，用于信息检索。在问答环节，通过解析用户查询并从KG中调取相关子图来生成答案。这种KG的融合不仅通过保持客户服务的结构信息提升了检索的精确度，同时也通过减少文本分割的影响提升了回答的质量。基于我们的关键检索（MRR，Recall@K，NDCG@K）和文本生成（BLEU，ROUGE，METEOR）指标的基准数据集的实证评估显示，我们的方法在MRR上比基线提升了77.6%，在BLEU上提升了0.32。该方法已在LinkedIn客户服务团队中应用了大约六个月，成功将每个问题的平均解决时间缩短了28.6%。



- 论文原文: [https://arxiv.org/abs/2404.17723](https://arxiv.org/abs/2404.17723)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)