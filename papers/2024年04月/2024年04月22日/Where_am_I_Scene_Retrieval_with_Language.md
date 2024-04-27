# “我身在何方？”通过语言技术实现场景检索

发布时间：2024年04月22日

`Agent` `具身智能`

> "Where am I?" Scene Retrieval with Language

# 摘要

> 自然语言界面在具身智能领域的应用日益广泛，为我们与智能代理进行基于语言的互动提供了更多可能，如指导代理在特定地点完成任务。举例来说，用户可能会说：“把碗放回冰箱旁的橱柜里”，或者“在那个有红色标志的十字路口见我”。为了实现这一功能，我们需要一种能够将自然语言与环境地图表示形式相连接的方法。基于此，我们研究了一个关键问题：我们能否通过开放式自然语言查询来识别由3D场景图表示的场景。我们将这一任务命名为“基于语言的场景检索”，它与“粗略定位”有关，但我们的目标是在一系列独立的3D场景集合中寻找匹配项，而非在大规模连续地图上。因此，我们开发了Text2SceneGraphMatcher，这是一个学习文本描述与场景图之间联合嵌入的“场景检索”流程，用以判断它们是否匹配。相关的代码、训练好的模型以及数据集将对公众开放。

> Natural language interfaces to embodied AI are becoming more ubiquitous in our daily lives. This opens further opportunities for language-based interaction with embodied agents, such as a user instructing an agent to execute some task in a specific location. For example, "put the bowls back in the cupboard next to the fridge" or "meet me at the intersection under the red sign." As such, we need methods that interface between natural language and map representations of the environment. To this end, we explore the question of whether we can use an open-set natural language query to identify a scene represented by a 3D scene graph. We define this task as "language-based scene-retrieval" and it is closely related to "coarse-localization," but we are instead searching for a match from a collection of disjoint scenes and not necessarily a large-scale continuous map. Therefore, we present Text2SceneGraphMatcher, a "scene-retrieval" pipeline that learns joint embeddings between text descriptions and scene graphs to determine if they are matched. The code, trained models, and datasets will be made public.

[Arxiv](https://arxiv.org/abs/2404.14565)