# 全面评估了高达 405B 的量化指令调优大型语言模型，通过实验分析揭示其性能。

发布时间：2024年09月17日

`LLM理论` `人工智能`

> A Comprehensive Evaluation of Quantized Instruction-Tuned Large Language Models: An Experimental Analysis up to 405B

# 摘要

> 以往研究多用量化的 LLM 进行评估，但指标有限，如困惑度或基本知识任务和旧数据集。此外，近期大规模模型如 Llama 3.1（高达 405B）尚未充分检验。本文针对从 7B 到 405B 的不同模型，评估了使用 GPTQ、AWQ、SmoothQuant 和 FP8 等量化方法的指令调优 LLM 性能。通过 13 个基准，我们在常识问答、知识与语言理解、指令跟随、幻觉检测、数学和对话六类任务中进行评估。研究发现：(1) 较大 LLM 量化至与较小 FP16 LLM 相似尺寸，通常在多数基准上表现更佳，但幻觉检测和指令跟随除外；(2) 性能因量化方法、模型大小和比特宽度而异，权重仅方法在大型模型中效果更佳；(3) 任务难度对量化导致的准确性下降影响不大；(4) MT-Bench 评估方法在近期高性能 LLM 间区分能力有限。

> Prior research works have evaluated quantized LLMs using limited metrics such as perplexity or a few basic knowledge tasks and old datasets. Additionally, recent large-scale models such as Llama 3.1 with up to 405B have not been thoroughly examined. This paper evaluates the performance of instruction-tuned LLMs across various quantization methods (GPTQ, AWQ, SmoothQuant, and FP8) on models ranging from 7B to 405B. Using 13 benchmarks, we assess performance across six task types: commonsense Q\&A, knowledge and language understanding, instruction following, hallucination detection, mathematics, and dialogue. Our key findings reveal that (1) quantizing a larger LLM to a similar size as a smaller FP16 LLM generally performs better across most benchmarks, except for hallucination detection and instruction following; (2) performance varies significantly with different quantization methods, model size, and bit-width, with weight-only methods often yielding better results in larger models; (3) task difficulty does not significantly impact accuracy degradation due to quantization; and (4) the MT-Bench evaluation method has limited discriminatory power among recent high-performing LLMs.

[Arxiv](https://arxiv.org/abs/2409.11055)