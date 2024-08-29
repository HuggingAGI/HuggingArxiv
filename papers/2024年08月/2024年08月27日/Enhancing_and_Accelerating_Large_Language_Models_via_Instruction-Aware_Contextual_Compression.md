# 借助指令感知上下文压缩技术，我们旨在提升和加速大型语言模型的性能。

发布时间：2024年08月27日

`LLM应用` `人工智能` `软件工程`

> Enhancing and Accelerating Large Language Models via Instruction-Aware Contextual Compression

# 摘要

> 大型语言模型（LLM）因其卓越的多任务表现而广受瞩目。为解决幻觉问题，LLM常采用检索增强技术，引入外部知识与上下文。然而，检索到的上下文常不准确且粒度粗糙，向LLM提供无关信息会导致响应质量下降、推理延迟增加及成本上升。本文提出“指令感知上下文压缩”方法，剔除冗余信息，优化LLM的运行效率与性能。实验显示，该方法大幅降低内存占用，缩短生成时间，性能与全上下文使用相当。具体成果包括：上下文成本削减50%，推理内存节省5%，速度提升2.2倍，Rouge-1仅微降0.047。这表明我们的方法在效率与性能间找到了理想平衡点。

> Large Language Models (LLMs) have garnered widespread attention due to their remarkable performance across various tasks. However, to mitigate the issue of hallucinations, LLMs often incorporate retrieval-augmented pipeline to provide them with rich external knowledge and context. Nevertheless, challenges stem from inaccurate and coarse-grained context retrieved from the retriever. Supplying irrelevant context to the LLMs can result in poorer responses, increased inference latency, and higher costs. This paper introduces a method called Instruction-Aware Contextual Compression, which filters out less informative content, thereby accelerating and enhancing the use of LLMs. The experimental results demonstrate that Instruction-Aware Contextual Compression notably reduces memory consumption and minimizes generation latency while maintaining performance levels comparable to those achieved with the use of the full context. Specifically, we achieved a 50% reduction in context-related costs, resulting in a 5% reduction in inference memory usage and a 2.2-fold increase in inference speed, with only a minor drop of 0.047 in Rouge-1. These findings suggest that our method strikes an effective balance between efficiency and performance.

[Arxiv](https://arxiv.org/abs/2408.15491)