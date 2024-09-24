# 将 Transformer 的扩散策略扩展至 10 亿参数，应用于机器人操控

发布时间：2024年09月22日

`Agent` `机器人` `人工智能`

> Scaling Diffusion Policy in Transformer to 1 Billion Parameters for Robotic Manipulation

# 摘要

> Diffusion Policy 是一种强大的端到端视觉运动机器人控制学习工具。然而，我们发现其在 transformer 架构中难以有效扩展，即使增加少量层也会影响训练效果。为此，我们提出了 Scalable Diffusion Transformer Policy，通过引入两个模块改进训练动态，使网络更好地处理多模态动作分布。我们解决了大梯度问题，并利用非因果注意力减少累积误差。实验证明，我们的方法成功将模型从 1000 万扩展到 10 亿参数，显著提升了性能和泛化能力。在 MetaWorld 的 50 个任务中，我们的模型平均提升了 21.6\% 的性能；在真实世界机器人任务中，单臂任务提升 36.25\%，双臂任务提升 75\%。我们的工作为视觉运动学习的模型扩展提供了新方向。项目详情请访问 scaling-diffusion-policy.github.io。

> Diffusion Policy is a powerful technique tool for learning end-to-end visuomotor robot control. It is expected that Diffusion Policy possesses scalability, a key attribute for deep neural networks, typically suggesting that increasing model size would lead to enhanced performance. However, our observations indicate that Diffusion Policy in transformer architecture (\DP) struggles to scale effectively; even minor additions of layers can deteriorate training outcomes. To address this issue, we introduce Scalable Diffusion Transformer Policy for visuomotor learning. Our proposed method, namely \textbf{\methodname}, introduces two modules that improve the training dynamic of Diffusion Policy and allow the network to better handle multimodal action distribution. First, we identify that \DP~suffers from large gradient issues, making the optimization of Diffusion Policy unstable. To resolve this issue, we factorize the feature embedding of observation into multiple affine layers, and integrate it into the transformer blocks. Additionally, our utilize non-causal attention which allows the policy network to \enquote{see} future actions during prediction, helping to reduce compounding errors. We demonstrate that our proposed method successfully scales the Diffusion Policy from 10 million to 1 billion parameters. This new model, named \methodname, can effectively scale up the model size with improved performance and generalization. We benchmark \methodname~across 50 different tasks from MetaWorld and find that our largest \methodname~outperforms \DP~with an average improvement of 21.6\%. Across 7 real-world robot tasks, our ScaleDP demonstrates an average improvement of 36.25\% over DP-T on four single-arm tasks and 75\% on three bimanual tasks. We believe our work paves the way for scaling up models for visuomotor learning. The project page is available at scaling-diffusion-policy.github.io.

[Arxiv](https://arxiv.org/abs/2409.14411)