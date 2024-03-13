# [在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](https://arxiv.org/abs/2403.07379)

发布时间：2024年03月12日

`LLM理论`

> Hallmarks of Optimization Trajectories in Neural Networks and LLMs: The Lengths, Bends, and Dead Ends

> 我们创新性地通过剖析神经网络内部优化轨迹中蕴含的丰富参数结构，深入解读其工作机制。为此，我们定义了一系列定性与定量相结合的优化轨迹复杂度概念，揭示了动量、权重衰减、批次大小等不同优化策略之间的微妙互动关系。借助这些新概念，我们成功揭示了深度神经网络优化过程的本质特征——何时能稳健推进，何时会陷入困境。从轨迹角度出发，我们还发现了动量和权重衰减间相互促进探索方向的作用机制，以及其他一些有助于定向正则化的特性。为了验证我们方法的有效性，我们在大规模视觉和语言任务上进行实验，涵盖了最多拥有120亿参数的大规模语言模型（LLMs）。

> We propose a fresh take on understanding the mechanisms of neural networks by analyzing the rich structure of parameters contained within their optimization trajectories. Towards this end, we introduce some natural notions of the complexity of optimization trajectories, both qualitative and quantitative, which reveal the inherent nuance and interplay involved between various optimization choices, such as momentum, weight decay, and batch size. We use them to provide key hallmarks about the nature of optimization in deep neural networks: when it goes right, and when it finds itself in a dead end. Further, thanks to our trajectory perspective, we uncover an intertwined behaviour of momentum and weight decay that promotes directional exploration, as well as a directional regularization behaviour of some others. We perform experiments over large-scale vision and language settings, including large language models (LLMs) with up to 12 billion parameters, to demonstrate the value of our approach.

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/x1.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/x2.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/rn50_regs_cosine_other-three.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/x3.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/x4.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cosine_pythia_ckpts.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/x5.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Mom,WD.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Weight_Decay.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_SAM.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Momentum.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cos_sims_rel_init.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Batch_Size.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/cosine_pythia_ckpts_init-subtracted.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Parameter_Norms_theta_t_2_vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/theta__t+k__-_theta_t_2_for_k=1_vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Distance_from_Initialization_theta_t_-theta_0_2_vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t__vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+1_-theta_t,theta_t-theta_0__vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t+k_-theta_t,theta_t-theta__t-k____for_k=1__in__circ__vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/angle_theta__t_-theta_0,theta_T-theta_0__vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Initialization_angle_theta_t-theta_0,theta_1-theta_0__vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Apex_Angle_at_Origin_angle_theta_t,theta_0__vs_Epochs__t__across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__vs_Eigenvalue_Index_across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_K__0_vs_Eigenvalue_Index_across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__vs_Eigenvalue_Index_across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/Eigenvalues_mathbf_C__0_vs_Eigenvalue_Index_across_Scale.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/query_key_value.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/query_key_value.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/dense.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/dense.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/dense_4h_to_h.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/dense_4h_to_h.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/dense_h_to_4h.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/dense_h_to_4h.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/embed_in.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/embed_out.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/final_layer_norm.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/final_layer_norm.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/input_layernorm.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/input_layernorm.weight.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/post_attention_layernorm.bias.png)

![在神经网络及大型语言模型内部，优化路径具有显著特征，表现为路径长度、曲率变化以及无解的死胡同。本研究聚焦于揭示这些路径特性在深度学习训练过程中的规律及其对LLMs的影响。](../../../paper_images/2403.07379/post_attention_layernorm.weight.png)