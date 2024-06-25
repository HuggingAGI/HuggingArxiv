# LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型

发布时间：2024年06月24日

`LLM应用

这篇论文主要探讨了如何从现有的密集模型（如LLaMA-2 7B）构建MoE（Mixture of Experts）模型，即LLaMA-MoE模型。论文详细介绍了专家构建和持续预训练的过程，并展示了这种模型在保持语言处理能力的同时，能够智能地分配输入令牌给特定专家，从而仅激活部分参数。这种模型的构建和优化是为了扩展大型语言模型的能力，属于LLM应用的范畴。` `模型优化`

> LLaMA-MoE: Building Mixture-of-Experts from LLaMA with Continual Pre-training

# 摘要

> MoE 框架因其扩展大型语言模型的潜力而日益流行，但大规模从头训练 MoE 仍受限于数据需求和稳定性问题。为此，我们探索了从现有密集模型构建 MoE 的新途径。具体而言，我们基于 LLaMA-2 7B 模型，通过专家构建和持续预训练两个关键步骤，成功打造了 LLaMA-MoE 模型。专家构建将 FFNs 参数分割为多个专家，而持续预训练则深化了 MoE 模型及其门网络的训练。本文详细讨论了专家构建的多种方法及持续预训练的数据采样策略。最终，我们的 LLaMA-MoE 模型不仅保持了强大的语言处理能力，还能智能地将输入令牌分配给特定专家，仅激活部分参数。实证研究表明，经过 200B 令牌的训练，LLaMA-MoE-3.5B 模型在性能上显著超越了激活参数相似的密集模型。相关代码和模型已公开于 https://github.com/pjlab-sys4nlp/llama-moe。

> Mixture-of-Experts (MoE) has gained increasing popularity as a promising framework for scaling up large language models (LLMs). However, training MoE from scratch in a large-scale setting still suffers from data-hungry and instability problems. Motivated by this limit, we investigate building MoE models from existing dense large language models. Specifically, based on the well-known LLaMA-2 7B model, we obtain an MoE model by: (1) Expert Construction, which partitions the parameters of original Feed-Forward Networks (FFNs) into multiple experts; (2) Continual Pre-training, which further trains the transformed MoE model and additional gate networks. In this paper, we comprehensively explore different methods for expert construction and various data sampling strategies for continual pre-training. After these stages, our LLaMA-MoE models could maintain language abilities and route the input tokens to specific experts with part of the parameters activated. Empirically, by training 200B tokens, LLaMA-MoE-3.5B models significantly outperform dense models that contain similar activation parameters. The source codes and models are available at https://github.com/pjlab-sys4nlp/llama-moe .

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x1.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x2.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x3.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x4.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x5.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x6.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x7.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x8.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x9.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x10.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x11.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x12.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x13.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x14.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x15.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x16.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x17.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x18.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x19.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x20.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x21.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x22.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x23.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x24.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x25.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x26.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x27.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x28.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x29.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x30.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x31.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x32.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x33.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x34.png)

![LLaMA-MoE：基于LLaMA架构，通过持续预训练打造专家混合模型](../../../paper_images/2406.16554/x35.png)

[Arxiv](https://arxiv.org/abs/2406.16554)