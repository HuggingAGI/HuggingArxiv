# 驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成

发布时间：2024年06月06日

`Agent

理由：这篇论文介绍了一个名为Text-to-Drive（T2D）的系统，该系统利用大型语言模型（LLMs）来生成多样化的驾驶行为描述，并在模拟中实现这些行为。这个系统可以被视为一个Agent，因为它能够根据输入的语言描述生成相应的驾驶行为，并在模拟环境中执行这些行为。此外，T2D的核心是构建一个状态图，将低级状态映射到高级抽象，这表明系统具有一定的自主决策能力，符合Agent的定义。虽然系统中使用了LLM，但主要应用是作为生成和执行驾驶行为的工具，而不是专注于LLM的理论研究或应用。因此，这篇论文更适合归类为Agent。` `自动驾驶` `模拟系统`

> Text-to-Drive: Diverse Driving Behavior Synthesis via Large Language Models

# 摘要

> 模拟多样化场景对于训练和评估自动驾驶等安全关键系统至关重要。然而，模拟其他车辆轨迹以实现有意义的交互成本高昂。采用语言描述生成驾驶行为是一种创新策略，为操作员提供了一种直观且可扩展的方法来模拟各种驾驶场景。但缺乏大规模注释的语言-轨迹数据限制了这一方法的发展。为此，我们开发了Text-to-Drive（T2D），利用大型语言模型（LLMs）生成多样化的驾驶行为。T2D采用两阶段知识驱动方法：首先，利用LLMs生成场景的多样化驾驶行为描述；其次，通过LLM的推理能力在模拟中实现这些行为。T2D的核心是构建一个状态图，将低级状态映射到高级抽象，无需人工监督即可支持下游任务，如观察总结、策略评估和奖励塑造。我们的研究表明，T2D生成的轨迹比现有方法更多样化，并提供了一个自然语言界面，便于交互式地融入人类偏好。更多示例请访问我们的网站：https://text-to-drive.github.io/

> Generating varied scenarios through simulation is crucial for training and evaluating safety-critical systems, such as autonomous vehicles. Yet, the task of modeling the trajectories of other vehicles to simulate diverse and meaningful close interactions remains prohibitively costly. Adopting language descriptions to generate driving behaviors emerges as a promising strategy, offering a scalable and intuitive method for human operators to simulate a wide range of driving interactions. However, the scarcity of large-scale annotated language-trajectory data makes this approach challenging.
  To address this gap, we propose Text-to-Drive (T2D) to synthesize diverse driving behaviors via Large Language Models (LLMs). We introduce a knowledge-driven approach that operates in two stages. In the first stage, we employ the embedded knowledge of LLMs to generate diverse language descriptions of driving behaviors for a scene. Then, we leverage LLM's reasoning capabilities to synthesize these behaviors in simulation. At its core, T2D employs an LLM to construct a state chart that maps low-level states to high-level abstractions. This strategy aids in downstream tasks such as summarizing low-level observations, assessing policy alignment with behavior description, and shaping the auxiliary reward, all without needing human supervision. With our knowledge-driven approach, we demonstrate that T2D generates more diverse trajectories compared to other baselines and offers a natural language interface that allows for interactive incorporation of human preference. Please check our website for more examples: https://text-to-drive.github.io/

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/teaser.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/overview.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/iterator.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/state_summary.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/intersection_trajectories.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/highway_trajectories.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/merge_trajectories.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/code_nl_similarity_matrix.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/code_policy_agreement_matrix.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/kendall_tau_code_diversity.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/jsd_comparison_hist_2.png)

![驾驭文字，驱动多样：大型语言模型助力驾驶行为多样化合成](../../../paper_images/2406.04300/robust_aux.png)

[Arxiv](https://arxiv.org/abs/2406.04300)