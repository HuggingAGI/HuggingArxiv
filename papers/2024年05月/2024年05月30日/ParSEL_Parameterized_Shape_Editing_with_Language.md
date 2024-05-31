# ParSEL：语言驱动的参数化形状编辑

发布时间：2024年05月30日

`LLM应用

这篇论文介绍了ParSEL系统，该系统利用大型语言模型（LLMs）来推断和生成符合用户意图的编辑程序，以实现对3D资产的精细操控。论文中提到的AEP算法和LLMs的应用，都是为了解决自然语言在精确操作指定上的不足，并提高3D内容创作的效率和精确性。因此，这篇论文属于LLM应用类别，因为它展示了LLMs在特定应用场景（即3D资产编辑）中的实际应用和效果。` `3D内容创作`

> ParSEL: Parameterized Shape Editing with Language

# 摘要

> 自然语言编辑3D资产的能力为3D内容创作的普及开辟了新途径。尽管自然语言在表达一般意图上颇具优势，但在精确操作的指定上却显得力不从心。为此，我们推出了ParSEL系统，它让用户能够通过自然语言对高质量3D资产进行精细操控。用户只需提供一个分割的3D网格和编辑请求，ParSEL便能生成一个可调节参数的编辑程序，让用户在精确控制下探索形状的多样变化。我们借助大型语言模型（LLMs）来推断符合用户意图的编辑程序，虽然LLMs在识别初步编辑操作上表现出色，但在构建完整编辑程序时却常显不足，有时甚至会违背形状的固有语义。为此，我们开发了分析编辑传播（AEP）算法，它通过逐步添加操作，直至形成完整的编辑程序。与以往方法不同，AEP通过计算机代数系统进行几何分析，寻找与用户可能的编辑意图相匹配的分析编辑操作。实验结果显示，ParSEL在通过自然语言请求实现3D对象的可控编辑方面，明显优于其他系统设计。

> The ability to edit 3D assets from natural language presents a compelling paradigm to aid in the democratization of 3D content creation. However, while natural language is often effective at communicating general intent, it is poorly suited for specifying precise manipulation. To address this gap, we introduce ParSEL, a system that enables controllable editing of high-quality 3D assets from natural language. Given a segmented 3D mesh and an editing request, ParSEL produces a parameterized editing program. Adjusting the program parameters allows users to explore shape variations with a precise control over the magnitudes of edits. To infer editing programs which align with an input edit request, we leverage the abilities of large-language models (LLMs). However, while we find that LLMs excel at identifying initial edit operations, they often fail to infer complete editing programs, and produce outputs that violate shape semantics. To overcome this issue, we introduce Analytical Edit Propagation (AEP), an algorithm which extends a seed edit with additional operations until a complete editing program has been formed. Unlike prior methods, AEP searches for analytical editing operations compatible with a range of possible user edits through the integration of computer algebra systems for geometric analysis. Experimentally we demonstrate ParSEL's effectiveness in enabling controllable editing of 3D objects through natural language requests over alternative system designs.

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x1.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x2.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x3.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x4.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x5.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x6.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x7.png)

![ParSEL：语言驱动的参数化形状编辑](../../../paper_images/2405.20319/x8.png)

[Arxiv](https://arxiv.org/abs/2405.20319)