# 交通跟随行为对自动空中管制序列的影响

发布时间：2024年04月26日

`Agent` `交通管理` `智能体系统`

> Impact of Traffic-Following on Order of Autonomous Airspace Operations

# 摘要

> 本文深入探讨了在分布式多智能体系统中，如何通过最小化不必要的结构性限制来动态形成交通秩序。我们提出了一种创新的方法，通过分析当前和历史交通流向的一致性与频率，构建并实时更新空域的交通模式图。借助这一地图，智能体能够评估遵循交通流的效益，从而在时间和秩序之间做出权衡。研究表明，在低度遵循交通行为的情况下，飞机的旅行时间几乎不受影响，却能显著提升空域的有序性。然而，过度的交通跟随可能会增加飞行时间，尽管如此，它也能在一定程度上降低空域的总体混乱度。本研究提出的方法和评价指标，将有助于智能体基于这些权衡，进行最优和动态的交通行为调整。

> In this paper, we investigate the dynamic emergence of traffic order in a distributed multi-agent system, aiming to minimize inefficiencies that stem from unnecessary structural impositions. We introduce a methodology for developing a dynamically-updating traffic pattern map of the airspace by leveraging information about the consistency and frequency of flow directions used by current as well as preceding traffic. Informed by this map, an agent can discern the degree to which it is advantageous to follow traffic by trading off utilities such as time and order. We show that for the traffic levels studied, for low degrees of traffic-following behavior, there is minimal penalty in terms of aircraft travel times while improving the overall orderliness of the airspace. On the other hand, heightened traffic-following behavior may result in increased aircraft travel times, while marginally reducing the overall entropy of the airspace. Ultimately, the methods and metrics presented in this paper can be used to optimally and dynamically adjust an agent's traffic-following behavior based on these trade-offs.

[Arxiv](https://arxiv.org/abs/2404.17627)