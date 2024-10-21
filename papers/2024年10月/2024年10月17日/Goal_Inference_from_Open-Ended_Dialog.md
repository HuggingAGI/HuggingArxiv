# 从开放对话中洞察目标

发布时间：2024年10月17日

`Agent` `机器人`

> Goal Inference from Open-Ended Dialog

# 摘要

> 我们开发了一种在线方法，让实体代理能够灵活学习并完成多样化的用户目标。与依赖大量数据的离线方法 RLHF 不同，我们的方法在在线环境中同样灵活高效。通过与大型语言模型 (LLM) 的对话，我们提取自然语言目标表示，并利用 LLM 扮演不同目标的人类角色，进行贝叶斯推理。这使得我们的方法能够处理复杂目标的不确定性。在杂货购物和家庭机器人辅助领域，我们通过文本接口和 AI2Thor 模拟验证了该方法，结果表明其性能优于缺乏目标表示或概率推理的基线方法。

> We present an online method for embodied agents to learn and accomplish diverse user goals. While offline methods like RLHF can represent various goals but require large datasets, our approach achieves similar flexibility with online efficiency. We extract natural language goal representations from conversations with Large Language Models (LLMs). We prompt an LLM to role play as a human with different goals and use the corresponding likelihoods to run Bayesian inference over potential goals. As a result, our method can represent uncertainty over complex goals based on unrestricted dialog. We evaluate our method in grocery shopping and home robot assistance domains using a text-based interface and AI2Thor simulation respectively. Results show our method outperforms ablation baselines that lack either explicit goal representation or probabilistic inference.

[Arxiv](https://arxiv.org/abs/2410.13957)