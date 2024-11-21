# OCEAN：针对大型语言模型的离线思维链评估与对齐

发布时间：2024年10月31日

`LLM应用` `知识图谱` `离线评估`

> OCEAN: Offline Chain-of-thought Evaluation and Alignment in Large Language Models

# 摘要

> 离线评估 LLMs 对于理解其能力极为关键，不过现有研究中当下的方法探索尚不充分。在此次工作中，我们聚焦于思维链能力的离线评估，并展示了如何依据所提评估方法来优化 LLMs。为实现具备丰富知识和推理路径的离线反馈，我们运用知识图谱（如 Wikidata5m）给生成的思维链予以反馈。鉴于 LLM 推理与 KG 结构存在异质性，KG 对 LLM 行为的直接交互和反馈颇具难度，因为这需要在 KG 中对 LLM 生成的思维链进行精准的实体链接和基础定位。为应对上述挑战，我们提出了离线思维链评估框架 OCEAN，将 LLMs 中的思维链推理建模为 MDP，并评估策略与 KG 偏好建模的契合度。为克服推理的异质性和基础定位问题，我们借助策略内 KG 探索和 RL 为 LLM 生成的思维链推理路径生成令牌级的似然分布，模拟 KG 推理偏好。接着，我们把知识图谱对生成推理路径的有效性和一致性的反馈纳入逆倾向得分，提出 KG-IPS 估计器。理论上，我们证明了所提 KG-IPS 估计器的无偏性，并给出其方差下限。凭借离线策略评估的值函数，我们能够直接进行离线策略优化，进一步增强思维链的一致性。我们的实证研究表明，OCEAN 能够高效优化生成具有更高估计值的思维链推理路径，且不会影响 LLMs 在下游任务中的一般能力及其内部知识。

> Offline evaluation of LLMs is crucial in understanding their capacities, though current methods remain underexplored in existing research. In this work, we focus on the offline evaluation of the chain-of-thought capabilities and show how to optimize LLMs based on the proposed evaluation method. To enable offline feedback with rich knowledge and reasoning paths, we use knowledge graphs (e.g., Wikidata5m) to provide feedback on the generated chain of thoughts. Due to the heterogeneity between LLM reasoning and KG structures, direct interaction and feedback from KGs on LLM behavior are challenging, as they require accurate entity linking and grounding of LLM-generated chains of thought in the KG. To address the above challenge, we propose an offline chain-of-thought evaluation framework, OCEAN, which models chain-of-thought reasoning in LLMs as an MDP and evaluate the policy's alignment with KG preference modeling. To overcome the reasoning heterogeneity and grounding problems, we leverage on-policy KG exploration and RL to model a KG policy that generates token-level likelihood distributions for LLM-generated chain-of-thought reasoning paths, simulating KG reasoning preference. Then we incorporate the knowledge-graph feedback on the validity and alignment of the generated reasoning paths into inverse propensity scores and propose KG-IPS estimator. Theoretically, we prove the unbiasedness of the proposed KG-IPS estimator and provide a lower bound on its variance. With the off-policy evaluated value function, we can directly enable off-policy optimization to further enhance chain-of-thought alignment. Our empirical study shows that OCEAN can be efficiently optimized for generating chain-of-thought reasoning paths with higher estimated values without affecting LLMs' general abilities in downstream tasks or their internal knowledge.

[Arxiv](https://arxiv.org/abs/2410.23703)