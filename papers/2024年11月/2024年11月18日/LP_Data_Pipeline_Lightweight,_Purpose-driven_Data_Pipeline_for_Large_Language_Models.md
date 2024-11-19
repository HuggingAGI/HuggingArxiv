# LP 数据管道：专为大型语言模型打造的轻量级、目标驱动型数据管道

发布时间：2024年11月18日

`LLM应用` `语言模型` `数据处理`

> LP Data Pipeline: Lightweight, Purpose-driven Data Pipeline for Large Language Models

# 摘要

> 创建大型语言模型（LLMs）所需的高质量、大规模数据集，往往要依靠资源密集型且由 GPU 加速的模型来进行质量筛选，致使整个过程既耗时又费钱。对 GPU 的这种依赖，限制了那些缺乏强大计算基础设施的组织的可及性。为应对此问题，我们推出了轻量级、目标驱动（LP）的数据管道，这是一个完全在 CPU 上运行的框架，用于优化数据集提取、筛选和整理的流程。基于我们的四项核心原则，LP 数据管道大幅缩减了准备时间和成本，同时保证了高数据质量。尤为重要的是，我们的管道能够创建针对特定领域和语言的目标驱动型数据集，提升了 LLMs 在专业场景中的适用性。我们期待我们的管道能够降低 LLM 开发的门槛，让各类组织更轻松地获取 LLMs。

> Creating high-quality, large-scale datasets for large language models (LLMs) often relies on resource-intensive, GPU-accelerated models for quality filtering, making the process time-consuming and costly. This dependence on GPUs limits accessibility for organizations lacking significant computational infrastructure. To address this issue, we introduce the Lightweight, Purpose-driven (LP) Data Pipeline, a framework that operates entirely on CPUs to streamline the processes of dataset extraction, filtering, and curation. Based on our four core principles, the LP Data Pipeline significantly reduces preparation time and cost while maintaining high data quality. Importantly, our pipeline enables the creation of purpose-driven datasets tailored to specific domains and languages, enhancing the applicability of LLMs in specialized contexts. We anticipate that our pipeline will lower the barriers to LLM development, enabling a wide range of organizations to access LLMs more easily.

[Arxiv](https://arxiv.org/abs/2411.11289)