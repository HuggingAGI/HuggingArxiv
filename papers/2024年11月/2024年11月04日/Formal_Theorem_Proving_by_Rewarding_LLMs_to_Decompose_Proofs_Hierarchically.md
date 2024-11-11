# 通过奖励大型语言模型（LLMs）分层分解证明来进行形式定理证明

发布时间：2024年11月04日

`LLM应用` `定理证明`

> Formal Theorem Proving by Rewarding LLMs to Decompose Proofs Hierarchically

# 摘要

> 数学定理证明是大型语言模型深度和抽象推理能力的重要试验台。本文重点在于提高大型语言模型用允许自动证明验证/评估的形式语言编写证明的能力。之前的大多数结果都为定理证明器提供了人工编写的引理，这可以说是一种过度简化的设置，不能充分测试证明器的规划和分解能力。相反，我们在更自然的设置中工作，在测试时，与定理直接相关的引理不会提供给定理证明器。我们设计了一种基于强化学习的训练算法，鼓励模型将定理分解为引理，证明引理，然后使用引理证明定理。我们的奖励机制受到数学家自我训练方式的启发：即使当前模型难以证明一个定理，但对于在此过程中提出并证明的任何正确且新颖的引理，仍会给模型一个积极的奖励。在训练期间，我们的模型提出并证明了不在训练数据集中的引理。事实上，当我们在从形式证明档案（AFP）提取的数据集上进行训练时，这些新提出的正确引理占训练重放缓冲区的 37.7％。通过我们的强化学习算法训练的模型优于通过监督微调训练的模型，在 AFP 测试集上的通过率从 40.8％提高到 45.5％，在分布外测试集上从 36.5％提高到 39.5％。

> Mathematical theorem proving is an important testbed for large language models' deep and abstract reasoning capability. This paper focuses on improving LLMs' ability to write proofs in formal languages that permit automated proof verification/evaluation. Most previous results provide human-written lemmas to the theorem prover, which is an arguably oversimplified setting that does not sufficiently test the provers' planning and decomposition capabilities. Instead, we work in a more natural setup where the lemmas that are directly relevant to the theorem are not given to the theorem prover at test time. We design an RL-based training algorithm that encourages the model to decompose a theorem into lemmas, prove the lemmas, and then prove the theorem by using the lemmas. Our reward mechanism is inspired by how mathematicians train themselves: even if a theorem is too challenging to be proved by the current model, a positive reward is still given to the model for any correct and novel lemmas that are proposed and proved in this process. During training, our model proposes and proves lemmas that are not in the training dataset. In fact, these newly-proposed correct lemmas consist of 37.7% of the training replay buffer when we train on the dataset extracted from Archive of Formal Proofs (AFP). The model trained by our RL algorithm outperforms that trained by supervised finetuning, improving the pass rate from 40.8% to 45.5% on AFP test set, and from 36.5% to 39.5% on an out-of-distribution test set.

[Arxiv](https://arxiv.org/abs/2411.01829)