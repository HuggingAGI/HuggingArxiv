# 采用 In-Context Learning 方法，探索建模操作的合成跟踪生成技术。

发布时间：2024年08月26日

`LLM应用` `软件工程` `人工智能`

> Towards Synthetic Trace Generation of Modeling Operations using In-Context Learning Approach

# 摘要

> 在模型驱动软件工程中，精确的软件模型构建至关重要。然而，复杂系统的建模极易出错，需深厚的领域知识。过去十年，虽有自动化技术助力建模，但其依赖的大量训练数据常因隐私等问题而难以获取。大型语言模型的兴起虽能辅助合成数据生成，但尚不支持建模操作的直接生成。为此，我们构思了一个结合事件日志、智能助手和LLMs生成操作的框架。该框架不仅协助设计者细化系统、记录图形环境中的操作，还能智能推荐相关操作。同时，我们利用顶尖LLMs生成了全新的建模事件数据集。通过在欧洲项目中的工业案例实践，我们验证了该框架的可行性。评估显示，LLMs虽能生成建模事件，但与人类操作相比，准确性仍有提升空间。

> Producing accurate software models is crucial in model-driven software engineering (MDE). However, modeling complex systems is an error-prone task that requires deep application domain knowledge. In the past decade, several automated techniques have been proposed to support academic and industrial practitioners by providing relevant modeling operations. Nevertheless, those techniques require a huge amount of training data that cannot be available due to several factors, e.g., privacy issues. The advent of large language models (LLMs) can support the generation of synthetic data although state-of-the-art approaches are not yet supporting the generation of modeling operations. To fill the gap, we propose a conceptual framework that combines modeling event logs, intelligent modeling assistants, and the generation of modeling operations using LLMs. In particular, the architecture comprises modeling components that help the designer specify the system, record its operation within a graphical modeling environment, and automatically recommend relevant operations. In addition, we generate a completely new dataset of modeling events by telling on the most prominent LLMs currently available. As a proof of concept, we instantiate the proposed framework using a set of existing modeling tools employed in industrial use cases within different European projects. To assess the proposed methodology, we first evaluate the capability of the examined LLMs to generate realistic modeling operations by relying on well-founded distance metrics. Then, we evaluate the recommended operations by considering real-world industrial modeling artifacts. Our findings demonstrate that LLMs can generate modeling events even though the overall accuracy is higher when considering human-based operations.

[Arxiv](https://arxiv.org/abs/2408.14259)