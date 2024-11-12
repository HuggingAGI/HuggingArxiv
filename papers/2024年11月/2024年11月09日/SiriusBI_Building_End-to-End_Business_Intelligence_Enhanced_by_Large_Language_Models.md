# SiriusBI：由大型语言模型增强的端到端商业智能的构建

发布时间：2024年11月09日

`LLM应用` `商业智能`

> SiriusBI: Building End-to-End Business Intelligence Enhanced by Large Language Models

# 摘要

> 人工智能技术的迅速发展，特别是大型语言模型（LLMs），正在为商业智能（BI）建立一个新的范例。尽管在利用 LLMs 增强 BI 系统方面出现了开创性的工作，但我们在实际工业场景部署时发现了以下三个问题：交互限制、性能瓶颈和功能缺陷。

在本文中，我们介绍了 SiriusBI，这是一个旨在同时解决这三个问题的端到端商业智能系统。首先，我们提出了一个名为具有查询功能的多轮对话的智能且面向应用的模块，旨在克服当前 BI 解决方案中普遍存在的交互限制。接下来，为了缓解场景迁移导致的性能瓶颈，我们引入了两种在准确性和部署成本之间取得平衡的 SQL 生成方法。最后，为了解决功能缺陷带来的实际挑战，我们开发了一个涵盖整个 BI 流程的端到端工作流，确保 SiriusBI 提供一套强大且完整的功能。

作为腾讯数据平台中的一个独立云服务，SiriusBI 已在腾讯的金融、广告和云部门得到应用，为数十家企业客户提供服务。在真实世界数据集上的实验和在工业 BI 场景中的实际应用证明了 SiriusBI 的实用性和有效性。值得注意的是，SiriusBI 在腾讯金融的 SQL 生成中实现了 97%的显著准确率，在腾讯广告中为 89%，在腾讯云中为 91%。

> The rapid advancement of AI technologies, particularly Large Language Models (LLMs), is establishing a new paradigm for Business Intelligence (BI). Despite the emergence of pioneering work in enhancing BI systems with LLMs, we have identified the following three issues when deployed in real industrial scenarios: interaction limitations, performance bottlenecks, and functionality deficiencies.
  In this paper, we present SiriusBI, an end-to-end business intelligence system that is designed to address the three issues simultaneously. First, we propose an intelligent and application-oriented module called multi-round dialogue with querying, which aims to overcome the prevalent interaction limitations in current BI solutions. Next, to mitigate the performance bottlenecks caused by scenario migration, we introduce two SQL generation methods that strike a balance between accuracy and deployment costs. Finally, to tackle the practical challenges posed by functionality deficiencies, we develop an end-to-end workflow that covers the entire BI process, ensuring that SiriusBI delivers a robust and complete set of functionalities.
  As an independent cloud service in Tencent's data platform, SiriusBI has been applied across Tencent's finance, advertising, and cloud sectors, providing services to dozens of enterprise clients. Experiments on real-world datasets and practical applications in industrial BI scenarios demonstrate the practicality and effectiveness of SiriusBI. Remarkably, SiriusBI achieves remarkable accuracy rates of 97% in SQL generation for Tencent Finance, 89% for Tencent Advertisement, and 91% for Tencent Cloud.

[Arxiv](https://arxiv.org/abs/2411.06102)