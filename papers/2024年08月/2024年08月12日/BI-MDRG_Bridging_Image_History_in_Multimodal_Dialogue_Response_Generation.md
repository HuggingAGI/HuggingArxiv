# BI-MDRG：连接多模态对话中的图像历史，助力响应生成

发布时间：2024年08月12日

`LLM应用` `人工智能` `图像处理`

> BI-MDRG: Bridging Image History in Multimodal Dialogue Response Generation

# 摘要

> 多模态对话响应生成 (MDRG) 任务要求模型根据对话上下文生成文本、图像或两者结合的响应。由于缺乏专用的大规模数据集，以往研究多依赖文本模态作为图像输入输出的过渡，而非端到端处理。这种做法可能遗漏图像关键信息，影响基于图像的文本响应及图像响应中对象的一致性。本文提出 BI-MDRG，通过整合图像历史信息，提升文本响应与图像内容的相关性及连续图像响应中对象的一致性。实验表明，BI-MDRG 能显著提升多模态对话质量。同时，针对评估图像一致性的数据集缺口，我们精心标注了 300 个对话，以追踪对话间对象的一致性。

> Multimodal Dialogue Response Generation (MDRG) is a recently proposed task where the model needs to generate responses in texts, images, or a blend of both based on the dialogue context. Due to the lack of a large-scale dataset specifically for this task and the benefits of leveraging powerful pre-trained models, previous work relies on the text modality as an intermediary step for both the image input and output of the model rather than adopting an end-to-end approach. However, this approach can overlook crucial information about the image, hindering 1) image-grounded text response and 2) consistency of objects in the image response. In this paper, we propose BI-MDRG that bridges the response generation path such that the image history information is utilized for enhanced relevance of text responses to the image content and the consistency of objects in sequential image responses. Through extensive experiments on the multimodal dialogue benchmark dataset, we show that BI-MDRG can effectively increase the quality of multimodal dialogue. Additionally, recognizing the gap in benchmark datasets for evaluating the image consistency in multimodal dialogue, we have created a curated set of 300 dialogues annotated to track object consistency across conversations.

[Arxiv](https://arxiv.org/abs/2408.05926)