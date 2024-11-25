# DyCoke：针对快速视频大型语言模型的动态令牌压缩技术

发布时间：2024年11月22日

`LLM应用` `语言模型`

> DyCoke: Dynamic Compression of Tokens for Fast Video Large Language Models

# 摘要

> 视频大型语言模型（VLLMs）近来在处理复杂视频内容上进步显著，然而因其视频输入生成的数千个视觉标记带来的高计算成本，其推理效率仍受制约。经验表明，与单个图像输入不同，VLLMs 往往在不同解码迭代中关注不同帧的视觉标记，这导致一次性修剪策略易误删重要标记。鉴于此，我们推出了 DyCoke，这是一种无需训练的标记压缩方法，用于优化标记表征并加快 VLLMs 速度。DyCoke 融入了一个即插即用的时间压缩模块，通过合并跨帧的冗余标记来减少时间冗余，并采用动态 KV 缓存缩减来有选择地修剪空间冗余标记。它能在每个解码步骤动态保留关键标记，从而保证高质量推理。大量实验结果显示，DyCoke 能超越之前的最先进同类方法，在无需训练的情况下，实现 1.5 倍的推理加速，相对基线 VLLM 减少 1.4 倍内存，同时还能提升性能。

> Video large language models (VLLMs) have significantly advanced recently in processing complex video content, yet their inference efficiency remains constrained because of the high computational cost stemming from the thousands of visual tokens generated from the video inputs. We empirically observe that, unlike single image inputs, VLLMs typically attend visual tokens from different frames at different decoding iterations, making a one-shot pruning strategy prone to removing important tokens by mistake. Motivated by this, we present DyCoke, a training-free token compression method to optimize token representation and accelerate VLLMs. DyCoke incorporates a plug-and-play temporal compression module to minimize temporal redundancy by merging redundant tokens across frames, and applies dynamic KV cache reduction to prune spatially redundant tokens selectively. It ensures high-quality inference by dynamically retaining the critical tokens at each decoding step. Extensive experimental results demonstrate that DyCoke can outperform the prior SoTA counterparts, achieving 1.5X inference speedup, 1.4X memory reduction against the baseline VLLM, while still improving the performance, with no training.

[Arxiv](https://arxiv.org/abs/2411.15024)