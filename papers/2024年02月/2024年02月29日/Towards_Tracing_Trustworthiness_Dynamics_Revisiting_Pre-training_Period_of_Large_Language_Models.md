# [为探究大型语言模型（LLM）可信度动态变化，我们再次聚焦其预训练阶段，旨在深入理解这一关键阶段对其后续表现和可信度的影响。]

发布时间：2024年02月29日

`LLM理论`

> Towards Tracing Trustworthiness Dynamics: Revisiting Pre-training Period of Large Language Models

> 对于LLMs来说，确保其可信性是至关重要的。当前多数研究聚焦于完全预训练阶段的LLMs，以求深化理解并改进其可信性。在这篇论文中，我们独辟蹊径，首度探讨了LLMs在预训练阶段潜在的可信性表现，尤其关注五个核心维度：可靠性、隐私保护、无害性、公正性和稳健性。实验初期，我们采用线性探测方法对LLMs进行分析，发现高探测精度意味着LLMs在预训练早期就能识别出各可信维度中的概念差异。因此，为进一步挖掘预训练过程中的潜在可能性，我们从LLM的预训练检查点提取导向向量来提升其可信性。此外，借鉴\citet{choi2023understanding}关于互信息估计受限于线性探测精度的观点，我们运用互信息探测手段，研究LLMs在预训练期间可信性动态变化规律。我们首次揭示了一种类似“拟合与压缩”双阶段的现象~\citep{shwartz2017opening}。此研究开创性地剖析了LLM预训练阶段的可信性建模问题，旨在揭示更多新见解，并激励该领域的后续进展。我们的代码将在GitHub上公开，网址为 \url{https://github.com/ChnQ/TracingLLM}。

> Ensuring the trustworthiness of large language models (LLMs) is crucial. Most studies concentrate on fully pre-trained LLMs to better understand and improve LLMs' trustworthiness. In this paper, to reveal the untapped potential of pre-training, we pioneer the exploration of LLMs' trustworthiness during this period, focusing on five key dimensions: reliability, privacy, toxicity, fairness, and robustness. To begin with, we apply linear probing to LLMs. The high probing accuracy suggests that \textit{LLMs in early pre-training can already distinguish concepts in each trustworthiness dimension}. Therefore, to further uncover the hidden possibilities of pre-training, we extract steering vectors from a LLM's pre-training checkpoints to enhance the LLM's trustworthiness. Finally, inspired by~\citet{choi2023understanding} that mutual information estimation is bounded by linear probing accuracy, we also probe LLMs with mutual information to investigate the dynamics of trustworthiness during pre-training. We are the first to observe a similar two-phase phenomenon: fitting and compression~\citep{shwartz2017opening}. This research provides an initial exploration of trustworthiness modeling during LLM pre-training, seeking to unveil new insights and spur further developments in the field. We will make our code publicly accessible at \url{https://github.com/ChnQ/TracingLLM}.

[Arxiv](https://arxiv.org/abs/2402.19465)