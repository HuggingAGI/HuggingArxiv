# 协作知识融合：通过大型语言模型实现多任务推荐系统的全新方法

发布时间：2024年10月27日

`LLM应用` `推荐系统` `语言模型`

> Collaborative Knowledge Fusion: A Novel Approach for Multi-task Recommender Systems via LLMs

# 摘要

> 由于大型语言模型（LLMs）展现出的出色通用智能，将其融入推荐系统的趋势愈发明显，旨在更深刻地洞悉人类的兴趣和意图。现有的基于 LLMs 的推荐系统主要借助文本形式的项目属性和用户交互历史，优化了像评分预测或可解释推荐之类的单一任务。然而，这些方式忽略了传统协作信号在判别用户深层意图时的关键作用，也无视了任务间的相互关联。为克服这些局限，我们推出了名为 CKF 的新框架，专为通过个性化协作知识融合进 LLMs 来推动多任务推荐而打造。具体来说，我们的方法联合传统协同过滤模型生成协作嵌入，接着运用元网络为每位用户构建个性化映射桥梁。完成映射后，将嵌入融入精心设计的提示模板，再输入到先进的 LLM 中以表征用户兴趣。为探究不同推荐任务间的内在联系，我们开发了 Multi-Lora，这是一种用于多任务优化的新型参数高效方法，能够清晰区分任务共享和任务特定的信息。该方法在 LLMs 与推荐场景之间搭建了桥梁，同时通过各项任务间的相互知识传递丰富了监督信号。在四个大型公共数据集上针对四个常见推荐任务展开的大量实验和深入的稳健性分析，证明了我们框架的有效性和优越性。

> Owing to the impressive general intelligence of large language models (LLMs), there has been a growing trend to integrate them into recommender systems to gain a more profound insight into human interests and intentions. Existing LLMs-based recommender systems primarily leverage item attributes and user interaction histories in textual format, improving the single task like rating prediction or explainable recommendation. Nevertheless, these approaches overlook the crucial contribution of traditional collaborative signals in discerning users' profound intentions and disregard the interrelatedness among tasks. To address these limitations, we introduce a novel framework known as CKF, specifically developed to boost multi-task recommendations via personalized collaborative knowledge fusion into LLMs. Specifically, our method synergizes traditional collaborative filtering models to produce collaborative embeddings, subsequently employing the meta-network to construct personalized mapping bridges tailored for each user. Upon mapped, the embeddings are incorporated into meticulously designed prompt templates and then fed into an advanced LLM to represent user interests. To investigate the intrinsic relationship among diverse recommendation tasks, we develop Multi-Lora, a new parameter-efficient approach for multi-task optimization, adept at distinctly segregating task-shared and task-specific information. This method forges a connection between LLMs and recommendation scenarios, while simultaneously enriching the supervisory signal through mutual knowledge transfer among various tasks. Extensive experiments and in-depth robustness analyses across four common recommendation tasks on four large public data sets substantiate the effectiveness and superiority of our framework.

[Arxiv](https://arxiv.org/abs/2410.20642)