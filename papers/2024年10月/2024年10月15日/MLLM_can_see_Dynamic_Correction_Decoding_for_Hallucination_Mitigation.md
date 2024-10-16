# MLLM 能“看”吗？动态校正解码助力幻觉缓解

发布时间：2024年10月15日

`LLM应用` `人工智能` `计算机视觉`

> MLLM can see? Dynamic Correction Decoding for Hallucination Mitigation

# 摘要

> 多模态大型语言模型 (MLLM) 常出现幻觉现象，但其原因尚不明朗。我们通过实证分析发现，尽管 MLLM 在最终输出中错误生成对象，但它们在前几层中其实能识别视觉对象。我们推测，这可能是语言模型的强知识先验抑制了视觉信息，导致幻觉。为此，我们提出了一种新的动态校正解码方法 (DeCo)，它能自适应地选择前几层，并按比例将知识集成到最终层，以调整输出。DeCo 与模型无关，可与多种经典解码策略结合，适用于不同 MLLM。在广泛使用的基准测试中，DeCo 显著降低了幻觉率，展现了其减轻幻觉的潜力。代码已开源，详见 https://github.com/zjunlp/DeCo。

> Multimodal Large Language Models (MLLMs) frequently exhibit hallucination phenomena, but the underlying reasons remain poorly understood. In this paper, we present an empirical analysis and find that, although MLLMs incorrectly generate the objects in the final output, they are actually able to recognize visual objects in the preceding layers. We speculate that this may be due to the strong knowledge priors of the language model suppressing the visual information, leading to hallucinations. Motivated by this, we propose a novel dynamic correction decoding method for MLLMs (DeCo), which adaptively selects the appropriate preceding layers and proportionally integrates knowledge into the final layer to adjust the output logits. Note that DeCo is model agnostic and can be seamlessly incorporated with various classic decoding strategies and applied to different MLLMs. We evaluate DeCo on widely-used benchmarks, demonstrating that it can reduce hallucination rates by a large margin compared to baselines, highlighting its potential to mitigate hallucinations. Code is available at https://github.com/zjunlp/DeCo.

[Arxiv](https://arxiv.org/abs/2410.11779)