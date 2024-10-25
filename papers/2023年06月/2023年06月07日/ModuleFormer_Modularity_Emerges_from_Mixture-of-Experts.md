# ModuleFormer：模块化从专家混合中出现

发布时间：2023年06月07日

`LLM理论` `人工智能` `神经网络`

> ModuleFormer: Modularity Emerges from Mixture-of-Experts

# 摘要

> 摘要：大型语言模型（LLMs）已经取得了显著的成果。然而，现有的模型训练和部署成本高昂，并且在不遗忘先前知识的情况下难以将其知识扩展到预训练数据之外。本文提出了一种新的神经网络架构——ModuleFormer，它利用模块化来提高大型语言模型的效率和灵活性。ModuleFormer 基于稀疏混合专家（SMoE）。与之前基于 SMoE 的模块化语言模型不同，后者需要有领域标签的数据来学习特定领域的专家，而 ModuleFormer 可以通过其新的负载均衡和集中损失从未经整理的数据中诱导出模块化。ModuleFormer 是一种模块化架构，包括两种不同类型的模块：新的分拆注意力头和前馈专家。在训练和推理过程中，不同的模块根据输入标记稀疏地被激活。在我们的实验中，我们发现模块化架构为大型预训练语言模型提供了三个重要的能力：1）效率，因为 ModuleFormer 对于每个输入标记仅激活其模块的子集，因此它可以以两倍以上的吞吐量达到与密集型 LLMs 相同的性能；2）可扩展性，ModuleFormer 比密集型 LLMs 更能抵御灾难性遗忘，并且可以轻松地用新模块扩展以学习训练数据中未包含的新知识；3）专业化，微调 ModuleFormer 可以将一部分模块专门用于微调任务，并且与任务无关的模块可以轻松修剪以进行轻量级部署。

> 
Abstract:Large Language Models (LLMs) have achieved remarkable results. However, existing models are expensive to train and deploy, and it is also difficult to expand their knowledge beyond pre-training data without forgetting previous knowledge. This paper proposes a new neural network architecture, ModuleFormer, that leverages modularity to improve the efficiency and flexibility of large language models. ModuleFormer is based on the Sparse Mixture of Experts (SMoE). Unlike the previous SMoE-based modular language model, which requires domain-labeled data to learn domain-specific experts, ModuleFormer can induce modularity from uncurated data with its new load balancing and concentration losses. ModuleFormer is a modular architecture that includes two different types of modules: new stick-breaking attention heads and feedforward experts. Different modules are sparsely activated conditions on the input token during training and inference. In our experiment, we found that the modular architecture enables three important abilities for large pre-trained language models: 1) Efficiency, since ModuleFormer only activates a subset of its modules for each input token, thus it could achieve the same performance as dense LLMs with more than two times throughput; 2) Extendability, ModuleFormer is more immune to catastrophic forgetting than dense LLMs and can be easily extended with new modules to learn new knowledge that is not included in the training data; 3) Specialisation, finetuning ModuleFormer could specialize a subset of modules to the finetuning task and the task-unrelated modules could be easily pruned for a lightweight deployment.
    

[Arxiv](https://arxiv.org/pdf/2306.04640)