# 借助大型语言模型实现灰盒模糊测试中的种子生成

发布时间：2024年11月27日

`LLM应用` `软件测试` `漏洞检测`

> Harnessing Large Language Models for Seed Generation in Greybox Fuzzing

# 摘要

> Greybox 模糊测试已成为探寻软件漏洞的首选技术，在效率与探索深度之间达成平衡。尽管研究聚焦于改进模糊测试技术，然而高质量初始种子的重要性依旧关键，却常被忽视。现有的种子生成方法存在局限，尤其对于具有非标准或自定义输入格式的程序。大型语言模型（LLMs）已在众多领域掀起变革，在理解和生成各知识领域的复杂模式方面展现出空前能力。本文引入了 SeedMind，这是一个借助 LLMs 以智能种子生成来推动 Greybox 模糊测试的新系统。与以往方法不同，SeedMind 利用 LLMs 创建测试用例生成器，而非直接生成测试用例。我们的方法实现了一个迭代、反馈驱动的流程，引导 LLM 逐步优化测试用例的生成，以提高代码覆盖的深度和广度。在开发 SeedMind 时，我们攻克了关键难题，包括输入格式限制、上下文窗口约束以及确保一致且具有进度感知的行为。对实际应用的深度评估显示，SeedMind 能有效利用 LLMs 生成高质量测试用例，助力错误查找中的模糊测试，其效用堪比人类创建的种子，且显著优于现有的基于 LLM 的解决方案。

> Greybox fuzzing has emerged as a preferred technique for discovering software bugs, striking a balance between efficiency and depth of exploration. While research has focused on improving fuzzing techniques, the importance of high-quality initial seeds remains critical yet often overlooked. Existing methods for seed generation are limited, especially for programs with non-standard or custom input formats. Large Language Models (LLMs) has revolutionized numerous domains, showcasing unprecedented capabilities in understanding and generating complex patterns across various fields of knowledge. This paper introduces SeedMind, a novel system that leverages LLMs to boost greybox fuzzing through intelligent seed generation. Unlike previous approaches, SeedMind employs LLMs to create test case generators rather than directly producing test cases. Our approach implements an iterative, feedback-driven process that guides the LLM to progressively refine test case generation, aiming for increased code coverage depth and breadth. In developing SeedMind, we addressed key challenges including input format limitations, context window constraints, and ensuring consistent, progress-aware behavior. Intensive evaluations with real-world applications show that SeedMind effectively harnesses LLMs to generate high-quality test cases and facilitate fuzzing in bug finding, presenting utility comparable to human-created seeds and significantly outperforming the existing LLM-based solutions.

[Arxiv](https://arxiv.org/abs/2411.18143)