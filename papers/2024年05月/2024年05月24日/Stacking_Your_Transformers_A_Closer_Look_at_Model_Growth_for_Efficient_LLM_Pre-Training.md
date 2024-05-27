# 变压器堆叠术：探究模型增长策略，优化大型语言模型预训练效率

发布时间：2024年05月24日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）预训练中的模型增长方法，并针对现有方法的评估不全面、可扩展性未经检验以及缺乏实践指南这三大挑战进行了深入研究。论文通过系统评估和实验，提出了一种名为$G_{\text{stack}}$的增长操作，并验证了其在不同规模模型和大量数据预训练中的有效性。此外，论文还提供了实践指南，以增强该方法在LLM预训练中的实用性。这些内容更偏向于LLM的理论研究和方法论探讨，而非具体的应用实例或Agent、RAG相关的研究，因此归类为LLM理论。` `模型训练`

> Stacking Your Transformers: A Closer Look at Model Growth for Efficient LLM Pre-Training

# 摘要

> 大型语言模型（LLMs）的预训练因规模巨大而成本高昂。模型增长，即利用小模型加速大模型的训练，展现出巨大潜力。然而，这些增长方法在高效LLM预训练中的实际效果尚未明朗。本研究指出了三大挑战：（O1）评估不全面，（O2）可扩展性未经检验，（O3）缺乏实践指南。针对O1，我们将现有方法归纳为四个基本增长操作，并在标准化预训练环境中进行了系统评估。结果显示，深度堆叠操作$G_{\text{stack}}$显著加速了训练过程，降低了损失，并在八个NLP基准测试中超越了强基线。基于这些积极成果，我们深入研究了$G_{\text{stack}}$，以验证其可扩展性（O2），并展示了其在高达7B模型和750B令牌预训练中的优异表现。例如，与传统训练的7B模型相比，$G_{\text{stack}}$在194B令牌时达到相同损失，提速54.6%。我们还制定了关于$G_{\text{stack}}$增长时机和因子的实践指南（O3），使其在LLM预训练中更具实用性。此外，我们提供了详尽的讨论和消融研究。代码和模型已公开在https://llm-stacking.github.io/。

> LLMs are computationally expensive to pre-train due to their large scale. Model growth emerges as a promising approach by leveraging smaller models to accelerate the training of larger ones. However, the viability of these model growth methods in efficient LLM pre-training remains underexplored. This work identifies three critical $\underline{\textit{O}}$bstacles: ($\textit{O}$1) lack of comprehensive evaluation, ($\textit{O}$2) untested viability for scaling, and ($\textit{O}$3) lack of empirical guidelines. To tackle $\textit{O}$1, we summarize existing approaches into four atomic growth operators and systematically evaluate them in a standardized LLM pre-training setting. Our findings reveal that a depthwise stacking operator, called $G_{\text{stack}}$, exhibits remarkable acceleration in training, leading to decreased loss and improved overall performance on eight standard NLP benchmarks compared to strong baselines. Motivated by these promising results, we conduct extensive experiments to delve deeper into $G_{\text{stack}}$ to address $\textit{O}$2 and $\textit{O}$3. For $\textit{O}$2 (untested scalability), our study shows that $G_{\text{stack}}$ is scalable and consistently performs well, with experiments up to 7B LLMs after growth and pre-training LLMs with 750B tokens. For example, compared to a conventionally trained 7B model using 300B tokens, our $G_{\text{stack}}$ model converges to the same loss with 194B tokens, resulting in a 54.6\% speedup. We further address $\textit{O}$3 (lack of empirical guidelines) by formalizing guidelines to determine growth timing and growth factor for $G_{\text{stack}}$, making it practical in general LLM pre-training. We also provide in-depth discussions and comprehensive ablation studies of $G_{\text{stack}}$. Our code and pre-trained model are available at $\href{https://llm-stacking.github.io/}{https://llm-stacking.github.io/}$.

[Arxiv](https://arxiv.org/abs/2405.15319)