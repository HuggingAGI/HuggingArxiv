# "我身在何处？" 语言辅助的场景检索技术

发布时间：2024年04月22日

`Agent` `具身智能`

> "Where am I?" Scene Retrieval with Language

# 摘要

> 随着自然语言接口在具身智能领域的广泛应用，我们日常与智能代理的交流变得更加便捷。用户可以轻松地命令代理在特定地点完成特定任务，如“将碗放回冰箱旁的橱柜”或“在有红色标志的路口与我碰面”。为了实现这一点，我们迫切需要一种能够将自然语言与环境地图表示相连接的方法。本研究旨在探讨是否能够通过开放式自然语言查询来识别由三维场景图表示的场景，这一任务被称为“基于语言的场景检索”，与“粗略定位”紧密相关，但不同之处在于，我们是在一系列独立的场集中寻找匹配项，而非在大规模连续地图中搜索。因此，我们设计了Text2SceneGraphMatcher，这是一个“场景检索”流程，它通过学习文本描述与场景图之间的联合嵌入来确认它们是否匹配。相关的代码、训练模型和数据集将向公众开放。

> Natural language interfaces to embodied AI are becoming more ubiquitous in our daily lives. This opens further opportunities for language-based interaction with embodied agents, such as a user instructing an agent to execute some task in a specific location. For example, "put the bowls back in the cupboard next to the fridge" or "meet me at the intersection under the red sign." As such, we need methods that interface between natural language and map representations of the environment. To this end, we explore the question of whether we can use an open-set natural language query to identify a scene represented by a 3D scene graph. We define this task as "language-based scene-retrieval" and it is closely related to "coarse-localization," but we are instead searching for a match from a collection of disjoint scenes and not necessarily a large-scale continuous map. Therefore, we present Text2SceneGraphMatcher, a "scene-retrieval" pipeline that learns joint embeddings between text descriptions and scene graphs to determine if they are matched. The code, trained models, and datasets will be made public.

[Arxiv](https://arxiv.org/abs/2404.14565)