# AdaMoLE：以自适应低秩专家混合策略，对大型语言模型进行精准微调。

发布时间：2024年05月01日

`LLM应用` `机器学习`

> AdaMoLE: Fine-Tuning Large Language Models with Adaptive Mixture of Low-Rank Adaptation Experts

# 摘要

> 我们推出了 AdaMoLE，这是一种创新的微调大型语言模型（LLM）的方法，它通过自适应的低秩适应（LoRA）专家混合来实现。与传统的静态 top-k 激活策略不同，AdaMoLE 利用专用的阈值网络动态调整激活阈值，以适应多样化任务的复杂性变化。该方法通过在模型层中引入多个 LoRA 专家，并结合门控函数与阈值机制，能够根据输入情境精准地选择并激活最合适的专家。经过我们在多种常识推理和自然语言处理任务上的深入评估，AdaMoLE 的表现超越了传统基线。这一提升凸显了 AdaMoLE 在自适应选择 LoRA 专家方面的优势，它在不增加专家数量的前提下提升了模型效能。实验的验证不仅证明了 AdaMoLE 是一种增强 LLM 的可靠方法，也为未来自适应专家选择机制的研究指明了有价值方向，这可能会为优化各类语言处理任务的模型性能开辟新的可能性。

> We introduce AdaMoLE, a novel method for fine-tuning large language models (LLMs) through an Adaptive Mixture of Low-Rank Adaptation (LoRA) Experts. Moving beyond conventional methods that employ a static top-k strategy for activating experts, AdaMoLE dynamically adjusts the activation threshold using a dedicated threshold network, adaptively responding to the varying complexities of different tasks. By replacing a single LoRA in a layer with multiple LoRA experts and integrating a gating function with the threshold mechanism, AdaMoLE effectively selects and activates the most appropriate experts based on the input context. Our extensive evaluations across a variety of commonsense reasoning and natural language processing tasks show that AdaMoLE exceeds baseline performance. This enhancement highlights the advantages of AdaMoLE's adaptive selection of LoRA experts, improving model effectiveness without a corresponding increase in the expert count. The experimental validation not only confirms AdaMoLE as a robust approach for enhancing LLMs but also suggests valuable directions for future research in adaptive expert selection mechanisms, potentially broadening the scope for optimizing model performance across diverse language processing tasks.

[Arxiv](https://arxiv.org/abs/2405.00361)