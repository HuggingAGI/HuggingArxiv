# CHOPS：借助客户档案系统，与大型语言模型 (LLM) 展开高效客户服务对话
`Agent应用`
> 越来越多的企业和软件平台开始依赖GPT-3.5、GPT-4、GLM-3和LLaMa-2等大型语言模型，以提供聊天支持、文件访问或客户服务的智能代理。然而，现有的LLM客户服务模式在与客户档案的整合和提供高效服务所需的操作能力方面仍有局限。同时，现行API集成过于强调多样性，忽略了在现实客户服务中至关重要的精确性和错误防范。为此，我们设计了一个名为CHOPS的LLM代理，它能够：（1）高效地利用现有数据库或系统获取用户信息，并遵循既定规范与这些系统互动；（2）在避免不当操作的前提下，提供精确且合理的回答或完成系统要求的操作；（3）结合小型和大型LLM，以合理的推理成本实现卓越性能。我们还推出了CPHOS数据集，内含数据库、指导文件和QA对，这些数据源自CPHOS平台，该平台旨在帮助高中师生组织模拟物理奥林匹克竞赛。通过CPHOS数据集的广泛实验，我们验证了CHOPS架构的效能，展示了LLM如何提升或替代人工客服。我们的代码和数据集即将开放源代码。
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01343/motivation2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01343/dataset1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01343/pipeline2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01343/classifier2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.01343/ablate.png)
