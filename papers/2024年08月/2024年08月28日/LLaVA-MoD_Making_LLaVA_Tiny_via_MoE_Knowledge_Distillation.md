# LLaVA-MoD：借助 MoE 知识蒸馏技术，让 LLaVA 更精简

发布时间：2024年08月28日

`LLM应用` `人工智能` `多模态学习`

> LLaVA-MoD: Making LLaVA Tiny via MoE Knowledge Distillation

# 摘要

> 我们推出了LLaVA-MoD框架，通过从大型多模态语言模型中提炼知识，高效训练小型多模态模型。该框架解决了两大难题：一是通过融入稀疏专家混合架构，优化小型模型的结构，平衡效率与表达力；二是采用渐进式知识转移策略，确保知识全面迁移。实验证明，LLaVA-MoD在多模态任务中表现卓越，参数少、成本低，甚至在幻觉测试中超越了大型模型。代码即将在GitHub上发布。

> We introduce LLaVA-MoD, a novel framework designed to enable the efficient training of small-scale Multimodal Language Models (s-MLLM) by distilling knowledge from large-scale MLLM (l-MLLM). Our approach tackles two fundamental challenges in MLLM distillation. First, we optimize the network structure of s-MLLM by integrating a sparse Mixture of Experts (MoE) architecture into the language model, striking a balance between computational efficiency and model expressiveness. Second, we propose a progressive knowledge transfer strategy to ensure comprehensive knowledge migration. This strategy begins with mimic distillation, where we minimize the Kullback-Leibler (KL) divergence between output distributions to enable the student model to emulate the teacher network's understanding. Following this, we introduce preference distillation via Direct Preference Optimization (DPO), where the key lies in treating l-MLLM as the reference model. During this phase, the s-MLLM's ability to discriminate between superior and inferior examples is significantly enhanced beyond l-MLLM, leading to a better student that surpasses its teacher, particularly in hallucination benchmarks. Extensive experiments demonstrate that LLaVA-MoD outperforms existing models across various multimodal benchmarks while maintaining a minimal number of activated parameters and low computational costs. Remarkably, LLaVA-MoD, with only 2B activated parameters, surpasses Qwen-VL-Chat-7B by an average of 8.8% across benchmarks, using merely 0.3% of the training data and 23% trainable parameters. These results underscore LLaVA-MoD's ability to effectively distill comprehensive knowledge from its teacher model, paving the way for the development of more efficient MLLMs. The code will be available on: https://github.com/shufangxun/LLaVA-MoD.

[Arxiv](https://arxiv.org/abs/2408.15881)