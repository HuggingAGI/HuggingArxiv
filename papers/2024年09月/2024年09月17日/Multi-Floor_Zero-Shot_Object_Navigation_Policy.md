# 多层零-shot 物体导航策略

发布时间：2024年09月17日

`Agent` `机器人` `人工智能`

> Multi-Floor Zero-Shot Object Navigation Policy

# 摘要

> 在多层环境中进行物体导航是机器人技术的一大挑战，需要精细的空间推理和灵活的探索策略。传统方法多聚焦于单层场景，忽略了多层结构的复杂性。为此，我们提出了多层导航策略（MFNP），并在零样本物体导航任务中应用。该策略包含三大核心：跨层探索、多模态大型语言模型辅助推理及高效层间过渡。实验表明，MFNP在HM3D和MP3D等多层场景数据集上，显著超越现有方法，成功率与探索效率均有提升。消融研究证实了各组件的有效性。实际测试中，Unitree四足机器人成功在未知环境中完成多层导航并定位目标。MFNP的引入，为复杂多层环境下的物体导航提供了新思路，也为未来基于视觉的现实多层导航研究奠定了基础。

> Object navigation in multi-floor environments presents a formidable challenge in robotics, requiring sophisticated spatial reasoning and adaptive exploration strategies. Traditional approaches have primarily focused on single-floor scenarios, overlooking the complexities introduced by multi-floor structures. To address these challenges, we first propose a Multi-floor Navigation Policy (MFNP) and implement it in Zero-Shot object navigation tasks. Our framework comprises three key components: (i) Multi-floor Navigation Policy, which enables an agent to explore across multiple floors; (ii) Multi-modal Large Language Models (MLLMs) for reasoning in the navigation process; and (iii) Inter-Floor Navigation, ensuring efficient floor transitions. We evaluate MFNP on the Habitat-Matterport 3D (HM3D) and Matterport 3D (MP3D) datasets, both include multi-floor scenes. Our experiment results demonstrate that MFNP significantly outperforms all the existing methods in Zero-Shot object navigation, achieving higher success rates and improved exploration efficiency. Ablation studies further highlight the effectiveness of each component in addressing the unique challenges of multi-floor navigation. Meanwhile, we conducted real-world experiments to evaluate the feasibility of our policy. Upon deployment of MFNP, the Unitree quadruped robot demonstrated successful multi-floor navigation and found the target object in a completely unseen environment. By introducing MFNP, we offer a new paradigm for tackling complex, multi-floor environments in object navigation tasks, opening avenues for future research in visual-based navigation in realistic, multi-floor settings.

[Arxiv](https://arxiv.org/abs/2409.10906)