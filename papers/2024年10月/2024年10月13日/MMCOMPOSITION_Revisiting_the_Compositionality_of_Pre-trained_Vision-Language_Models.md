# MMCOMPOSITION：探索预训练视觉-语言模型的组合性

发布时间：2024年10月13日

`LLM应用` `人工智能` `计算机视觉`

> MMCOMPOSITION: Revisiting the Compositionality of Pre-trained Vision-Language Models

# 摘要

> 大型视觉语言模型 (VLMs) 的出现极大地推动了多模态理解，使得在图像和视频字幕、视觉问答和跨模态检索等任务中，视觉和文本信息的整合更加精细和准确。然而，尽管 VLMs 能力卓越，研究人员对其组合性（即理解和生成新组合的能力）的理解仍显不足。现有基准仅从对象、关系和属性角度进行粗略评估，忽略了更深层次的推理。为了填补这一空白，我们推出了 MMCOMPOSITION，一个全新的人工注释基准，旨在全面准确地评估 VLMs 的组合性。通过 MMCOMPOSITION，我们发现 GPT-4o 的组合性竟不如最佳开源模型，并深入分析了原因。实验揭示了 VLMs 在细粒度组合感知和推理上的局限，为未来的 VLM 设计和训练指明了方向。资源链接：https://hanghuacs.github.io/MMComposition/

> The advent of large Vision-Language Models (VLMs) has significantly advanced multimodal understanding, enabling more sophisticated and accurate integration of visual and textual information across various tasks, including image and video captioning, visual question answering, and cross-modal retrieval. Despite VLMs' superior capabilities, researchers lack a comprehensive understanding of their compositionality -- the ability to understand and produce novel combinations of known visual and textual components. Prior benchmarks provide only a relatively rough compositionality evaluation from the perspectives of objects, relations, and attributes while neglecting deeper reasoning about object interactions, counting, and complex compositions. However, compositionality is a critical ability that facilitates coherent reasoning and understanding across modalities for VLMs. To address this limitation, we propose MMCOMPOSITION, a novel human-annotated benchmark for comprehensively and accurately evaluating VLMs' compositionality. Our proposed benchmark serves as a complement to these earlier works. With MMCOMPOSITION, we can quantify and explore the compositionality of the mainstream VLMs. Surprisingly, we find GPT-4o's compositionality inferior to the best open-source model, and we analyze the underlying reasons. Our experimental analysis reveals the limitations of VLMs in fine-grained compositional perception and reasoning, and points to areas for improvement in VLM design and training. Resources available at: https://hanghuacs.github.io/MMComposition/

[Arxiv](https://arxiv.org/abs/2410.09733)