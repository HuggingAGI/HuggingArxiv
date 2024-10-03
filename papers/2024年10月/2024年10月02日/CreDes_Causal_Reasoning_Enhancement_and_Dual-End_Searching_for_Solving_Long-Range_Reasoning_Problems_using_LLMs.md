# CreDes：通过因果推理增强和双端搜索，解决 LLM 中的长距离推理难题

发布时间：2024年10月02日

`LLM理论` `人工智能`

> CreDes: Causal Reasoning Enhancement and Dual-End Searching for Solving Long-Range Reasoning Problems using LLMs

# 摘要

> 大型语言模型 (LLM) 在处理长程推理的组合优化问题时，因因果幻觉和大搜索空间而受限。为解决因果幻觉问题，本文提出因果关系增强 (CRE) 机制，确保推理与状态转换的每一步都因果正确。针对长因果范围和大搜索空间的挑战，我们设计了双端搜索 (DES) 方法，从初始和目标状态同时搜索解决方案。结合 CRE 和 DES (CreDes)，我们的模型实现了高效的多步推理，避免了传统单步推理的低效。实验证明，CreDes 在长程推理任务中，无论在准确性还是时间效率上，均显著超越现有最先进 (SOTA) 解决方案。

> Large language models (LLMs) have demonstrated limitations in handling combinatorial optimization problems involving long-range reasoning, partially due to causal hallucinations and huge search space. As for causal hallucinations, i.e., the inconsistency between reasoning and corresponding state transition, this paper introduces the Causal Relationship Enhancement (CRE) mechanism combining cause-effect interventions and the Individual Treatment Effect (ITE) to guarantee the solid causal rightness between each step of reasoning and state transition. As for the long causal range and huge search space limiting the performances of existing models featuring single-direction search, a Dual-End Searching (DES) approach is proposed to seek solutions by simultaneously starting from both the initial and goal states on the causal probability tree. By integrating CRE and DES (CreDes), our model has realized simultaneous multi-step reasoning, circumventing the inefficiencies from cascading multiple one-step reasoning like the Chain-of-Thought (CoT). Experiments demonstrate that CreDes significantly outperforms existing State-Of-The-Art (SOTA) solutions in long-range reasoning tasks in terms of both accuracy and time efficiency.

[Arxiv](https://arxiv.org/abs/2410.01696)