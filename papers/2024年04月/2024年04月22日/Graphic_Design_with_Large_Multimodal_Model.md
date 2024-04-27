# 大型多模态模型在图形设计中的应用

发布时间：2024年04月22日

`分类：LLM应用` `平面设计` `自动化设计`

> Graphic Design with Large Multimodal Model

# 摘要

> 在平面设计界，自动化设计元素的整合以创作出层次分明的艺术作品，既提升了效率，也为设计领域的大众化开辟了道路。目前，图形布局生成（GLG）是一种流行的方法，它专注于顺序化设计元素的布局。然而，这种方法受限于必须事先确定图层的正确顺序，这不仅束缚了创意的翅膀，也加重了用户的负担。本文提出了一种新的解决方案——层次化布局生成（HLG），它更为灵活，能够从无序的设计元素中创造出视觉构图。为应对HLG挑战，我们推出了Graphist，这是首个基于大型多模态模型的布局生成模型。Graphist巧妙地将HLG问题转化为序列生成问题，输入RGB-A图像，输出包含元素坐标、尺寸和顺序信息的JSON草图协议。我们还为HLG设计了新的评估标准，Graphist在这些标准上超越了先前的方法，并为该领域设定了新的基准。项目详情可访问：https://github.com/graphic-design-ai/graphist

> In the field of graphic design, automating the integration of design elements into a cohesive multi-layered artwork not only boosts productivity but also paves the way for the democratization of graphic design. One existing practice is Graphic Layout Generation (GLG), which aims to layout sequential design elements. It has been constrained by the necessity for a predefined correct sequence of layers, thus limiting creative potential and increasing user workload. In this paper, we present Hierarchical Layout Generation (HLG) as a more flexible and pragmatic setup, which creates graphic composition from unordered sets of design elements. To tackle the HLG task, we introduce Graphist, the first layout generation model based on large multimodal models. Graphist efficiently reframes the HLG as a sequence generation problem, utilizing RGB-A images as input, outputs a JSON draft protocol, indicating the coordinates, size, and order of each element. We develop new evaluation metrics for HLG. Graphist outperforms prior arts and establishes a strong baseline for this field. Project homepage: https://github.com/graphic-design-ai/graphist

[Arxiv](https://arxiv.org/abs/2404.14368)