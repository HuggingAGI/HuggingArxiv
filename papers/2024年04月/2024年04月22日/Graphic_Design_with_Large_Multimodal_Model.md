# 大型多模态模型在图形设计中的应用

发布时间：2024年04月22日

`LLM应用` `平面设计` `自动化设计`

> Graphic Design with Large Multimodal Model

# 摘要

> 在平面设计界，自动化地将设计元素融合为一个和谐的多层艺术作品，既提升了效率，也为设计的普及化开辟了新径。目前，图形布局生成（GLG）技术正致力于有序地排列设计元素，但这种做法因要求预先设定正确的层级顺序而受限，这不仅束缚了创意的翅膀，也加重了用户的工作负担。本文提出了一种新颖的分层布局生成（HLG）方法，它以一种更灵活、更实用的框架，从无序的设计元素集合中创造出图形构图。为应对HLG挑战，我们推出了Graphist——首个基于大型多模态模型的布局生成模型。Graphist巧妙地将HLG问题转化为序列生成问题，输入RGB-A图像，输出包含坐标、尺寸和元素顺序信息的JSON草稿协议。我们还为HLG任务设计了全新的评估标准，Graphist在这些标准上超越了先前的技术，并为该领域设定了新的基准。项目网址：https://github.com/graphic-design-ai/graphist

> In the field of graphic design, automating the integration of design elements into a cohesive multi-layered artwork not only boosts productivity but also paves the way for the democratization of graphic design. One existing practice is Graphic Layout Generation (GLG), which aims to layout sequential design elements. It has been constrained by the necessity for a predefined correct sequence of layers, thus limiting creative potential and increasing user workload. In this paper, we present Hierarchical Layout Generation (HLG) as a more flexible and pragmatic setup, which creates graphic composition from unordered sets of design elements. To tackle the HLG task, we introduce Graphist, the first layout generation model based on large multimodal models. Graphist efficiently reframes the HLG as a sequence generation problem, utilizing RGB-A images as input, outputs a JSON draft protocol, indicating the coordinates, size, and order of each element. We develop new evaluation metrics for HLG. Graphist outperforms prior arts and establishes a strong baseline for this field. Project homepage: https://github.com/graphic-design-ai/graphist

[Arxiv](https://arxiv.org/abs/2404.14368)