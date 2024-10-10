# ParallelSpec：高效推测解码的并行起草工具

发布时间：2024年10月07日

`LLM理论` `人工智能`

> ParallelSpec: Parallel Drafter for Efficient Speculative Decoding

# 摘要

> 推测解码已成为 LLM 推理的高效方案，其中小型草稿器低成本预测未来标记，目标模型并行验证。然而，现有方法仍自回归草拟标记，以维持语言建模的顺序依赖，这在推测解码中造成巨大计算负担。我们提出 ParallelSpec，替代自回归草拟策略。与推测阶段的自回归草拟不同，我们训练并行草稿器作为高效推测模型。ParallelSpec 使用单一模型并行预测多个未来标记，并可最小成本集成到任何需要对齐草稿器和目标模型输出分布的推测解码框架中。实验显示，ParallelSpec 在不同领域文本生成基准测试中将基线方法延迟加速高达 62%，并在 Llama-2-13B 模型上实现 2.84 倍总体加速。

> Speculative decoding has proven to be an efficient solution to large language model (LLM) inference, where the small drafter predicts future tokens at a low cost, and the target model is leveraged to verify them in parallel. However, most existing works still draft tokens auto-regressively to maintain sequential dependency in language modeling, which we consider a huge computational burden in speculative decoding. We present ParallelSpec, an alternative to auto-regressive drafting strategies in state-of-the-art speculative decoding approaches. In contrast to auto-regressive drafting in the speculative stage, we train a parallel drafter to serve as an efficient speculative model. ParallelSpec learns to efficiently predict multiple future tokens in parallel using a single model, and it can be integrated into any speculative decoding framework that requires aligning the output distributions of the drafter and the target model with minimal training cost. Experimental results show that ParallelSpec accelerates baseline methods in latency up to 62% on text generation benchmarks from different domains, and it achieves 2.84X overall speedup on the Llama-2-13B model using third-party evaluation criteria.

[Arxiv](https://arxiv.org/abs/2410.05589)