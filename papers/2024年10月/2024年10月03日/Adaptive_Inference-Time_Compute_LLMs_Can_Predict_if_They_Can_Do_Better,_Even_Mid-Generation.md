# LLM 具备自适应推理时计算能力，即使在生成过程中也能预测自身表现是否还有提升空间。

发布时间：2024年10月03日

`LLM应用` `人工智能`

> Adaptive Inference-Time Compute: LLMs Can Predict if They Can Do Better, Even Mid-Generation

# 摘要

> 推理时计算是提升大型语言模型（LLM）性能的有效手段，其中 Best-of-N 采样技术应用广泛。然而，这种方法计算成本高，需依赖外部奖励模型并生成多个样本。为此，我们提出了一种新的生成自评估方案，旨在自适应减少样本数量，同时保持甚至提升性能。通过生成奖励模型，LLM 能在生成过程中预测重新开始是否能产生更好结果，无需外部模型。这一能力成本极低，仅需生成一个预定义令牌。实验表明，Llama 3.1 8B 在 AlpacaEval 上对 GPT-4 的胜率从 21% 提升至 34%，GSM8K 数学性能从 84% 提升至 91%。通过自适应采样和温度调整，我们发现 74% 的性能提升仅需 1.2 个样本。此外，生成过程中可早期修剪 50-75% 的样本，性能影响微乎其微。总体而言，我们的方法使 LLM 在推理时的计算更加高效和可扩展。

> Inference-time computation is a powerful paradigm to enhance the performance of large language models (LLMs), with Best-of-N sampling being a widely used technique. However, this method is computationally expensive, requiring both (1) an external reward model and (2) the generation of multiple samples. In this work, we introduce a new generative self-evaluation scheme designed to adaptively reduce the number of generated samples while maintaining or even improving performance. We use a generative reward model formulation, allowing the LLM to predict mid-generation the probability that restarting the generation will yield a better response. These predictions are obtained without an external reward model and can be used to decide whether or not to generate more samples, prune unpromising samples early on, or to pick the best sample. This capability is very inexpensive as it involves generating a single predefined token. Trained using a dataset constructed with real unfiltered LMSYS user prompts, Llama 3.1 8B's win rate against GPT-4 on AlpacaEval increases from 21% to 34% with 16 samples and math performance on GSM8K improves from 84% to 91%. By sampling only when the LLM determines that it is beneficial to do so and adaptively adjusting temperature annealing, we demonstrate that 74% of the improvement from using 16 samples can be achieved with only 1.2 samples on average. We further demonstrate that 50-75% of samples can be pruned early in generation with minimal degradation in performance. Overall, our methods enable more efficient and scalable compute utilization during inference for LLMs.

[Arxiv](https://arxiv.org/abs/2410.02725)