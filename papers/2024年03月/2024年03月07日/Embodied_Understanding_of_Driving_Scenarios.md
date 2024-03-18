# [深入探究驾驶场景中的具身认知]

发布时间：2024年03月07日

`Agent`

> Embodied Understanding of Driving Scenarios

> 具身场景理解为自主智能体洞悉复杂开放驾驶环境并作出恰当反应奠定了基础。目前的研究依赖于视觉-语言模型（VLMs），但这些模型局限于二维空间且欠缺空间感知及长期预测能力。为此，我们深入剖析自动驾驶的核心要素，并构建了针对性评估标准。现在，我们创新性地推出了“具身语言模型”（ELM）——一个专门为处理大规模空间与时间跨度驾驶场景而设计的整体解决方案。ELM 引入了空间感知预训练机制，确保智能体具备稳健的空间定位功能；同时采用时间感知令牌选择技术，精准捕捉时序线索。我们将 ELM 应用于重新构建的多元化基准测试中，全面超越了以往的最优方法，并承诺将所有相关代码、数据和模型公开共享。

> Embodied scene understanding serves as the cornerstone for autonomous agents to perceive, interpret, and respond to open driving scenarios. Such understanding is typically founded upon Vision-Language Models (VLMs). Nevertheless, existing VLMs are restricted to the 2D domain, devoid of spatial awareness and long-horizon extrapolation proficiencies. We revisit the key aspects of autonomous driving and formulate appropriate rubrics. Hereby, we introduce the Embodied Language Model (ELM), a comprehensive framework tailored for agents' understanding of driving scenes with large spatial and temporal spans. ELM incorporates space-aware pre-training to endow the agent with robust spatial localization capabilities. Besides, the model employs time-aware token selection to accurately inquire about temporal cues. We instantiate ELM on the reformulated multi-faced benchmark, and it surpasses previous state-of-the-art approaches in all aspects. All code, data, and models will be publicly shared.

[Arxiv](https://arxiv.org/abs/2403.04593)