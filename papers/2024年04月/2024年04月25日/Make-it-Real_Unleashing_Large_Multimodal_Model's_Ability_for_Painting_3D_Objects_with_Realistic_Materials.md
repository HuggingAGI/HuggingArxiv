# 实现真实：激发大型多模态模型的潜力，以逼真材质绘制三维物体。

发布时间：2024年04月25日

`分类：LLM应用

这篇论文介绍了一种名为Make-it-Real的创新方法，它利用了多模态大型语言模型（特别是GPT-4V）来提升3D资产的真实感。该方法通过识别和描述材料，构建详尽的材料数据库，然后精确匹配并调整3D对象各部分的材料，最后将这些材料应用于新的SVBRDF材质生成过程，以显著提升视觉真实度。这篇论文展示了大型语言模型在3D内容创作领域的应用，因此可以归类为LLM应用。` `3D建模` `人工智能`

> Make-it-Real: Unleashing Large Multimodal Model's Ability for Painting 3D Objects with Realistic Materials

# 摘要

> 在3D资产的真实感提升中，物理真实性材料扮演着关键角色，适用于多样的应用场景和光照条件。但目前，众多3D资产和生成模型在模拟真实材料特性上存在不足。手动通过图形软件分配材料既繁琐又耗时。本文介绍了一种创新方法——Make-it-Real，利用多模态大型语言模型（尤其是GPT-4V）的进展：首先，GPT-4V能够高效识别和描述材料，构建出详尽的材料数据库；其次，结合视觉提示和分层文本指令，GPT-4V能精确匹配并调整3D对象各部分的材料；最后，这些匹配的材料被精细地应用于新的SVBRDF材质生成过程，根据原始漫反射图显著提升视觉真实度。Make-it-Real简化了3D内容创作的流程，成为3D资产开发者的得力助手。

> Physically realistic materials are pivotal in augmenting the realism of 3D assets across various applications and lighting conditions. However, existing 3D assets and generative models often lack authentic material properties. Manual assignment of materials using graphic software is a tedious and time-consuming task. In this paper, we exploit advancements in Multimodal Large Language Models (MLLMs), particularly GPT-4V, to present a novel approach, Make-it-Real: 1) We demonstrate that GPT-4V can effectively recognize and describe materials, allowing the construction of a detailed material library. 2) Utilizing a combination of visual cues and hierarchical text prompts, GPT-4V precisely identifies and aligns materials with the corresponding components of 3D objects. 3) The correctly matched materials are then meticulously applied as reference for the new SVBRDF material generation according to the original diffuse map, significantly enhancing their visual authenticity. Make-it-Real offers a streamlined integration into the 3D content creation workflow, showcasing its utility as an essential tool for developers of 3D assets.

[Arxiv](https://arxiv.org/abs/2404.16829)