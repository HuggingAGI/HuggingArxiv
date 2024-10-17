# HumanEval-V：通过编码任务，评估大型多模态模型在视觉理解和推理方面的表现。

发布时间：2024年10月16日

`LLM应用` `人工智能` `软件开发`

> HumanEval-V: Evaluating Visual Understanding and Reasoning Abilities of Large Multimodal Models Through Coding Tasks

# 摘要

> 编码任务是评估大型语言模型 (LLM) 的重要工具，因为它考验高级指令理解、复杂推理和功能程序实现——这些都是推动人工通用智能的关键能力。尽管大型多模态模型 (LMM) 在视觉感知和理解方面有所进步，但针对这些模型的严格编码基准仍显不足，尤其是在视觉推理任务中。为此，我们推出了 HumanEval-V，一个专为评估 LMM 视觉理解和推理能力而设计的新颖轻量级基准。HumanEval-V 包含 108 个精心挑选的入门级 Python 编码任务，源自 CodeForces 和 Stack Overflow 等平台。每个任务都经过改编，确保视觉元素与源数据区分开来，防止数据泄露。LMM 需根据视觉上下文和预定义的 Python 函数签名完成代码解决方案。每个任务都配有精心设计的测试用例，确保评估的全面性和可靠性。我们使用 HumanEval-V 测试了 19 个最先进的 LMM，发现显著挑战。例如，GPT-4o 在 pass@1 上仅达到 13%，pass@10 为 36.4%，而 70B 参数的开源模型在 pass@1 上得分低于 4%。消融研究进一步揭示了当前 LMM 在视觉推理和编码能力上的局限。这些结果指出了未来研究中需要加强 LMM 能力的关键领域。我们已在 https://github.com/HumanEval-V/HumanEval-V-Benchmark 开源了代码和基准。

> Coding tasks have been valuable for evaluating Large Language Models (LLMs), as they demand the comprehension of high-level instructions, complex reasoning, and the implementation of functional programs -- core capabilities for advancing Artificial General Intelligence. Despite the progress in Large Multimodal Models (LMMs), which extend LLMs with visual perception and understanding capabilities, there remains a notable lack of coding benchmarks that rigorously assess these models, particularly in tasks that emphasize visual reasoning. To address this gap, we introduce HumanEval-V, a novel and lightweight benchmark specifically designed to evaluate LMMs' visual understanding and reasoning capabilities through code generation. HumanEval-V includes 108 carefully crafted, entry-level Python coding tasks derived from platforms like CodeForces and Stack Overflow. Each task is adapted by modifying the context and algorithmic patterns of the original problems, with visual elements redrawn to ensure distinction from the source, preventing potential data leakage. LMMs are required to complete the code solution based on the provided visual context and a predefined Python function signature outlining the task requirements. Every task is equipped with meticulously handcrafted test cases to ensure a thorough and reliable evaluation of model-generated solutions. We evaluate 19 state-of-the-art LMMs using HumanEval-V, uncovering significant challenges. Proprietary models like GPT-4o achieve only 13% pass@1 and 36.4% pass@10, while open-weight models with 70B parameters score below 4% pass@1. Ablation studies further reveal the limitations of current LMMs in vision reasoning and coding capabilities. These results underscore key areas for future research to enhance LMMs' capabilities. We have open-sourced our code and benchmark at https://github.com/HumanEval-V/HumanEval-V-Benchmark.

[Arxiv](https://arxiv.org/abs/2410.12381)