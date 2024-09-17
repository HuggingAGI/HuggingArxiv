# LeGEND：借助大型语言模型，自上而下生成自动驾驶系统场景的创新方法

发布时间：2024年09月16日

`LLM应用` `自动驾驶` `测试与验证`

> LeGEND: A Top-Down Approach to Scenario Generation of Autonomous Driving Systems Assisted by Large Language Models

# 摘要

> 自动驾驶系统 (ADS) 的安全性至关重要，需要在公共道路部署前进行全面测试。现有测试方法多关注场景的关键性，却忽略了场景多样性对系统缺陷反映的重要性。为此，我们提出 LeGEND，采用自上而下的场景生成方式：从抽象功能场景逐步细化到具体场景，从而在功能层面控制多样性。然而，功能场景常以自然语言记录，难以被计算机精确处理。为此，LeGEND 利用大型语言模型 (LLM) 将文本功能场景转换为正式逻辑场景。为减少无用信息干扰，我们设计了两阶段转换过程，使用中间语言；因此，LeGEND 采用两个 LLM，一个提取信息，另一个转换为逻辑场景。我们在百度的行业级 ADS——Apollo 上评估了 LeGEND，结果显示其能有效识别关键场景，且在场景多样性上优于基线方法。此外，我们还展示了我们两阶段转换框架的优势，以及所采用 LLM 的准确性。

> Autonomous driving systems (ADS) are safety-critical and require comprehensive testing before their deployment on public roads. While existing testing approaches primarily aim at the criticality of scenarios, they often overlook the diversity of the generated scenarios that is also important to reflect system defects in different aspects. To bridge the gap, we propose LeGEND, that features a top-down fashion of scenario generation: it starts with abstract functional scenarios, and then steps downwards to logical and concrete scenarios, such that scenario diversity can be controlled at the functional level. However, unlike logical scenarios that can be formally described, functional scenarios are often documented in natural languages (e.g., accident reports) and thus cannot be precisely parsed and processed by computers. To tackle that issue, LeGEND leverages the recent advances of large language models (LLMs) to transform textual functional scenarios to formal logical scenarios. To mitigate the distraction of useless information in functional scenario description, we devise a two-phase transformation that features the use of an intermediate language; consequently, we adopt two LLMs in LeGEND, one for extracting information from functional scenarios, the other for converting the extracted information to formal logical scenarios. We experimentally evaluate LeGEND on Apollo, an industry-grade ADS from Baidu. Evaluation results show that LeGEND can effectively identify critical scenarios, and compared to baseline approaches, LeGEND exhibits evident superiority in diversity of generated scenarios. Moreover, we also demonstrate the advantages of our two-phase transformation framework, and the accuracy of the adopted LLMs.

[Arxiv](https://arxiv.org/abs/2409.10066)