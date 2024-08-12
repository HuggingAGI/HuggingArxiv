# 实现解码时的可控性：通过对比提示实现无梯度多目标对齐

发布时间：2024年08月09日

`LLM理论` `人工智能` `软件工程`

> Unlocking Decoding-time Controllability: Gradient-Free Multi-Objective Alignment with Contrastive Prompts

# 摘要

> 多目标对齐任务旨在平衡大型语言模型的不同对齐目标，如有用性、无害性和诚实性，以满足用户的个性化需求。传统方法通过训练多个模型来应对不同偏好，导致模型数量随目标和偏好数量线性增长，且可扩展性差，需频繁重新训练。为此，我们提出MCA（多目标对比对齐），通过为每个目标设计专家和对抗提示，在解码时进行对比，从而有效平衡各目标。实验证明，MCA在生成不同对齐目标间的均衡帕累托前沿方面表现优异。

> The task of multi-objective alignment aims at balancing and controlling the different alignment objectives (e.g., helpfulness, harmlessness and honesty) of large language models to meet the personalized requirements of different users. However, previous methods tend to train multiple models to deal with various user preferences, with the number of trained models growing linearly with the number of alignment objectives and the number of different preferences. Meanwhile, existing methods are generally poor in extensibility and require significant re-training for each new alignment objective considered. Considering the limitation of previous approaches, we propose MCA (Multi-objective Contrastive Alignemnt), which constructs an expert prompt and an adversarial prompt for each objective to contrast at the decoding time and balances the objectives through combining the contrast. Our approach is verified to be superior to previous methods in obtaining a well-distributed Pareto front among different alignment objectives.

[Arxiv](https://arxiv.org/abs/2408.05094)