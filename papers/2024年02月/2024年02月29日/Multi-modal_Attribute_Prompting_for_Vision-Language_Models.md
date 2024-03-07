# [针对视觉-语言模型，我们提出多模态属性提示方法，旨在通过融合多种模态信息以提升模型的表现力和理解力。](https://arxiv.org/abs/2403.00219)

发布时间：2024年02月29日

`LLM应用`

> Multi-modal Attribute Prompting for Vision-Language Models

> 类似CLIP的大规模预训练视觉-语言模型在下游任务上展现出卓越的泛化性能，但在少量样本情况下却显得力不从心。现有提示技术侧重于全局文本和图像表征，却忽视了多模态属性特性，这限制了模型对细粒度视觉信息的感知能力和对更多未见过类别的泛化范围。为此，我们创新性地提出了多模态属性提示方法（MAP），它巧妙结合了文本属性提示、视觉属性提示及属性层级对齐策略。MAP有三大优势：一，我们设计了借助文本属性语义增强的可学习视觉属性提示，能灵活捕获来自未知类别的图像细微视觉属性，有效提升CLIP的精细化视觉理解力；二，提出的属性层级对齐机制与全局对齐互补，强化了对开放词汇对象跨模态对齐的稳健性。值得一提的是，本研究首次尝试针对CLIP构建跨模态属性层级对齐的小样本适应框架。在涵盖11个数据集的广泛实验验证中，我们所提方法显著超越了当前最先进的解决方案。

> Large pre-trained Vision-Language Models (VLMs), like CLIP, exhibit strong generalization ability to downstream tasks but struggle in few-shot scenarios. Existing prompting techniques primarily focus on global text and image representations, yet overlooking multi-modal attribute characteristics. This limitation hinders the model's ability to perceive fine-grained visual details and restricts its generalization ability to a broader range of unseen classes. To address this issue, we propose a Multi-modal Attribute Prompting method (MAP) by jointly exploring textual attribute prompting, visual attribute prompting, and attribute-level alignment. The proposed MAP enjoys several merits. First, we introduce learnable visual attribute prompts enhanced by textual attribute semantics to adaptively capture visual attributes for images from unknown categories, boosting fine-grained visual perception capabilities for CLIP. Second, the proposed attribute-level alignment complements the global alignment to enhance the robustness of cross-modal alignment for open-vocabulary objects. To our knowledge, this is the first work to establish cross-modal attribute-level alignment for CLIP-based few-shot adaptation. Extensive experimental results on 11 datasets demonstrate that our method performs favorably against state-of-the-art approaches.