# 3D场景中的多模态情境推理

发布时间：2024年09月03日

`Agent` `人工智能` `计算机视觉`

> Multi-modal Situated Reasoning in 3D Scenes

# 摘要

> 情境意识对具身AI代理理解3D场景至关重要。为突破现有数据集的局限，我们推出了多模态情境问答（MSQA），一个涵盖广泛真实3D场景的大型多模态数据集。MSQA包含25万多个问答对，涉及九大类别，全面覆盖复杂情境。我们创新性地采用交错多模态输入，融合文本、图像和点云，以消除单一模态的歧义。此外，我们还设计了MSNN基准，用于评估导航中的情境推理。综合评估显示，现有视觉-语言模型在处理多模态输入和情境建模方面存在不足。实验证明，MSQA作为预训练数据集，能有效提升情境推理模型的性能。

> Situation awareness is essential for understanding and reasoning about 3D scenes in embodied AI agents. However, existing datasets and benchmarks for situated understanding are limited in data modality, diversity, scale, and task scope. To address these limitations, we propose Multi-modal Situated Question Answering (MSQA), a large-scale multi-modal situated reasoning dataset, scalably collected leveraging 3D scene graphs and vision-language models (VLMs) across a diverse range of real-world 3D scenes. MSQA includes 251K situated question-answering pairs across 9 distinct question categories, covering complex scenarios within 3D scenes. We introduce a novel interleaved multi-modal input setting in our benchmark to provide text, image, and point cloud for situation and question description, resolving ambiguity in previous single-modality convention (e.g., text). Additionally, we devise the Multi-modal Situated Next-step Navigation (MSNN) benchmark to evaluate models' situated reasoning for navigation. Comprehensive evaluations on MSQA and MSNN highlight the limitations of existing vision-language models and underscore the importance of handling multi-modal interleaved inputs and situation modeling. Experiments on data scaling and cross-domain transfer further demonstrate the efficacy of leveraging MSQA as a pre-training dataset for developing more powerful situated reasoning models.

[Arxiv](https://arxiv.org/abs/2409.02389)