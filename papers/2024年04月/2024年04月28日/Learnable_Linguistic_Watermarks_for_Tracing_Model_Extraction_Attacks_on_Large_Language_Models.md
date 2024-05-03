# 为大型语言模型量身定制的可学习语言水印技术，旨在有效追踪并防范模型提取攻击。

发布时间：2024年04月28日

`LLM应用` `人工智能安全` `知识产权保护`

> Learnable Linguistic Watermarks for Tracing Model Extraction Attacks on Large Language Models

# 摘要

> 随着人工智能领域的迅猛发展，确保大型语言模型（LLMs）的知识产权安全变得至关重要。目前，面对模型抽取攻击，主流的水印技术主要采用在模型逻辑输出中嵌入信号或对文本进行后期处理，这些手段大多基于经验。我们提出了一种创新的方法，通过在LLMs中嵌入可学习的语言学水印，用以追踪和防范模型抽取攻击。该方法通过在标记频率分布中引入控制性噪声，巧妙地调整了LLM的输出分布，嵌入了一种统计上可识别的水印。我们采用了统计假设检验和信息论的工具，特别是Kullback-Leibler散度，以高效区分原始与修改后的分布。我们的水印技术在保护模型安全的同时，保持了输出质量，实现了低误报率和误漏率，确保了LLM原始性能的稳定。

> In the rapidly evolving domain of artificial intelligence, safeguarding the intellectual property of Large Language Models (LLMs) is increasingly crucial. Current watermarking techniques against model extraction attacks, which rely on signal insertion in model logits or post-processing of generated text, remain largely heuristic. We propose a novel method for embedding learnable linguistic watermarks in LLMs, aimed at tracing and preventing model extraction attacks. Our approach subtly modifies the LLM's output distribution by introducing controlled noise into token frequency distributions, embedding an statistically identifiable controllable watermark.We leverage statistical hypothesis testing and information theory, particularly focusing on Kullback-Leibler Divergence, to differentiate between original and modified distributions effectively. Our watermarking method strikes a delicate well balance between robustness and output quality, maintaining low false positive/negative rates and preserving the LLM's original performance.

[Arxiv](https://arxiv.org/abs/2405.01509)