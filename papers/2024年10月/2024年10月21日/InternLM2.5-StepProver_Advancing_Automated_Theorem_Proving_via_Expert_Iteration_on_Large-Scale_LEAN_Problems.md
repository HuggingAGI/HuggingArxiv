# InternLM2.5-StepProver：借助专家迭代，攻克大规模 LEAN 问题，推动自动定理证明技术迈向新高度

发布时间：2024年10月21日

`LLM应用`

> InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems

# 摘要

> 大型语言模型（LLM）在数学定理证明中表现出色，尤其是在使用LEAN等正式语言时。主要采用专家迭代学习范式，依赖于包含大量数学问题的预定义数据集。LLM通过尝试证明数据集中的问题，并基于发现的证明进行自我训练，不断迭代提升能力。我们建议使用包含超过20,000 CPU天的LEAN问题数据集Lean-workbook进行专家迭代。研究发现，解决问题的数量与证明长度和CPU使用量呈对数线性关系。为此，我们训练了一个批评模型，用于挑选相对简单的问题供策略模型试验，并引导模型深入探索更复杂的证明。InternLM2.5-StepProver在MiniF2F、Lean-Workbook-Plus、ProofNet和Putnam等基准测试中达到了开源领域的顶尖水平。具体而言，它在MiniF2F-test中达到了65.9%的通过率，并在Lean-Workbook-Plus中证明了（或反驳了）17.0%的问题，相较于初始的9.5%，进步显著。我们已在https://github.com/InternLM/InternLM-Math和https://huggingface.co/datasets/internlm/Lean-Workbook上开源了相关模型和证明。

> Large Language Models (LLMs) have emerged as powerful tools in mathematical theorem proving, particularly when utilizing formal languages such as LEAN. The major learning paradigm is expert iteration, which necessitates a pre-defined dataset comprising numerous mathematical problems. In this process, LLMs attempt to prove problems within the dataset and iteratively refine their capabilities through self-training on the proofs they discover. We propose to use large scale LEAN problem datasets Lean-workbook for expert iteration with more than 20,000 CPU days. During expert iteration, we found log-linear trends between solved problem amount with proof length and CPU usage. We train a critic model to select relatively easy problems for policy models to make trials and guide the model to search for deeper proofs. InternLM2.5-StepProver achieves open-source state-of-the-art on MiniF2F, Lean-Workbook-Plus, ProofNet, and Putnam benchmarks. Specifically, it achieves a pass of 65.9% on the MiniF2F-test and proves (or disproves) 17.0% of problems in Lean-Workbook-Plus which shows a significant improvement compared to only 9.5% of problems proved when Lean-Workbook-Plus was released. We open-source our models and searched proofs at https://github.com/InternLM/InternLM-Math and https://huggingface.co/datasets/internlm/Lean-Workbook.

[Arxiv](https://arxiv.org/abs/2410.15700)