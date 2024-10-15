# COrAL：一种高效迭代细化的无序语言建模方法

发布时间：2024年10月12日

`LLM理论` `人工智能`

> COrAL: Order-Agnostic Language Modeling for Efficient Iterative Refinement

# 摘要

> 迭代细化已成为提升大型语言模型（LLM）复杂任务能力的有效手段。然而，现有方法多在应用或提示层面依赖自回归（AR）建模进行迭代，导致高推理延迟。为此，我们提出上下文感知无序语言建模（COrAL），直接将迭代细化融入LLM架构，同时保持高效计算。COrAL在可控上下文窗口内处理多令牌依赖，使模型在生成过程中实现内部迭代细化。借助COrAL的无序特性，我们引入滑动块无序解码，在上下文窗口内进行多令牌前向预测与后向重建，从而在滑动块中并行迭代输出，捕捉多样依赖，避免顺序生成的高成本。实证显示，COrAL在推理任务中分别提升性能与速度，GSM8K准确性提升4.6%，LogiQA提升4.0%，推理速度提升3.9倍。代码生成初步结果显示，因无序输出不一致，通过率下降，凸显质量与速度的内在权衡。代码已公开，详见https://github.com/YuxiXie/COrAL。

> Iterative refinement has emerged as an effective paradigm for enhancing the capabilities of large language models (LLMs) on complex tasks. However, existing approaches typically implement iterative refinement at the application or prompting level, relying on autoregressive (AR) modeling. The sequential token generation in AR models can lead to high inference latency. To overcome these challenges, we propose Context-Wise Order-Agnostic Language Modeling (COrAL), which incorporates iterative refinement directly into the LLM architecture while maintaining computational efficiency. Our approach models multiple token dependencies within manageable context windows, enabling the model to perform iterative refinement internally during the generation process. Leveraging the order-agnostic nature of COrAL, we introduce sliding blockwise order-agnostic decoding, which performs multi-token forward prediction and backward reconstruction within context windows. This allows the model to iteratively refine its outputs in parallel in the sliding block, effectively capturing diverse dependencies without the high inference cost of sequential generation. Empirical evaluations on reasoning tasks demonstrate that COrAL improves performance and inference speed, respectively, achieving absolute accuracy gains of $4.6\%$ on GSM8K and $4.0\%$ on LogiQA, along with inference speedups of up to $3.9\times$ over next-token baselines. Preliminary results on code generation indicate a drop in pass rates due to inconsistencies in order-agnostic outputs, highlighting the inherent quality--speed trade-off. Our code is publicly available at https://github.com/YuxiXie/COrAL.

[Arxiv](https://arxiv.org/abs/2410.09675)