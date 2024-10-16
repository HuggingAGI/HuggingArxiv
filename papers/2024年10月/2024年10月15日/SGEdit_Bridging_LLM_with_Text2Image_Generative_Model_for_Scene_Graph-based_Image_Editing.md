# SGEdit：融合 LLM 与 Text2Image 生成模型，实现基于场景图的图像编辑

发布时间：2024年10月15日

`LLM应用` `图像编辑` `人工智能`

> SGEdit: Bridging LLM with Text2Image Generative Model for Scene Graph-based Image Editing

# 摘要

> 场景图以结构化、层次化的方式呈现图像，节点和边分别代表对象及其关系。这为图像编辑提供了自然接口，大幅提升精度和灵活性。我们创新地将大型语言模型 (LLM) 与基于场景图的 Text2Image 生成模型结合，实现对象级精确修改和场景创意重组，同时保持图像完整性。方法分两步：首先，LLM 驱动的场景解析器构建场景图，捕捉对象及其关系，并解析细粒度属性，如掩码和描述，助力微调扩散模型，优化对象表示。其次，LLM 编辑控制器引导编辑，由注意力调制的扩散编辑器执行，实现对象的增删改换。实验表明，我们的框架在编辑精度和场景美学上显著超越现有方法。

> Scene graphs offer a structured, hierarchical representation of images, with nodes and edges symbolizing objects and the relationships among them. It can serve as a natural interface for image editing, dramatically improving precision and flexibility. Leveraging this benefit, we introduce a new framework that integrates large language model (LLM) with Text2Image generative model for scene graph-based image editing. This integration enables precise modifications at the object level and creative recomposition of scenes without compromising overall image integrity. Our approach involves two primary stages: 1) Utilizing a LLM-driven scene parser, we construct an image's scene graph, capturing key objects and their interrelationships, as well as parsing fine-grained attributes such as object masks and descriptions. These annotations facilitate concept learning with a fine-tuned diffusion model, representing each object with an optimized token and detailed description prompt. 2) During the image editing phase, a LLM editing controller guides the edits towards specific areas. These edits are then implemented by an attention-modulated diffusion editor, utilizing the fine-tuned model to perform object additions, deletions, replacements, and adjustments. Through extensive experiments, we demonstrate that our framework significantly outperforms existing image editing methods in terms of editing precision and scene aesthetics.

[Arxiv](https://arxiv.org/abs/2410.11815)