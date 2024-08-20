# SMILE：基于预训练模型，实现零-shot 构建稀疏低秩专家混合体

发布时间：2024年08月19日

`LLM理论` `人工智能` `机器学习`

> SMILE: Zero-Shot Sparse Mixture of Low-Rank Experts Construction From Pre-Trained Foundation Models

# 摘要

> 随着深度模型训练成本的飙升，模型融合技术应运而生，旨在从现有模型中汲取知识。从基础的权重平均到高级的AdaMerging，模型融合不仅提升了性能，还加速了新模型的诞生。但参数间的干扰和融合过程的不可解释性仍是难题。本研究从子空间分析入手，重新定义参数干扰为优化问题，并创新性地提出零-shot稀疏低秩专家混合（SMILE）方法，实现模型无缝升级，无需额外数据或训练。我们通过扩展维度巧妙解决了参数干扰，并在多任务中验证了SMILE的强大适应性与扩展性。探索代码，尽在https://github.com/tanganke/fusion_bench。

> Deep model training on extensive datasets is increasingly becoming cost-prohibitive, prompting the widespread adoption of deep model fusion techniques to leverage knowledge from pre-existing models. From simple weight averaging to more sophisticated methods like AdaMerging, model fusion effectively improves model performance and accelerates the development of new models. However, potential interference between parameters of individual models and the lack of interpretability in the fusion progress remain significant challenges. Existing methods often try to resolve the parameter interference issue by evaluating attributes of parameters, such as their magnitude or sign, or by parameter pruning. In this study, we begin by examining the fine-tuning of linear layers through the lens of subspace analysis and explicitly define parameter interference as an optimization problem to shed light on this subject. Subsequently, we introduce an innovative approach to model fusion called zero-shot Sparse MIxture of Low-rank Experts (SMILE) construction, which allows for the upscaling of source models into an MoE model without extra data or further training. Our approach relies on the observation that fine-tuning mostly keeps the important parts from the pre-training, but it uses less significant or unused areas to adapt to new tasks. Also, the issue of parameter interference, which is intrinsically intractable in the original parameter space, can be managed by expanding the dimensions. We conduct extensive experiments across diverse scenarios, such as image classification and text generalization tasks, using full fine-tuning and LoRA fine-tuning, and we apply our method to large language models (CLIP models, Flan-T5 models, and Mistral-7B models), highlighting the adaptability and scalability of SMILE. Code is available at https://github.com/tanganke/fusion_bench

[Arxiv](https://arxiv.org/abs/2408.10174)