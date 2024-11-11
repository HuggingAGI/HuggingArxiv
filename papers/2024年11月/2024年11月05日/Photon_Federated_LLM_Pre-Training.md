# 光子：联邦大型语言模型预训练

发布时间：2024年11月05日

`LLM应用` `计算机`

> Photon: Federated LLM Pre-Training

# 摘要

> 扩展大型语言模型（LLM）需要大量的数据和计算资源，由于分布式训练的高带宽要求，这些资源传统上被限制在数据中心。像联邦学习（FL）这样的低带宽方法，如果能有效地用于预训练，就可以实现跨弱连接的 GPU 对更大模型的协同训练。为了实现这一目标，我们引入了 Photon，这是第一个用于联邦端到端 LLM 训练的完整系统，利用跨仓库的 FL 进行全球规模的训练，同时将通信开销降至最低。使用 Photon，我们从头开始训练了第一个联邦式的仅解码器 LLM 家族。我们表明：（1）Photon 能够以联邦方式训练高达 70 亿参数的模型，同时达到比集中式预训练更好的困惑度；（2）Photon 模型的训练时间随着可用计算资源的增加而减少，实现了与集中式类似的计算时间权衡；（3）Photon 通过减少 64 倍至 512 倍的通信量，比基线分布式训练方法的挂钟时间快 35％。我们的提议对数据异质性具有鲁棒性，收敛速度是之前像 DiLoCo 这样的方法的两倍。这种令人惊讶的数据效率源于一种独特的方法，即结合小的客户端批量大小和极高的学习率，这得益于联邦平均对超参数的鲁棒性。因此，Photon 代表了第一个用于全球互联网范围 LLM 预训练的经济系统。

> Scaling large language models (LLMs) demands extensive data and computing resources, which are traditionally constrained to data centers by the high-bandwidth requirements of distributed training. Low-bandwidth methods like federated learning (FL) could enable collaborative training of larger models across weakly-connected GPUs if they can effectively be used for pre-training. To achieve this, we introduce Photon, the first complete system for federated end-to-end LLM training, leveraging cross-silo FL for global-scale training with minimal communication overheads. Using Photon, we train the first federated family of decoder-only LLMs from scratch. We show that: (1) Photon can train model sizes up to 7B in a federated fashion while reaching an even better perplexity than centralized pre-training; (2) Photon model training time decreases with available compute, achieving a similar compute-time trade-off to centralized; and (3) Photon outperforms the wall-time of baseline distributed training methods by 35% via communicating 64x-512xless. Our proposal is robust to data heterogeneity and converges twice as fast as previous methods like DiLoCo. This surprising data efficiency stems from a unique approach combining small client batch sizes with extremely high learning rates, enabled by federated averaging's robustness to hyperparameters. Photon thus represents the first economical system for global internet-wide LLM pre-training.

[Arxiv](https://arxiv.org/abs/2411.02908)