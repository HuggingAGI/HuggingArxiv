# 密集训练，稀疏推理：重新思考混合专家语言模型的训练

发布时间：2024年04月08日

`LLM应用` `语言模型` `计算效率`

> Dense Training, Sparse Inference: Rethinking Training of Mixture-of-Experts Language Models

# 摘要

> 摘要：与密集模型相比，专家混合（MoE）语言模型能够将计算成本降低 2 - 4 倍，且不会牺牲性能，这使得它们在计算受限的场景中效率更高。然而，MoE 模型通常需要 2 - 4 倍更多的参数才能达到与密集模型相当的性能，这导致了更大的 GPU 内存需求，并使得 MoE 模型在诸如自回归生成等 I/O 受限的场景中效率较低。在这项工作中，我们为 MoE 模型提出了一种混合密集训练和稀疏推理框架（DS-MoE），通过在训练期间对所有专家进行密集计算，在推理期间进行稀疏计算，实现了强大的计算和参数效率。我们在训练大型语言模型（LLM）上的实验表明，我们的 DS-MoE 模型比标准稀疏 MoE 更具参数效率，在总参数大小和性能方面与密集模型相当，同时计算成本更低（激活模型 30 - 40%的参数）。使用 vLLM 的性能测试表明，我们的 DS-MoE-6B 模型比类似的密集模型（如 Mistral-7B）运行速度快高达 1.86 倍，比可比的 MoE（如 DeepSeekMoE-16B 和 Qwen1.5-MoE-A2.7B）快 1.50 至 1.71 倍。

> 
Abstract:Mixture-of-Experts (MoE) language models can reduce computational costs by 2-4$\times$ compared to dense models without sacrificing performance, making them more efficient in computation-bounded scenarios. However, MoE models generally require 2-4$\times$ times more parameters to achieve comparable performance to a dense model, which incurs larger GPU memory requirements and makes MoE models less efficient in I/O-bounded scenarios like autoregressive generation. In this work, we propose a hybrid dense training and sparse inference framework for MoE models (DS-MoE) which achieves strong computation and parameter efficiency by employing dense computation across all experts during training and sparse computation during inference. Our experiments on training LLMs demonstrate that our DS-MoE models are more parameter-efficient than standard sparse MoEs and are on par with dense models in terms of total parameter size and performance while being computationally cheaper (activating 30-40% of the model's parameters). Performance tests using vLLM show that our DS-MoE-6B model runs up to $1.86\times$ faster than similar dense models like Mistral-7B, and between $1.50\times$ and $1.71\times$ faster than comparable MoEs, such as DeepSeekMoE-16B and Qwen1.5-MoE-A2.7B.
    

[Arxiv](https://arxiv.org/pdf/2404.05567)