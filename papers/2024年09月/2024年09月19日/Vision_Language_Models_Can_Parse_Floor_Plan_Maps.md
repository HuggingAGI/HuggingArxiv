# 视觉语言模型能够解析楼层平面图

发布时间：2024年09月19日

`LLM应用` `机器人` `地理信息系统`

> Vision Language Models Can Parse Floor Plan Maps

# 摘要

> 视觉语言模型 (VLM) 能够同时处理图像和文本，广泛应用于视觉问答和图像描述等任务。本文聚焦于地图解析，这一在 VLM 领域尚待探索的新任务，对移动机器人尤为重要。地图解析不仅涉及标签理解，还需掌握地图的几何结构，即各区域特征及其连接方式。为测试 VLM 在地图解析中的表现，我们利用平面图生成室内导航任务计划。实验表明，VLM 在复杂导航任务中表现出色，成功率达 0.96，如连续完成九个导航动作。此外，我们发现 VLM 在小地图和简单任务中表现更佳，但在大型开放区域中性能有所下降。基于此，我们提出了应对这些挑战的实用建议。详情请访问：https://shorturl.at/OUkEY

> Vision language models (VLMs) can simultaneously reason about images and texts to tackle many tasks, from visual question answering to image captioning. This paper focuses on map parsing, a novel task that is unexplored within the VLM context and particularly useful to mobile robots. Map parsing requires understanding not only the labels but also the geometric configurations of a map, i.e., what areas are like and how they are connected. To evaluate the performance of VLMs on map parsing, we prompt VLMs with floorplan maps to generate task plans for complex indoor navigation. Our results demonstrate the remarkable capability of VLMs in map parsing, with a success rate of 0.96 in tasks requiring a sequence of nine navigation actions, e.g., approaching and going through doors. Other than intuitive observations, e.g., VLMs do better in smaller maps and simpler navigation tasks, there was a very interesting observation that its performance drops in large open areas. We provide practical suggestions to address such challenges as validated by our experimental results. Webpage: https://shorturl.at/OUkEY

[Arxiv](https://arxiv.org/abs/2409.12842)