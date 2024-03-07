# [LocalRQA：一站式方案，从构建数据集到本地完成增强检索型问答系统的训练、测试与部署。](https://arxiv.org/abs/2403.00982)

发布时间：2024年03月01日

`RAG`

> LocalRQA: From Generating Data to Locally Training, Testing, and Deploying Retrieval-Augmented QA Systems

> retrieval-augmented question-answering systems 融合了检索技术与大型语言模型，显著提升了回答的精确度与信息含量。现有不少工具包让用户能够便捷地运用现成模型搭建这类系统，然而在满足研究者和开发者对模型训练、测试、部署个性化需求方面仍有欠缺。为此，我们推出名为 LocalRQA 的开源工具包，汇集了一系列源于前沿研究成果的模型训练算法、评估手段以及部署工具。以实际案例为例，我们借助从 Databricks 和 Faire 官网抓取的在线文档构建了 QA 系统。实验结果显示，运用 LocalRQA 训练并部署的 7B 参数模型，其表现力堪比 OpenAI 的 text-ada-002 和 GPT-4-turbo 模型。

> Retrieval-augmented question-answering systems combine retrieval techniques with large language models to provide answers that are more accurate and informative. Many existing toolkits allow users to quickly build such systems using off-the-shelf models, but they fall short in supporting researchers and developers to customize the model training, testing, and deployment process. We propose LocalRQA, an open-source toolkit that features a wide selection of model training algorithms, evaluation methods, and deployment tools curated from the latest research. As a showcase, we build QA systems using online documentation obtained from Databricks and Faire's websites. We find 7B-models trained and deployed using LocalRQA reach a similar performance compared to using OpenAI's text-ada-002 and GPT-4-turbo.