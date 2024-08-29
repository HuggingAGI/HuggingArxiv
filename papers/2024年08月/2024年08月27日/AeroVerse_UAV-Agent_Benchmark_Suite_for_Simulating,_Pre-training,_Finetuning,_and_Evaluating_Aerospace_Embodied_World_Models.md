# AeroVerse：一款专为模拟、预训练、微调及评估航空航天实体世界模型而设计的无人机-代理基准套件

发布时间：2024年08月27日

`Agent` `航空航天` `人工智能`

> AeroVerse: UAV-Agent Benchmark Suite for Simulating, Pre-training, Finetuning, and Evaluating Aerospace Embodied World Models

# 摘要

> 航空航天体现智能旨在赋予无人机等平台自主感知、认知和行动，以及与人类和环境的自我中心交互。为此，我们构建了首个大规模真实世界图像-文本预训练数据集AerialAgent-Ego10k，并创建了虚拟图像-文本-姿态对齐数据集CyberAgent Ego500k，以促进航空航天体现世界模型的预训练。我们首次明确定义了5个下游任务，并构建了相应的指令数据集，用于微调航空航天体现世界模型。同时，我们开发了基于GPT-4的下游任务评估指标SkyAgentEval，以全面、灵活和客观地评估结果。此外，我们将多个视觉语言模型、数据集和模拟器集成到基准套件AeroVerse中，该套件将被发布到社区，以促进航空航天体现智能的探索和发展。

> Aerospace embodied intelligence aims to empower unmanned aerial vehicles (UAVs) and other aerospace platforms to achieve autonomous perception, cognition, and action, as well as egocentric active interaction with humans and the environment. The aerospace embodied world model serves as an effective means to realize the autonomous intelligence of UAVs and represents a necessary pathway toward aerospace embodied intelligence. However, existing embodied world models primarily focus on ground-level intelligent agents in indoor scenarios, while research on UAV intelligent agents remains unexplored. To address this gap, we construct the first large-scale real-world image-text pre-training dataset, AerialAgent-Ego10k, featuring urban drones from a first-person perspective. We also create a virtual image-text-pose alignment dataset, CyberAgent Ego500k, to facilitate the pre-training of the aerospace embodied world model. For the first time, we clearly define 5 downstream tasks, i.e., aerospace embodied scene awareness, spatial reasoning, navigational exploration, task planning, and motion decision, and construct corresponding instruction datasets, i.e., SkyAgent-Scene3k, SkyAgent-Reason3k, SkyAgent-Nav3k and SkyAgent-Plan3k, and SkyAgent-Act3k, for fine-tuning the aerospace embodiment world model. Simultaneously, we develop SkyAgentEval, the downstream task evaluation metrics based on GPT-4, to comprehensively, flexibly, and objectively assess the results, revealing the potential and limitations of 2D/3D visual language models in UAV-agent tasks. Furthermore, we integrate over 10 2D/3D visual-language models, 2 pre-training datasets, 5 finetuning datasets, more than 10 evaluation metrics, and a simulator into the benchmark suite, i.e., AeroVerse, which will be released to the community to promote exploration and development of aerospace embodied intelligence.

[Arxiv](https://arxiv.org/abs/2408.15511)