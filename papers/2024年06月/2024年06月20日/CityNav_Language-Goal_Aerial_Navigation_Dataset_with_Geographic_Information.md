# CityNav：融合地理信息的语言导向空中导航数据集

发布时间：2024年06月20日

`Agent

这篇论文主要讨论了视觉与语言导航（VLN）在真实世界空中导航中的应用，特别是通过引入CityNav数据集来推动这一领域的发展。论文中提到的自主代理模型和基线模型的测试，以及2D空间地图的引入，都是为了提高空中导航的效率和性能。这些内容主要集中在如何通过技术手段提升自主代理（Agent）在特定任务（如空中导航）中的表现，因此属于Agent分类。` `空中导航` `城市规划`

> CityNav: Language-Goal Aerial Navigation Dataset with Geographic Information

# 摘要

> 视觉与语言导航（VLN）旨在通过融合视觉和语言线索，引导自主代理在真实世界中航行。尽管地面导航领域已取得显著进展，但空中导航的研究仍显不足，主要原因是缺乏适用于城市规模真实世界空中导航研究的资源。为此，我们推出了CityNav，一个基于真实城市三维点云的新数据集，专为语言引导的空中导航设计。CityNav收录了32,637条与人类演示轨迹相匹配的自然语言描述，这些描述通过专为此研究开发的网络3D模拟器从参与者处收集。每条描述均明确导航目标，利用真实城市中的地标名称和位置。我们还提供了基线模型，这些模型包含一个内部2D空间地图，代表描述中提及的地标。我们在CityNav数据集上测试了最新的空中导航基线模型及我们的提议模型。结果显示：(i) 基于人类演示轨迹训练的空中代理模型表现优于基于最短路径训练的模型，凸显了人类导航策略的重要性；(ii) 2D空间地图的引入显著提升了城市规模导航的效率。数据集和代码已公开，详情请访问https://water-cookie.github.io/city-nav-proj/。

> Vision-and-language navigation (VLN) aims to guide autonomous agents through real-world environments by integrating visual and linguistic cues. While substantial progress has been made in understanding these interactive modalities in ground-level navigation, aerial navigation remains largely underexplored. This is primarily due to the scarcity of resources suitable for real-world, city-scale aerial navigation studies. To bridge this gap, we introduce CityNav, a new dataset for language-goal aerial navigation using a 3D point cloud representation from real-world cities. CityNav includes 32,637 natural language descriptions paired with human demonstration trajectories, collected from participants via a new web-based 3D simulator developed for this research. Each description specifies a navigation goal, leveraging the names and locations of landmarks within real-world cities. We also provide baseline models of navigation agents that incorporate an internal 2D spatial map representing landmarks referenced in the descriptions. We benchmark the latest aerial navigation baselines and our proposed model on the CityNav dataset. The results using this dataset reveal the following key findings: (i) Our aerial agent models trained on human demonstration trajectories outperform those trained on shortest path trajectories, highlighting the importance of human-driven navigation strategies; (ii) The integration of a 2D spatial map significantly enhances navigation efficiency at city scale. Our dataset and code are available at https://water-cookie.github.io/city-nav-proj/

[Arxiv](https://arxiv.org/abs/2406.14240)