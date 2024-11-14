# NavAgent：用于无人机具身视觉和语言导航的多尺度城市街景融合

发布时间：2024年11月13日

`Agent` `具身智能` `无人机导航`

> NavAgent: Multi-scale Urban Street View Fusion For UAV Embodied Vision-and-Language Navigation

# 摘要

> 视觉和语言导航（VLN）作为具身智能中被广泛讨论的研究方向，旨在使具身智能体能够通过自然语言命令在复杂的视觉环境中导航。大多数现有的 VLN 方法侧重于室内地面机器人场景。然而，当应用于室外城市场景中的无人机 VLN 时，它面临两个重大挑战。首先，城市场景包含众多物体，这使得图像中细粒度的地标与这些地标的复杂文本描述相匹配具有挑战性。其次，整体环境信息涵盖多个模态维度，并且表示的多样性显著增加了编码过程的复杂性。为了应对这些挑战，我们提出了 NavAgent，这是第一个由大型视觉语言模型驱动的城市无人机具身导航模型。NavAgent 通过综合多尺度环境信息，包括拓扑图（全局）、全景图（中尺度）和细粒度地标（局部）来承担导航任务。具体来说，我们利用 GLIP 构建了一个能够识别和语言化细粒度地标的地标视觉识别器。随后，我们开发了动态增长的场景拓扑图，该图整合了环境信息，并使用图卷积网络对全局环境数据进行编码。此外，为了训练地标视觉识别器，我们开发了 NavAgent-Landmark2K，这是第一个针对真实城市街道场景的细粒度地标数据集。在 Touchdown 和 Map2seq 数据集上进行的实验中，NavAgent 优于强大的基线模型。代码和数据集将发布给社区，以促进室外 VLN 的探索和发展。

> Vision-and-Language Navigation (VLN), as a widely discussed research direction in embodied intelligence, aims to enable embodied agents to navigate in complicated visual environments through natural language commands. Most existing VLN methods focus on indoor ground robot scenarios. However, when applied to UAV VLN in outdoor urban scenes, it faces two significant challenges. First, urban scenes contain numerous objects, which makes it challenging to match fine-grained landmarks in images with complex textual descriptions of these landmarks. Second, overall environmental information encompasses multiple modal dimensions, and the diversity of representations significantly increases the complexity of the encoding process. To address these challenges, we propose NavAgent, the first urban UAV embodied navigation model driven by a large Vision-Language Model. NavAgent undertakes navigation tasks by synthesizing multi-scale environmental information, including topological maps (global), panoramas (medium), and fine-grained landmarks (local). Specifically, we utilize GLIP to build a visual recognizer for landmark capable of identifying and linguisticizing fine-grained landmarks. Subsequently, we develop dynamically growing scene topology map that integrate environmental information and employ Graph Convolutional Networks to encode global environmental data. In addition, to train the visual recognizer for landmark, we develop NavAgent-Landmark2K, the first fine-grained landmark dataset for real urban street scenes. In experiments conducted on the Touchdown and Map2seq datasets, NavAgent outperforms strong baseline models. The code and dataset will be released to the community to facilitate the exploration and development of outdoor VLN.

[Arxiv](https://arxiv.org/abs/2411.08579)