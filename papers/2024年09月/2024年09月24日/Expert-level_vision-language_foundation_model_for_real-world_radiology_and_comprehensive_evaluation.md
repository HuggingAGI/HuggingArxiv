# 专家级视觉-语言模型，专为现实放射学应用设计，并进行全面评估

发布时间：2024年09月24日

`LLM应用` `放射学`

> Expert-level vision-language foundation model for real-world radiology and comprehensive evaluation

# 摘要

> 放射学在现代医疗中扮演着关键角色，涉及众多复杂任务。近期，医学视觉-语言模型崭露头角，为多模态放射学任务提供了统一解决方案。然而，现有研究多聚焦于自然数据预训练，忽视了放射学图像的独特复杂性。为此，我们推出了RadFound，一个专为放射学设计的大型开源视觉-语言模型，基于810万张图像和25万对图像-文本数据，涵盖19个器官系统和10种成像模式。RadFound通过增强视觉编码器和跨模态学习设计，提升了多模态感知和生成能力。我们还构建了RadVLBench基准测试，涵盖医学问答和文本生成任务，并引入人类评估框架。在现实世界测试中，RadFound在定量和人类评估方面均表现卓越。RadFound的诞生标志着放射学领域的重大进步，展现了广阔的临床应用前景。

> Radiology is a vital and complex component of modern clinical workflow and covers many tasks. Recently, vision-language (VL) foundation models in medicine have shown potential in processing multimodal information, offering a unified solution for various radiology tasks. However, existing studies either pre-trained VL models on natural data or did not fully integrate vision-language architecture and pretraining, often neglecting the unique multimodal complexity in radiology images and their textual contexts. Additionally, their practical applicability in real-world scenarios remains underexplored. Here, we present RadFound, a large and open-source vision-language foundation model tailored for radiology, that is trained on the most extensive dataset of over 8.1 million images and 250,000 image-text pairs, covering 19 major organ systems and 10 imaging modalities. To establish expert-level multimodal perception and generation capabilities, RadFound introduces an enhanced vision encoder to capture intra-image local features and inter-image contextual information, and a unified cross-modal learning design tailored to radiology. To fully assess the models' capability, we construct a benchmark, RadVLBench, including radiology interpretation tasks like medical vision-language question-answering, as well as text generation tasks ranging from captioning to report generation. We also propose a human evaluation framework. When evaluated on the real-world benchmark involving three representative modalities, 2D images (chest X-rays), multi-view images (mammograms), and 3D images (thyroid CT scans), RadFound significantly outperforms other VL foundation models on both quantitative metrics and human evaluation. In summary, the development of RadFound represents an advancement in radiology generalists, demonstrating broad applicability potential for integration into clinical workflows.

[Arxiv](https://arxiv.org/abs/2409.16183)