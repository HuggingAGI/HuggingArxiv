# MM-Embed：具有多模态大型语言模型的通用多模态检索

发布时间：2024年11月04日

`LLM应用` `信息检索` `多模态`

> MM-Embed: Universal Multimodal Retrieval with Multimodal LLMs

# 摘要

> 最先进的检索模型通常处理一个简单直接的搜索场景，其中检索任务是固定的（例如，找到一段文字来回答一个特定的问题），并且对于查询和检索结果仅支持单一模态。本文介绍了使用多模态大型语言模型（MLLMs）推进信息检索的技术，实现了更广泛的搜索场景，称为通用多模态检索，其中容纳了多种模态和多样化的检索任务。为此，我们首先研究在具有 16 个检索任务的 10 个数据集上对 MLLM 进行微调作为双编码器检索器。我们的实证结果表明，微调后的 MLLM 检索器能够理解具有挑战性的查询，包括文本和图像，但在跨模态检索任务中由于 MLLM 的模态偏差表现不如较小的 CLIP 检索器。为了解决这个问题，我们提出了模态感知的硬负样本挖掘来减轻 MLLM 检索器表现出的模态偏差。其次，我们提议持续微调通用多模态检索器，以增强其文本检索能力，同时保持多模态检索能力。结果，我们的模型 MM-Embed 在涵盖多个领域和任务的多模态检索基准 M-BEIR 上实现了最先进的性能，同时在 MTEB 检索基准上也超过了最先进的文本检索模型 NV-Embed-v1。最后，我们探索将现成的 MLLM 作为零样本重排序器来提示，以改进多模态检索器候选者的排名。我们发现，通过提示和重排序，当用户查询（例如，由文本和图像组成的查询）更复杂且难以理解时，MLLM 可以进一步改善多模态检索。这些发现也为未来推进通用多模态检索铺平了道路。

> State-of-the-art retrieval models typically address a straightforward search scenario, where retrieval tasks are fixed (e.g., finding a passage to answer a specific question) and only a single modality is supported for both queries and retrieved results. This paper introduces techniques for advancing information retrieval with multimodal large language models (MLLMs), enabling a broader search scenario, termed universal multimodal retrieval, where multiple modalities and diverse retrieval tasks are accommodated. To this end, we first study fine-tuning an MLLM as a bi-encoder retriever on 10 datasets with 16 retrieval tasks. Our empirical results show that the fine-tuned MLLM retriever is capable of understanding challenging queries, composed of both text and image, but underperforms a smaller CLIP retriever in cross-modal retrieval tasks due to modality bias from MLLMs. To address the issue, we propose modality-aware hard negative mining to mitigate the modality bias exhibited by MLLM retrievers. Second, we propose to continually fine-tune the universal multimodal retriever to enhance its text retrieval capability while maintaining multimodal retrieval capability. As a result, our model, MM-Embed, achieves state-of-the-art performance on the multimodal retrieval benchmark M-BEIR, which spans multiple domains and tasks, while also surpassing the state-of-the-art text retrieval model, NV-Embed-v1, on MTEB retrieval benchmark. Finally, we explore to prompt the off-the-shelf MLLMs as the zero-shot rerankers to refine the ranking of the candidates from the multimodal retriever. We find that through prompt-and-reranking, MLLMs can further improve multimodal retrieval when the user queries (e.g., text-image composed queries) are more complex and challenging to understand. These findings also pave the way to advance universal multimodal retrieval in the future.

[Arxiv](https://arxiv.org/abs/2411.02571)