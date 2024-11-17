# 平衡速度与稳定性：LLM 中 FP8 和 BF16 训练的利弊权衡

发布时间：2024年11月10日

`LLM应用` `模型训练`

> Balancing Speed and Stability: The Trade-offs of FP8 vs. BF16 Training in LLMs

# 摘要

> 大型语言模型（LLMs）凭借类人的语言理解与生成能力以及在多领域的适用性，吸引了众多关注。
  这类模型具有规模庞大、训练数据丰富的特点，持续拓展着自然语言处理的边界。比如，Llama 3 系列的旗舰模型拥有 4050 亿个参数，基于 15.6 万亿个标记进行训练，就彰显了这一趋势。训练此类模型所需的巨大算力，推动了对优化训练过程效率的持续研究，尤其是在使用低精度格式方面。
  NVIDIA 的 H100 GPU 除了常见的 FP16 和 BF16 格式，还支持 FP8，成为优化工作的重点。初步研究显示，相较于 BF16，FP8 能在不影响模型性能的前提下大幅缩短训练时间，是大规模模型训练的理想之选。不过，采用 FP8 更广泛的影响，特别是在训练稳定性和下游任务表现方面，尚未完全明晰。
  本研究深入探究了在训练 LLMs 时选用 FP8 而非 BF16 所涉及的实际权衡。

> Large Language Models (LLMs) have attracted significant attention due to their human-like language understanding and generation capabilities, as well as their applicability across various domains.
  These models, characterized by their massive scale and extensive training data, continue to push the boundaries of what is possible in natural language processing. The Llama 3 series, for instance, exemplifies this trend with its flagship model boasting 405 billion parameters trained on 15.6 trillion tokens. The immense computational demands associated with training such models have spurred ongoing research into optimizing the efficiency of the training process, particularly through the use of lower-precision formats.
  NVIDIA's H100 GPU, which introduces support for FP8 in addition to the more conventional FP16 and BF16 formats, has emerged as a focal point in this optimization effort. Preliminary studies suggest that FP8 could offer substantial reductions in training time without sacrificing model performance when compared to BF16, making it a promising candidate for large-scale model training. However, the broader implications of adopting FP8, particularly in terms of training stability and downstream task performance, have yet to be fully understood.
  In this study, we delve into the practical trade-offs involved in adopting FP8 over BF16 for training LLMs.

[Arxiv](https://arxiv.org/abs/2411.08719)