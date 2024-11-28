# R-MTLLMF：无线边缘处的弹性多任务大型语言模型融合

发布时间：2024年11月27日

`LLM应用` `无线通信` `语言模型`

> R-MTLLMF: Resilient Multi-Task Large Language Model Fusion at the Wireless Edge

# 摘要

> 多任务大型语言模型（MTLLMs）在无线边缘的众多应用中至关重要，此处用户需要专门模型来高效处理多项任务。然而，MTLLMs 的训练复杂又费力，尤其在任务多变时。近来，通过任务向量实现模型融合的理念已成为组合微调参数以生成 MTLLM 的有效途径。本文在最坏情况的对抗性攻击假设下，研究了让边缘用户通过任务向量协同构建此类 MTTLMs 的问题。为此，先探究了对抗性噪声对多任务模型融合的影响，得出了所谓的权重解缠误差与均方误差（MSE）的关系。通过假设检验，直接表明 MSE 会增加任务向量间的干扰，致使模型融合失效。接着，提出了一种新颖的弹性 MTLLM 融合（R-MTLLMF）方法，其借助对 LLM 架构和微调过程的洞察，通过重新校准 MTLLM 来保障对抗性噪声下的任务向量聚合。随后，针对最坏情况和理想传输场景对所提的 R-MTLLMF 进行对比，以研究无线信道的影响。通过视觉 LLM 开展的大量模型融合实验证明了 R-MTLLMF 的有效性，在理想噪声场景下于八个不同任务中达到接近基线的性能，在最坏情况下显著优于未受保护的模型融合。结果进一步表明，从无线和 LLM 的视角出发，为实现整体的弹性，需要额外的物理层保护。

> Multi-task large language models (MTLLMs) are important for many applications at the wireless edge, where users demand specialized models to handle multiple tasks efficiently. However, training MTLLMs is complex and exhaustive, particularly when tasks are subject to change. Recently, the concept of model fusion via task vectors has emerged as an efficient approach for combining fine-tuning parameters to produce an MTLLM. In this paper, the problem of enabling edge users to collaboratively craft such MTTLMs via tasks vectors is studied, under the assumption of worst-case adversarial attacks. To this end, first the influence of adversarial noise to multi-task model fusion is investigated and a relationship between the so-called weight disentanglement error and the mean squared error (MSE) is derived. Using hypothesis testing, it is directly shown that the MSE increases interference between task vectors, thereby rendering model fusion ineffective. Then, a novel resilient MTLLM fusion (R-MTLLMF) is proposed, which leverages insights about the LLM architecture and fine-tuning process to safeguard task vector aggregation under adversarial noise by realigning the MTLLM. The proposed R-MTLLMF is then compared for both worst-case and ideal transmission scenarios to study the impact of the wireless channel. Extensive model fusion experiments with vision LLMs demonstrate R-MTLLMF's effectiveness, achieving close-to-baseline performance across eight different tasks in ideal noise scenarios and significantly outperforming unprotected model fusion in worst-case scenarios. The results further advocate for additional physical layer protection for a holistic approach to resilience, from both a wireless and LLM perspective.

[Arxiv](https://arxiv.org/abs/2411.18220)