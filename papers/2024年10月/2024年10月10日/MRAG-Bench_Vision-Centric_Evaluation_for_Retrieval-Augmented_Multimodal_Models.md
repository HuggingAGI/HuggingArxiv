# MRAG-Bench：专注于视觉的多模态模型增强检索评估工具

发布时间：2024年10月10日

`RAG` `计算机视觉` `人工智能`

> MRAG-Bench: Vision-Centric Evaluation for Retrieval-Augmented Multimodal Models

# 摘要

> 现有的多模态检索基准主要评估模型在问答中利用外部文本知识的能力。然而，在某些场景中，视觉信息的检索更为关键或便捷。为此，我们推出了 MRAG-Bench，一个专注于视觉增强知识优于文本知识的多模态检索增强生成基准。MRAG-Bench 包含 16,130 张图像和 1,353 个人工标注的多项选择题，覆盖 9 种场景。我们评估了 10 个开源和 4 个专有的视觉语言大模型（LVLMs），发现所有模型在图像增强下的表现均优于文本知识，凸显了 MRAG-Bench 的视觉导向性。此外，通过 MRAG-Bench 的深入分析，我们揭示了检索增强 LVLMs 的潜力与挑战。例如，顶尖模型 GPT-4o 在利用检索知识方面仅提升 5.82%，远低于人类参与者的 33.16%。这些发现突显了 MRAG-Bench 在推动 LVLMs 更高效利用视觉检索知识方面的重要性。

> Existing multimodal retrieval benchmarks primarily focus on evaluating whether models can retrieve and utilize external textual knowledge for question answering. However, there are scenarios where retrieving visual information is either more beneficial or easier to access than textual data. In this paper, we introduce a multimodal retrieval-augmented generation benchmark, MRAG-Bench, in which we systematically identify and categorize scenarios where visually augmented knowledge is better than textual knowledge, for instance, more images from varying viewpoints. MRAG-Bench consists of 16,130 images and 1,353 human-annotated multiple-choice questions across 9 distinct scenarios. With MRAG-Bench, we conduct an evaluation of 10 open-source and 4 proprietary large vision-language models (LVLMs). Our results show that all LVLMs exhibit greater improvements when augmented with images compared to textual knowledge, confirming that MRAG-Bench is vision-centric. Additionally, we conduct extensive analysis with MRAG-Bench, which offers valuable insights into retrieval-augmented LVLMs. Notably, the top-performing model, GPT-4o, faces challenges in effectively leveraging retrieved knowledge, achieving only a 5.82% improvement with ground-truth information, in contrast to a 33.16% improvement observed in human participants. These findings highlight the importance of MRAG-Bench in encouraging the community to enhance LVLMs' ability to utilize retrieved visual knowledge more effectively.

[Arxiv](https://arxiv.org/abs/2410.08182)