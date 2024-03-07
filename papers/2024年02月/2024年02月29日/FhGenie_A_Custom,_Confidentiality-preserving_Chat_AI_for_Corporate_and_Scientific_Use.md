# [FhGenie，一款专门针对企业和科研场景定制的、具备隐私保护功能的聊天 AI 助手](https://arxiv.org/abs/2403.00039)

发布时间：2024年02月29日

`Agent`

> FhGenie: A Custom, Confidentiality-preserving Chat AI for Corporate and Scientific Use

> 自 ChatGPT 问世以来，生成式 AI 引发了各行业热烈关注。这类 AI 聊天工具有力提升了各行各业知识工作者的生产力，但公有免费服务因服务商可能利用用户输入无边界地优化训练而潜藏数据泄露风险，即便是付费订阅服务，在用户数据处理上有时也不够透明。为解决此类顾虑，并在确保 Fraunhofer 员工信息保密的前提下充分利用这一技术，我们精心设计并打造了名为 FhGenie（取“精灵助手”之意）的定制聊天 AI。FhGenie 推出短短数日，即吸引了数千名 Fraunhofer 员工试用。众多组织随后跟进，模仿我们的实践。我们依托于商业级大型语言模型 (LLMs)，审慎将其融入系统中，以适应特定需求及符合保密和 GDPR 等合规要求。本文深入剖析了 FhGenie 在架构决策、设计、实现及后续升级方面的具体细节，同时探讨了实际应用中遇到的挑战、观察发现及核心经验。

> Since OpenAI's release of ChatGPT, generative AI has received significant attention across various domains. These AI-based chat systems have the potential to enhance the productivity of knowledge workers in diverse tasks. However, the use of free public services poses a risk of data leakage, as service providers may exploit user input for additional training and optimization without clear boundaries. Even subscription-based alternatives sometimes lack transparency in handling user data. To address these concerns and enable Fraunhofer staff to leverage this technology while ensuring confidentiality, we have designed and developed a customized chat AI called FhGenie (genie being a reference to a helpful spirit). Within few days of its release, thousands of Fraunhofer employees started using this service. As pioneers in implementing such a system, many other organizations have followed suit. Our solution builds upon commercial large language models (LLMs), which we have carefully integrated into our system to meet our specific requirements and compliance constraints, including confidentiality and GDPR. In this paper, we share detailed insights into the architectural considerations, design, implementation, and subsequent updates of FhGenie. Additionally, we discuss challenges, observations, and the core lessons learned from its productive usage.