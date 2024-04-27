# "我身在何方？" 通过语言实现场景检索

发布时间：2024年04月22日

`Agent` `人工智能`

> "Where am I?" Scene Retrieval with Language

# 摘要

> 自然语言接口在我们的日常生活中变得越来越常见，这为与体现智能体的语言交互开辟了更多可能性。比如，用户可以指示智能体在特定地点完成某项任务，如“把碗放回冰箱旁的碗柜”或“在有红牌子的路口见我”。为了实现这一点，我们需要一种能够将自然语言与环境的地图表示形式相连接的方法。我们研究了一个问题：是否能够利用开放式自然语言查询来识别由3D场景图表示的场景。我们将这一任务命名为“基于语言的场景检索”，它与“粗略定位”紧密相关，但我们是在一系列独立的场所中寻找匹配项，而非在大规模连续地图中搜索。因此，我们介绍了Text2SceneGraphMatcher，这是一个“场景检索”流程，它通过学习文本描述和场景图之间的联合嵌入来确定它们是否匹配。相关的代码、训练好的模型和数据集将向公众开放。

> Natural language interfaces to embodied AI are becoming more ubiquitous in our daily lives. This opens further opportunities for language-based interaction with embodied agents, such as a user instructing an agent to execute some task in a specific location. For example, "put the bowls back in the cupboard next to the fridge" or "meet me at the intersection under the red sign." As such, we need methods that interface between natural language and map representations of the environment. To this end, we explore the question of whether we can use an open-set natural language query to identify a scene represented by a 3D scene graph. We define this task as "language-based scene-retrieval" and it is closely related to "coarse-localization," but we are instead searching for a match from a collection of disjoint scenes and not necessarily a large-scale continuous map. Therefore, we present Text2SceneGraphMatcher, a "scene-retrieval" pipeline that learns joint embeddings between text descriptions and scene graphs to determine if they are matched. The code, trained models, and datasets will be made public.

[Arxiv](https://arxiv.org/abs/2404.14565)