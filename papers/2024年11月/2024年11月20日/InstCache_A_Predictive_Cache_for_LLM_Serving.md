# InstCache：LLM 服务的预测缓存

发布时间：2024年11月20日

`LLM应用` `计算机` `语言模型`

> InstCache: A Predictive Cache for LLM Serving

# 摘要

> 大型语言模型正在全方位地革新人类生活。然而，这种前所未有的强大能力是以极高的计算强度为代价的，导致了长延迟和大的能源消耗。键值缓存和语义缓存已被当作上述问题的解决办法提出，但由于每个标记或指令嵌入所需的内存成本颇高，二者在可扩展性方面都很受限。鉴于大多数指令短小、重复且能被大型语言模型预测这一观察结果，我们提议用与指令对齐的大型语言模型来预测用户指令，并将其存储在预测缓存（即 InstCache）中。我们引入了基于指令负对数似然的指令预填充算法，依据命中率来确定缓存大小。所提出的 InstCache 被高效地实现为一个哈希表，部署时查找延迟极低。实验结果显示，InstCache 在 LMSys 数据集上的命中率能高达 51.34%，相当于速度提升 2 倍，而内存成本仅为 4.5GB。

> Large language models are revolutionizing every aspect of human life. However, the unprecedented power comes at the cost of significant computing intensity, suggesting long latency and large energy footprint. Key-Value Cache and Semantic Cache have been proposed as a solution to the above problem, but both suffer from limited scalability due to significant memory cost for each token or instruction embeddings. Motivated by the observations that most instructions are short, repetitive and predictable by LLMs, we propose to predict user-instructions by an instruction-aligned LLM and store them in a predictive cache, so-called InstCache. We introduce an instruction pre-population algorithm based on the negative log likelihood of instructions, determining the cache size with regard to the hit rate. The proposed InstCache is efficiently implemented as a hash table with minimal lookup latency for deployment. Experimental results show that InstCache can achieve up to 51.34% hit rate on LMSys dataset, which corresponds to a 2x speedup, at a memory cost of only 4.5GB.

[Arxiv](https://arxiv.org/abs/2411.13820)