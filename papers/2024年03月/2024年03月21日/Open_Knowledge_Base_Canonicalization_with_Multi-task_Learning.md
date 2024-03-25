# 运用多任务学习方法进行开放知识库的标准化处理

发布时间：2024年03月21日

`Agent` `知识图谱` `数据规范化`

> Open Knowledge Base Canonicalization with Multi-task Learning

> 大规模开放知识库（OKB）的构建对于诸如网络搜索等众多基于知识的网络应用不可或缺，但其中名词短语与关系短语常因冗余和模糊性而困扰，亟需对OKB规范化进行探究。现有的方法通常借助先进的聚类算法及知识图谱嵌入技术（KGE）以推动规范化进程，然而这些方案并未充分发掘聚类与KGE学习间的相互增益，且针对各子任务设计的方法尚不完善。为此，我们提出了名为MulCanon的多任务学习框架，专门应对OKB规范化挑战。值得一提的是，MulCanon引入了扩散模型优化软聚类过程，利用临近信息提升名词短语的表达精度，从而达到更精准的表示效果。该框架整合了各项子任务的学习目标，采取两阶段的多任务学习策略进行训练。在一系列主流的OKB规范化基准上的全面实验证明，MulCanon能够取得卓越的规范化成果。

> The construction of large open knowledge bases (OKBs) is integral to many knowledge-driven applications on the world wide web such as web search. However, noun phrases and relational phrases in OKBs often suffer from redundancy and ambiguity, which calls for the investigation on OKB canonicalization. Current solutions address OKB canonicalization by devising advanced clustering algorithms and using knowledge graph embedding (KGE) to further facilitate the canonicalization process. Nevertheless, these works fail to fully exploit the synergy between clustering and KGE learning, and the methods designed for these subtasks are sub-optimal. To this end, we put forward a multi-task learning framework, namely MulCanon, to tackle OKB canonicalization. In addition, diffusion model is used in the soft clustering process to improve the noun phrase representations with neighboring information, which can lead to more accurate representations. MulCanon unifies the learning objectives of these sub-tasks, and adopts a two-stage multi-task learning paradigm for training. A thorough experimental study on popular OKB canonicalization benchmarks validates that MulCanon can achieve competitive canonicalization results.

[Arxiv](https://arxiv.org/abs/2403.14733)