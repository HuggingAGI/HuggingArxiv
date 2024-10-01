# RAGProbe：自动化评估 RAG 应用的新方法

发布时间：2024年09月24日

`RAG` `软件开发` `人工智能`

> RAGProbe: An Automated Approach for Evaluating RAG Applications

# 摘要

> 在构建生成式 AI 应用时，Retrieval Augmented Generation (RAG) 的应用日益广泛。然而，评估这些应用和 RAG 管道主要依赖于手动试错。自动化评估面临诸多挑战，如上下文误解、格式错误等。以往研究多聚焦于改进评估指标和利用现有问答数据集优化管道组件，但未涉及问答对架构的提供或自动化评估模板的创建。本文提出一种生成问答对变体以触发 RAG 管道故障的技术，并通过三个数据集验证了五个开源 RAG 管道。结果显示，提示包含多个问题时失败率最高，分别为跨文档的 91% 和单文档的 78%，凸显了处理组合问题的重要性。学术领域数据集失败率为 60%，开放领域数据集分别为 53% 和 62%。我们的自动化方法平均每个数据集失败率提升 51%，超越现有最先进方法。此外，我们提出了一种持续监控 RAG 管道健康状况的自动化方法，可集成至现有 CI/CD 管道，提升质量。

> Retrieval Augmented Generation (RAG) is increasingly being used when building Generative AI applications. Evaluating these applications and RAG pipelines is mostly done manually, via a trial and error process. Automating evaluation of RAG pipelines requires overcoming challenges such as context misunderstanding, wrong format, incorrect specificity, and missing content. Prior works therefore focused on improving evaluation metrics as well as enhancing components within the pipeline using available question and answer datasets. However, they have not focused on 1) providing a schema for capturing different types of question-answer pairs or 2) creating a set of templates for generating question-answer pairs that can support automation of RAG pipeline evaluation. In this paper, we present a technique for generating variations in question-answer pairs to trigger failures in RAG pipelines. We validate 5 open-source RAG pipelines using 3 datasets. Our approach revealed the highest failure rates when prompts combine multiple questions: 91% for questions when spanning multiple documents and 78% for questions from a single document; indicating a need for developers to prioritise handling these combined questions. 60% failure rate was observed in academic domain dataset and 53% and 62% failure rates were observed in open-domain datasets. Our automated approach outperforms the existing state-of-the-art methods, by increasing the failure rate by 51% on average per dataset. Our work presents an automated approach for continuously monitoring the health of RAG pipelines, which can be integrated into existing CI/CD pipelines, allowing for improved quality.

[Arxiv](https://arxiv.org/abs/2409.19019)