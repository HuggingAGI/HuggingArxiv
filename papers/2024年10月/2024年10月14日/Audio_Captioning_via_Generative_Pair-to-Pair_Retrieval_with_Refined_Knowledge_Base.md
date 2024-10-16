# 音频描述：基于精炼知识库的生成式配对检索

发布时间：2024年10月14日

`RAG` `音频处理` `人工智能`

> Audio Captioning via Generative Pair-to-Pair Retrieval with Refined Knowledge Base

# 摘要

> 音频理解任务的最新进展得益于 LLM 的推理能力，但让 LLM 学习音频概念需要大量数据和计算资源。为此，Retrieval-Augmented Generation (RAG) 从知识库中检索音频-文本对，并结合查询音频生成准确文本。本文探讨了不同检索方法和知识库对音频-文本对相关性和字幕性能的影响。我们提出生成对-对检索，利用生成的字幕精准匹配相关音频-文本对，提升检索信息的相关性和准确性。同时，我们优化知识库，仅保留与上下文意图一致的音频-文本对。实验结果表明，我们的方法在多个基准测试中达到最先进水平，消融研究进一步验证了其有效性。

> Recent advances in audio understanding tasks leverage the reasoning capabilities of LLMs. However, adapting LLMs to learn audio concepts requires massive training data and substantial computational resources. To address these challenges, Retrieval-Augmented Generation (RAG) retrieves audio-text pairs from a knowledge base (KB) and augments them with query audio to generate accurate textual responses. In RAG, the relevance of the retrieved information plays a crucial role in effectively processing the input. In this paper, we analyze how different retrieval methods and knowledge bases impact the relevance of audio-text pairs and the performance of audio captioning with RAG. We propose generative pair-to-pair retrieval, which uses the generated caption as a text query to accurately find relevant audio-text pairs to the query audio, thereby improving the relevance and accuracy of retrieved information. Additionally, we refine the large-scale knowledge base to retain only audio-text pairs that align with the contextualized intents. Our approach achieves state-of-the-art results on benchmarks including AudioCaps, Clotho, and Auto-ACD, with detailed ablation studies validating the effectiveness of our retrieval and KB construction methods.

[Arxiv](https://arxiv.org/abs/2410.10913)