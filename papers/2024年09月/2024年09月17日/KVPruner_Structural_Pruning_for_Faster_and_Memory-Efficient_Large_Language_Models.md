# KVPruner：为大型语言模型带来更快处理速度和更高内存效率的结构化剪枝技术

发布时间：2024年09月17日

`LLM理论` `人工智能` `计算机硬件`

> KVPruner: Structural Pruning for Faster and Memory-Efficient Large Language Models

# 摘要

> 大型语言模型推理过程中的 KV 缓存瓶颈是一个重大挑战。深度剪枝虽能加速推理，但恢复训练耗时长达两周；宽度剪枝虽保留性能，但提速有限。为此，我们推出 KVPruner，通过全局困惑度分析和多策略剪枝，既提升效率又保持性能。KVPruner 使内存使用减半，吞吐量提升超 35%，且仅需两小时 LoRA 微调即可恢复性能。

> The bottleneck associated with the key-value(KV) cache presents a significant challenge during the inference processes of large language models. While depth pruning accelerates inference, it requires extensive recovery training, which can take up to two weeks. On the other hand, width pruning retains much of the performance but offers slight speed gains. To tackle these challenges, we propose KVPruner to improve model efficiency while maintaining performance. Our method uses global perplexity-based analysis to determine the importance ratio for each block and provides multiple strategies to prune non-essential KV channels within blocks. Compared to the original model, KVPruner reduces runtime memory usage by 50% and boosts throughput by over 35%. Additionally, our method requires only two hours of LoRA fine-tuning on small datasets to recover most of the performance.

[Arxiv](https://arxiv.org/abs/2409.11057)