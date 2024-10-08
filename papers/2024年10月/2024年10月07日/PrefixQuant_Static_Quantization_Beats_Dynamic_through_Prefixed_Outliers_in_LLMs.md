# PrefixQuant：通过 LLM 中的前缀异常值，静态量化超越了动态量化。

发布时间：2024年10月07日

`LLM理论` `人工智能` `云计算`

> PrefixQuant: Static Quantization Beats Dynamic through Prefixed Outliers in LLMs

# 摘要

> 量化是提升大型语言模型 (LLM) 部署效率的关键，通过优化内存和推理速度。现有方法多聚焦于通道异常值，却忽视了令牌异常值，导致依赖高成本的动态量化。为此，我们推出了 PrefixQuant，一种无需重新训练即可离线隔离异常值的创新技术。PrefixQuant 通过识别高频异常值并将其前缀化，有效防止推理中的异常生成，简化量化过程。据我们所知，这是首个实现高效静态量化的技术，超越了昂贵的动态量化。例如，在 W4A4KV4 Llama-3-8B 模型中，PrefixQuant 的静态量化在 WikiText2 困惑度和常识推理任务准确率上均表现优异，推理速度也显著提升。代码已开源，详见 \url{https://github.com/ChenMnZ/PrefixQuant}。

> Quantization is essential for deploying Large Language Models (LLMs) by enhancing memory efficiency and inference speed. Existing methods for activation quantization mainly address channel-wise outliers, often neglecting token-wise outliers, leading to reliance on costly per-token dynamic quantization. To address this, we introduce PrefixQuant, a novel technique that isolates outlier tokens offline without re-training. Specifically, PrefixQuant identifies high-frequency outlier tokens and prefixes them in the KV cache, preventing the generation of outlier tokens during inference and simplifying quantization. To our knowledge, PrefixQuant is the first to enable efficient per-tensor static quantization to outperform expensive per-token dynamic quantization. For instance, in W4A4KV4 (4- bit weight, 4-bit activation, and 4-bit KV cache) Llama-3-8B, PrefixQuant with per-tensor static quantization achieves a 7.43 WikiText2 perplexity and 71.08% average accuracy on 5 common-sense reasoning tasks, outperforming previous per-token dynamic quantization methods like QuaRot with 0.98 perplexity improvement and +5.98 points accuracy. Additionally, the inference speed of W4A4 quantized models using PrefixQuant is 1.60x to 2.81x faster than FP16 models and exceeds QuaRot models by 1.2x to 1.3x. Our code is available at \url{https://github.com/ChenMnZ/PrefixQuant}.

[Arxiv](https://arxiv.org/abs/2410.05265)