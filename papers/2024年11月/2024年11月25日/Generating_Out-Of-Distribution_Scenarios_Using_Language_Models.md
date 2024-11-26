# 利用语言模型生成分布外的场景

发布时间：2024年11月25日

`LLM应用` `自动驾驶` `机器学习`

> Generating Out-Of-Distribution Scenarios Using Language Models

# 摘要

> 机器学习技术操控的自动驾驶汽车的部署，得在各类现实环境中展开广泛测试，妥善处理边缘情况和分布外场景，还要进行全面的安全验证，以保证这些系统能在难以预料的状况下安全、有效地行驶。应对分布外（OOD）驾驶场景对提升安全性极为关键，因为 OOD 场景有助于检验车辆自主系统中模型的可靠性。不过，由于其长尾分布以及在城市驾驶数据集中的稀缺性，生成 OOD 场景颇具难度。近来，大型语言模型（LLMs）在自动驾驶领域展现出良好前景，尤其是它们的零样本泛化和常识推理能力。在本文中，我们借助这些 LLM 的优势引入了一个生成各类 OOD 驾驶场景的框架。我们的方法利用 LLMs 构建分支树，每个分支代表一个独特的 OOD 场景。接着，这些场景在 CARLA 模拟器中通过一个自动框架进行模拟，该框架能让场景增强与相应的文本描述相匹配。我们通过大量模拟来评估框架，并通过衡量场景丰富程度的多样性指标来评估其性能。另外，我们引入了新的“OOD 性”指标，用于量化生成的场景偏离典型城市驾驶条件的程度。此外，我们还探究了现代视觉语言模型（VLMs）解读并安全驶过模拟 OOD 场景的能力。我们的研究成果为语言模型在处理城市驾驶情境中的 OOD 场景的可靠性提供了宝贵的见解。

> The deployment of autonomous vehicles controlled by machine learning techniques requires extensive testing in diverse real-world environments, robust handling of edge cases and out-of-distribution scenarios, and comprehensive safety validation to ensure that these systems can navigate safely and effectively under unpredictable conditions. Addressing Out-Of-Distribution (OOD) driving scenarios is essential for enhancing safety, as OOD scenarios help validate the reliability of the models within the vehicle's autonomy stack. However, generating OOD scenarios is challenging due to their long-tailed distribution and rarity in urban driving dataset. Recently, Large Language Models (LLMs) have shown promise in autonomous driving, particularly for their zero-shot generalization and common-sense reasoning capabilities. In this paper, we leverage these LLM strengths to introduce a framework for generating diverse OOD driving scenarios. Our approach uses LLMs to construct a branching tree, where each branch represents a unique OOD scenario. These scenarios are then simulated in the CARLA simulator using an automated framework that aligns scene augmentation with the corresponding textual descriptions. We evaluate our framework through extensive simulations, and assess its performance via a diversity metric that measures the richness of the scenarios. Additionally, we introduce a new "OOD-ness" metric, which quantifies how much the generated scenarios deviate from typical urban driving conditions. Furthermore, we explore the capacity of modern Vision-Language Models (VLMs) to interpret and safely navigate through the simulated OOD scenarios. Our findings offer valuable insights into the reliability of language models in addressing OOD scenarios within the context of urban driving.

[Arxiv](https://arxiv.org/abs/2411.16554)