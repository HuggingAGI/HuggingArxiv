# 实现真实：释放大型多模态模型的潜力，以绘制采用逼真材质的三维物体。

发布时间：2024年04月25日

`LLM应用` `3D建模` `人工智能`

> Make-it-Real: Unleashing Large Multimodal Model's Ability for Painting 3D Objects with Realistic Materials

# 摘要

> 物理真实感材料对于提升3D资产在不同应用和光照条件下的真实度起着关键作用。但目前3D资产和生成模型往往缺少真实的材质属性。手动通过图形软件分配材质既繁琐又耗时。本文中，我们借助多模态大型语言模型（MLLMs），尤其是GPT-4V，提出了一种创新方法“Make-it-Real”：首先，我们展示了GPT-4V在识别和描述材质方面的高效能力，这有助于构建一个详尽的材质库；其次，通过结合视觉线索和层级化文本提示，GPT-4V能够精确地识别并匹配3D对象的相应部件的材质；最后，正确匹配的材质被精心应用于新的SVBRDF材质生成过程，以原始漫反射图为参考，显著提升了视觉真实感。“Make-it-Real”作为一个高效的工具，为3D内容创作流程提供了简化的集成方案，对3D资产开发者来说极具价值。

> Physically realistic materials are pivotal in augmenting the realism of 3D assets across various applications and lighting conditions. However, existing 3D assets and generative models often lack authentic material properties. Manual assignment of materials using graphic software is a tedious and time-consuming task. In this paper, we exploit advancements in Multimodal Large Language Models (MLLMs), particularly GPT-4V, to present a novel approach, Make-it-Real: 1) We demonstrate that GPT-4V can effectively recognize and describe materials, allowing the construction of a detailed material library. 2) Utilizing a combination of visual cues and hierarchical text prompts, GPT-4V precisely identifies and aligns materials with the corresponding components of 3D objects. 3) The correctly matched materials are then meticulously applied as reference for the new SVBRDF material generation according to the original diffuse map, significantly enhancing their visual authenticity. Make-it-Real offers a streamlined integration into the 3D content creation workflow, showcasing its utility as an essential tool for developers of 3D assets.

[Arxiv](https://arxiv.org/abs/2404.16829)