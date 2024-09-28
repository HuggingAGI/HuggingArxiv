# 推理时刻的语言模型对齐，借助综合价值指导实现。

发布时间：2024年09月26日

`LLM应用` `人工智能`

> Inference-Time Language Model Alignment via Integrated Value Guidance

# 摘要

> 大型语言模型通常需要复杂的微调来符合人类偏好，但我们提出了 $\textit{Integrated Value Guidance}$ (IVG)，一种在推理时高效对齐模型的方法，无需直接微调。IVG 通过隐式和显式价值函数分别在标记和块级别指导解码，优于传统方法。在情感生成和摘要任务中，IVG 显著提升了模型对齐效果。在 AlpacaEval 2.0 基准测试中，IVG 使模型在长度控制下的胜率大幅提升，如 $\texttt{Mistral-7B-Instruct-v0.2}$ 从 $19.51\%$ 提升至 $26.51\%$，$\texttt{Mixtral-8x7B-Instruct-v0.1}$ 从 $25.58\%$ 提升至 $33.75\%$（使用 Tulu 指导）。

> Large language models are typically fine-tuned to align with human preferences, but tuning large models is computationally intensive and complex. In this work, we introduce $\textit{Integrated Value Guidance}$ (IVG), a method that uses implicit and explicit value functions to guide language model decoding at token and chunk-level respectively, efficiently aligning large language models purely at inference time. This approach circumvents the complexities of direct fine-tuning and outperforms traditional methods. Empirically, we demonstrate the versatility of IVG across various tasks. In controlled sentiment generation and summarization tasks, our method significantly improves the alignment of large models using inference-time guidance from $\texttt{gpt2}$-based value functions. Moreover, in a more challenging instruction-following benchmark AlpacaEval 2.0, we show that both specifically tuned and off-the-shelf value functions greatly improve the length-controlled win rates of large models against $\texttt{gpt-4-turbo}$ (e.g., $19.51\% \rightarrow 26.51\%$ for $\texttt{Mistral-7B-Instruct-v0.2}$ and $25.58\% \rightarrow 33.75\%$ for $\texttt{Mixtral-8x7B-Instruct-v0.1}$ with Tulu guidance).

[Arxiv](https://arxiv.org/abs/2409.17819)