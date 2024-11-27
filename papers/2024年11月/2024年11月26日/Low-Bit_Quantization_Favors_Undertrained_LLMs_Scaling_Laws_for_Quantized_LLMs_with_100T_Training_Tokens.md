# 低比特量化对未充分训练的 LLMs 有利：拥有 100T 训练令牌的量化 LLMs 的缩放规律

发布时间：2024年11月26日

`LLM理论` `语言模型` `量化研究`

> Low-Bit Quantization Favors Undertrained LLMs: Scaling Laws for Quantized LLMs with 100T Training Tokens

# 摘要

> 我们发现，低比特量化对未充分训练的大型语言模型（LLMs）更有利。通过观察可知，规模较大或训练令牌较少的模型在应用低比特量化时，所经历的量化引起的退化（QiD）较少；而经过大量训练令牌训练的较小模型，则会遭受显著的 QiD。为深入探究这一趋势，我们在受控环境中对超过 1500 个不同规模和不同训练水平（未充分训练或完全训练）的量化 LLM 检查点进行了研究，得出了用于理解 QiD 与训练令牌数量、模型规模和比特宽度等因素关系的缩放定律。
  依据得出的缩放定律，我们提出了一个新观点，即可以用 QiD 来衡量 LLM 的训练水平，并确定不同规模的完全训练的 LLM 所需的训练令牌数量。此外，我们运用缩放定律预测了用 100 万亿个令牌训练的不同规模 LLM 的量化性能。我们的预测显示，预计用超过 100 万亿个令牌训练的未来模型，其低比特量化性能可能不佳。这给未来的低比特量化带来了潜在挑战，也强调了在评估低比特量化研究时，了解模型训练水平的必要性。为助力未来对该问题的研究，我们在 https://huggingface.co/Xu-Ouyang 上发布了本工作中使用的所有 1500 多个量化检查点。

> We reveal that low-bit quantization favors undertrained large language models (LLMs) by observing that models with larger sizes or fewer training tokens experience less quantization-induced degradation (QiD) when applying low-bit quantization, whereas smaller models with extensive training tokens suffer significant QiD. To gain deeper insights into this trend, we study over 1500 quantized LLM checkpoints of various sizes and at different training levels (undertrained or fully trained) in a controlled setting, deriving scaling laws for understanding the relationship between QiD and factors such as the number of training tokens, model size and bit width.
  With the derived scaling laws, we propose a novel perspective that we can use QiD to measure an LLM's training levels and determine the number of training tokens required for fully training LLMs of various sizes. Moreover, we use the scaling laws to predict the quantization performance of different-sized LLMs trained with 100 trillion tokens. Our projection shows that the low-bit quantization performance of future models, which are expected to be trained with over 100 trillion tokens, may NOT be desirable. This poses a potential challenge for low-bit quantization in the future and highlights the need for awareness of a model's training level when evaluating low-bit quantization research. To facilitate future research on this problem, we release all the 1500+ quantized checkpoints used in this work at https://huggingface.co/Xu-Ouyang.

[Arxiv](https://arxiv.org/abs/2411.17691)