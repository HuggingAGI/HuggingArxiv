# 潜藏权重扩散：策略由轨迹孕育而生

发布时间：2024年10月17日

`Agent` `机器人` `人工智能`

> Latent Weight Diffusion: Generating Policies from Trajectories

# 摘要

> 随着开源机器人数据的增多，模仿学习在机器人操作和移动中崭露头角。当前，大型通用策略通过扩散模型预测控制或轨迹，具备学习多模态动作分布的优势。然而，通用性带来模型规模大和推理速度慢的代价。此外，扩散策略在性能和动作范围间存在权衡，较少扩散查询导致更大轨迹误差。因此，高频推理在机器人计算约束下常见。为应对这些挑战，我们提出潜在权重扩散（LWD），通过扩散学习机器人任务策略分布而非轨迹。LWD将演示轨迹编码至潜在空间，再由超网络解码为策略，并在潜在空间内用扩散去噪模型学习分布。实验证明，LWD能重建原始策略行为，推理时策略网络显著缩小，扩散模型查询减少。在Metaworld MT10基准测试中，LWD成功率高于普通多任务策略，推理模型缩小多达~18倍。此外，LWD生成闭环策略，长动作范围设置中表现优于扩散策略，回滚时扩散查询减少。

> With the increasing availability of open-source robotic data, imitation learning has emerged as a viable approach for both robot manipulation and locomotion. Currently, large generalized policies are trained to predict controls or trajectories using diffusion models, which have the desirable property of learning multimodal action distributions. However, generalizability comes with a cost - namely, larger model size and slower inference. Further, there is a known trade-off between performance and action horizon for Diffusion Policy (i.e., diffusing trajectories): fewer diffusion queries accumulate greater trajectory tracking errors. Thus, it is common practice to run these models at high inference frequency, subject to robot computational constraints.
  To address these limitations, we propose Latent Weight Diffusion (LWD), a method that uses diffusion to learn a distribution over policies for robotic tasks, rather than over trajectories. Our approach encodes demonstration trajectories into a latent space and then decodes them into policies using a hypernetwork. We employ a diffusion denoising model within this latent space to learn its distribution. We demonstrate that LWD can reconstruct the behaviors of the original policies that generated the trajectory dataset. LWD offers the benefits of considerably smaller policy networks during inference and requires fewer diffusion model queries. When tested on the Metaworld MT10 benchmark, LWD achieves a higher success rate compared to a vanilla multi-task policy, while using models up to ~18x smaller during inference. Additionally, since LWD generates closed-loop policies, we show that it outperforms Diffusion Policy in long action horizon settings, with reduced diffusion queries during rollout.

[Arxiv](https://arxiv.org/abs/2410.14040)