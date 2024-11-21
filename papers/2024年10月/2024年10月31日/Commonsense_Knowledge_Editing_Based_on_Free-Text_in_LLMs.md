# 在大型语言模型中基于自由文本的常识知识编辑

发布时间：2024年10月31日

`LLM应用` `知识编辑` `常识知识`

> Commonsense Knowledge Editing Based on Free-Text in LLMs

# 摘要

> 知识编辑技术对维持大型语言模型（LLMs）的准确性和及时性极为关键。然而，这项任务的设定忽略了现实世界中基于自由文本的大量常识知识，其具有知识范畴广、内容长且未实例化的特点。以往方法（如 MEMIT）的编辑对象为单个标记或实体，不适用于自由文本形式的常识知识。为应对上述挑战，我们从知识定位和知识编辑这两个角度展开实验。首先，引入自由文本知识定位（KLFT）方法，揭示了 MLP 和注意力层以及分散分布中常识知识分布的相关挑战。接着，提出动态感知编辑方法（DEM），利用动态感知模块定位与常识知识对应的参数位置，并通过知识编辑模块更新知识。DEM 方法充分发掘了 MLP 和注意力层的潜力，成功编辑了基于自由文本的常识知识。实验结果表明，DEM 能够取得出色的编辑效果。

> Knowledge editing technology is crucial for maintaining the accuracy and timeliness of large language models (LLMs) . However, the setting of this task overlooks a significant portion of commonsense knowledge based on free-text in the real world, characterized by broad knowledge scope, long content and non instantiation. The editing objects of previous methods (e.g., MEMIT) were single token or entity, which were not suitable for commonsense knowledge in free-text form. To address the aforementioned challenges, we conducted experiments from two perspectives: knowledge localization and knowledge editing. Firstly, we introduced Knowledge Localization for Free-Text(KLFT) method, revealing the challenges associated with the distribution of commonsense knowledge in MLP and Attention layers, as well as in decentralized distribution. Next, we propose a Dynamics-aware Editing Method(DEM), which utilizes a Dynamics-aware Module to locate the parameter positions corresponding to commonsense knowledge, and uses Knowledge Editing Module to update knowledge. The DEM method fully explores the potential of the MLP and Attention layers, and successfully edits commonsense knowledge based on free-text. The experimental results indicate that the DEM can achieve excellent editing performance.

[Arxiv](https://arxiv.org/abs/2410.23844)