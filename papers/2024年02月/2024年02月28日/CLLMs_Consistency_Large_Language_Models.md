# [CLLMs，即一致性大型语言模型，是针对提升模型输出稳定性和可靠性的新型研究方向。](https://arxiv.org/abs/2403.00835)

发布时间：2024年02月28日

`LLM应用`

> CLLMs: Consistency Large Language Models

> 雅可比等并行解码技术有望打破LLM解码过程的串行限制，通过并行化计算提高推断效率。但现实中，其相较于传统自回归解码并未取得显著加速效果，主要原因是单次固定点迭代步骤中难以准确预测多个令牌。为此，我们创新提出一种方法，致力于使LLM无论在哪种状态下都能快速收敛至雅可比轨迹上的固定点，具体做法是训练LLM确保以任何状态作为输入均能稳定预测出固定点。大量实验证明了该方法的有效性，在保证各领域特有及开放领域基准测试生成质量的同时，实现了2.4至3.4倍的生成速度提升。

> Parallel decoding methods such as Jacobi decoding show promise for more efficient LLM inference as it breaks the sequential nature of the LLM decoding process and transforms it into parallelizable computation. However, in practice, it achieves little speedup compared to traditional autoregressive (AR) decoding, primarily because Jacobi decoding seldom accurately predicts more than one token in a single fixed-point iteration step. To address this, we develop a new approach aimed at realizing fast convergence from any state to the fixed point on a Jacobi trajectory. This is accomplished by refining the target LLM to consistently predict the fixed point given any state as input. Extensive experiments demonstrate the effectiveness of our method, showing 2.4$\times$ to 3.4$\times$ improvements in generation speed while preserving generation quality across both domain-specific and open-domain benchmarks.

[Arxiv](https://arxiv.org/abs/2403.00835)