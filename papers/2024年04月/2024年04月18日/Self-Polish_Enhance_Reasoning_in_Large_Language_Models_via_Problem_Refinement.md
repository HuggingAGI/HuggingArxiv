# 自我精炼：优化问题以增强大型语言模型的推理能力

发布时间：2024年04月18日

`LLM应用

这篇论文摘要主要讨论了一种新的方法——自我打磨（SP）方法，用于提升大型语言模型（LLM）的多步推理能力。这种方法通过引导模型逐步优化问题，使其更清晰易解，从而提高推理性能。此外，研究还开发了多种自动提示变体，并建立了自我打磨提示库供社区使用。这种方法与其他推理侧提示方法（如思维链CoT）兼容，可以与尖端技术结合，实现更进一步的提升。实验结果显示，该方法在多个模型的推理基准测试中表现出色且稳定，并在鲁棒性评估中取得了显著成绩。因此，这篇论文属于LLM应用类别，因为它专注于改进LLM的实际应用性能。` `人工智能`

> Self-Polish: Enhance Reasoning in Large Language Models via Problem Refinement

# 摘要

> 为了增强大型语言模型的多步推理能力，研究人员深入研究了提示方法，尤其是思维链（CoT）方法，它能激发类似人类的推理过程。然而，他们未曾注意到通过提出更优质问题来提升模型推理性能的可能性。本研究从问题角度出发，创新性地提出了自我打磨（SP）方法，该方法通过引导模型逐步优化问题，使其更清晰易解，从而提升推理能力。我们还开发了多种自动提示变体，并建立了自我打磨提示库供社区使用。SP方法与CoT等其他推理侧提示方法兼容，可与尖端技术结合，实现更进一步的提升。实验结果显示，该方法在五个不同模型的推理基准测试中表现出色且稳定。此外，它在鲁棒性评估中也取得了令人瞩目的成绩。相关代码和提示已公开于https://github.com/WooooDyy/Self-Polish。

> To enhance the multi-step reasoning capabilities of large language models, researchers have extensively explored prompting methods, notably the Chain-of-Thought (CoT) method which explicitly elicits human-like rationales. However, they have inadvertently overlooked the potential of enhancing model reasoning performance by formulating higher-quality problems. In this work, we start from the problem side and propose Self-Polish (SP), a novel method that facilitates the model's reasoning by guiding it to progressively refine the given problems to be more comprehensible and solvable. We also explore several automatic prompting varients and propose the Self-Polish prompt bank for the community. SP is orthogonal to all other prompting methods of answer/reasoning side like CoT, allowing for seamless integration with state-of-the-art techniques for further improvement. Thorough experiments show that the proposed method attains notable and consistent effectiveness on five reasoning benchmarks across different models. Furthermore, our method also showcases impressive performance on robustness evaluation. Codes and prompts are available at https://github.com/WooooDyy/Self-Polish.

[Arxiv](https://arxiv.org/abs/2305.14497)