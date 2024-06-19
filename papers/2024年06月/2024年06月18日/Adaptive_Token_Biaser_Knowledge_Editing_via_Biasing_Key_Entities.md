# 知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。

发布时间：2024年06月18日

`LLM应用

这篇论文主要介绍了自适应令牌偏差器（ATBias），这是一种新型的解码技术，旨在精准提升情境编辑（ICE）的性能，特别是在大型语言模型（LLMs）中更新知识记忆的应用。ATBias通过聚焦于与知识紧密相关的令牌来调整解码过程中的logits，从而提高知识编辑的效率和准确性。这种方法不需要对模型内部结构或外部提示进行调整，且适用于各种LLMs。因此，这篇论文属于LLM应用分类。` `知识更新`

> Adaptive Token Biaser: Knowledge Editing via Biasing Key Entities

# 摘要

> 大型语言模型（LLMs）中的知识记忆更新迅速，而情境编辑（ICE）是目前最有效的知识更新手段。最新研究通过改进解码策略来强化ICE，无需对模型内部结构或外部提示进行调整。但这种改进作用于整个生成序列，包括许多非关键令牌。为此，我们提出了自适应令牌偏差器（ATBias），一种新型解码技术，旨在精准提升ICE。ATBias在解码时聚焦于与知识紧密相关的令牌，通过匹配新旧知识相关的关键实体来调整其logits。实验证明，ATBias显著提升了ICE性能，相比现有方法提升了32.3%，且延迟仅为其一半。ATBias不仅增强了ICE的知识编辑能力，而且几乎无成本地适用于各类LLMs。

> The parametric knowledge memorized by large language models (LLMs) becomes outdated quickly. In-context editing (ICE) is currently the most effective method for updating the knowledge of LLMs. Recent advancements involve enhancing ICE by modifying the decoding strategy, obviating the need for altering internal model structures or adjusting external prompts. However, this enhancement operates across the entire sequence generation, encompassing a plethora of non-critical tokens. In this work, we introduce $\textbf{A}$daptive $\textbf{T}$oken $\textbf{Bias}$er ($\textbf{ATBias}$), a new decoding technique designed to enhance ICE. It focuses on the tokens that are mostly related to knowledge during decoding, biasing their logits by matching key entities related to new and parametric knowledge. Experimental results show that ATBias significantly enhances ICE performance, achieving up to a 32.3% improvement over state-of-the-art ICE methods while incurring only half the latency. ATBias not only improves the knowledge editing capabilities of ICE but can also be widely applied to LLMs with negligible cost.

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/x1.png)

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/x2.png)

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/x3.png)

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/x4.png)

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/ablation_1.png)

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/ablation_2.png)

![知识编辑新方法：自适应令牌偏置器，通过调整关键实体的偏置来实现。](../../../paper_images/2406.12468/ablation_3.png)

[Arxiv](https://arxiv.org/abs/2406.12468)