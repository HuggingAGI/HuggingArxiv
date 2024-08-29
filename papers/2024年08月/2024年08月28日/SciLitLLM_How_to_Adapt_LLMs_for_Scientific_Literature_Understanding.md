# SciLitLLM：探索大型语言模型在科学文献理解中的适应之道

发布时间：2024年08月28日

`LLM应用` `科学研究` `人工智能`

> SciLitLLM: How to Adapt LLMs for Scientific Literature Understanding

# 摘要

> 科学文献理解是推动科学发现的关键，它帮助我们提取关键信息并获得深刻见解。尽管大型语言模型（LLM）在多个领域取得了显著成就，但在科学文献理解方面仍面临挑战，主要源于科学知识的匮乏和对专业科学任务的不熟悉。为此，我们提出了一种结合持续预训练（CPT）和监督微调（SFT）的混合策略，旨在同时增强LLM的科学知识注入和特定领域任务的指令遵循能力。在这一过程中，我们面临两大挑战：一是构建高质量的CPT语料库，二是生成多样化的SFT指令。我们通过精细的流程解决了这些问题，包括PDF文本提取、内容解析纠错、质量筛选和合成指令生成。基于此策略，我们开发了专门用于科学文献理解的LLM系列——SciLitLLM，它们在相关基准测试中表现出色。我们的贡献主要体现在三个方面：首先，我们提出了一种有效的框架，通过结合CPT和SFT，使LLM更好地适应科学文献理解，并可轻松扩展到其他领域。其次，我们开发了一种基于LLM的合成方法，用于生成多样且高质量的科学指令，为较少代表性的科学领域提供了一套新的监督微调指令集——SciLitIns。最后，SciLitLLM在科学文献理解基准测试中取得了显著的性能提升。

> Scientific literature understanding is crucial for extracting targeted information and garnering insights, thereby significantly advancing scientific discovery. Despite the remarkable success of Large Language Models (LLMs), they face challenges in scientific literature understanding, primarily due to (1) a lack of scientific knowledge and (2) unfamiliarity with specialized scientific tasks.
  To develop an LLM specialized in scientific literature understanding, we propose a hybrid strategy that integrates continual pre-training (CPT) and supervised fine-tuning (SFT), to simultaneously infuse scientific domain knowledge and enhance instruction-following capabilities for domain-specific tasks.cIn this process, we identify two key challenges: (1) constructing high-quality CPT corpora, and (2) generating diverse SFT instructions. We address these challenges through a meticulous pipeline, including PDF text extraction, parsing content error correction, quality filtering, and synthetic instruction creation. Applying this strategy, we present a suite of LLMs: SciLitLLM, specialized in scientific literature understanding. These models demonstrate promising performance on scientific literature understanding benchmarks.
  Our contributions are threefold: (1) We present an effective framework that integrates CPT and SFT to adapt LLMs to scientific literature understanding, which can also be easily adapted to other domains. (2) We propose an LLM-based synthesis method to generate diverse and high-quality scientific instructions, resulting in a new instruction set -- SciLitIns -- for supervised fine-tuning in less-represented scientific domains. (3) SciLitLLM achieves promising performance improvements on scientific literature understanding benchmarks.

[Arxiv](https://arxiv.org/abs/2408.15545)