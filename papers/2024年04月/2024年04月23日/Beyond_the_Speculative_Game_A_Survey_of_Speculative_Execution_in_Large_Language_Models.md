# 超越猜测游戏：深入探究大型语言模型中的推测性执行机制

发布时间：2024年04月23日

`LLM理论` `计算机科学`

> Beyond the Speculative Game: A Survey of Speculative Execution in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）规模的不断增长，推理效率成为了提升性能的关键问题。与内存占用相比，延迟问题更为严重，因为一个LLM（如GPT-4）每天可能要处理数十亿次请求。这一问题主要源于LLMs固有的自回归特性，即解码时只能按顺序生成令牌。为了解决这一瓶颈，我们借鉴了计算机架构中的投机执行概念，采用“草拟后验证”的方法应用于LLM解码。在这种方法下，一系列令牌将通过一些启发式规则快速草拟，然后由LLM并行验证。这种并行化的推理方式显著提升了解码速度。近年来，LLMs的成功推动了相关文献的增长，但目前尚缺一篇综述文章来梳理这一领域的研究现状，并为未来的发展方向提供指导。为此，我们撰写了首篇综述论文，全面回顾并系统分类了LLMs中投机执行的相关研究（如分块并行解码、投机解码等），并基于这一分类法进行了深入的评述和比较分析。最终，我们指出了该领域面临的多项关键挑战和未来可能的研究方向。

> With the increasingly giant scales of (causal) large language models (LLMs), the inference efficiency comes as one of the core concerns along the improved performance. In contrast to the memory footprint, the latency bottleneck seems to be of greater importance as there can be billions of requests to a LLM (e.g., GPT-4) per day. The bottleneck is mainly due to the autoregressive innateness of LLMs, where tokens can only be generated sequentially during decoding. To alleviate the bottleneck, the idea of speculative execution, which originates from the field of computer architecture, is introduced to LLM decoding in a \textit{draft-then-verify} style. Under this regime, a sequence of tokens will be drafted in a fast pace by utilizing some heuristics, and then the tokens shall be verified in parallel by the LLM. As the costly sequential inference is parallelized, LLM decoding speed can be significantly boosted. Driven by the success of LLMs in recent couple of years, a growing literature in this direction has emerged. Yet, there lacks a position survey to summarize the current landscape and draw a roadmap for future development of this promising area. To meet this demand, we present the very first survey paper that reviews and unifies literature of speculative execution in LLMs (e.g., blockwise parallel decoding, speculative decoding, etc.) in a comprehensive framework and a systematic taxonomy. Based on the taxonomy, we present a critical review and comparative analysis of the current arts. Finally we highlight various key challenges and future directions to further develop the area.

[Arxiv](https://arxiv.org/abs/2404.14897)