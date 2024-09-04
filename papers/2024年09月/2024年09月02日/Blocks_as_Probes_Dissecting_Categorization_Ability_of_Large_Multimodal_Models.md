# 以块为探针：深入解析大型多模态模型的分类本领

发布时间：2024年09月02日

`LLM应用` `计算机视觉` `认知科学`

> Blocks as Probes: Dissecting Categorization Ability of Large Multimodal Models

# 摘要

> 分类作为人类认知的核心能力，对认知科学和计算机视觉至关重要。为了评估视觉AI的分类能力，研究者们提出了多种任务。最新的大型多模态模型（LMMs）在高级视觉任务中表现出色，但对其基本分类能力的深入评估仍显不足。借鉴人类认知过程，分类包括类别学习和使用。我们提出的ComBo基准，通过解耦框架全面评估这一过程，揭示LMMs在泛化能力上虽有进步，但在细粒度感知和抽象理解等方面仍与人类有差距。这一研究不仅挑战了现有模型，也为LMMs的未来发展提供了新视角。

> Categorization, a core cognitive ability in humans that organizes objects based on common features, is essential to cognitive science as well as computer vision. To evaluate the categorization ability of visual AI models, various proxy tasks on recognition from datasets to open world scenarios have been proposed. Recent development of Large Multimodal Models (LMMs) has demonstrated impressive results in high-level visual tasks, such as visual question answering, video temporal reasoning, etc., utilizing the advanced architectures and large-scale multimodal instruction tuning. Previous researchers have developed holistic benchmarks to measure the high-level visual capability of LMMs, but there is still a lack of pure and in-depth quantitative evaluation of the most fundamental categorization ability. According to the research on human cognitive process, categorization can be seen as including two parts: category learning and category use. Inspired by this, we propose a novel, challenging, and efficient benchmark based on composite blocks, called ComBo, which provides a disentangled evaluation framework and covers the entire categorization process from learning to use. By analyzing the results of multiple evaluation tasks, we find that although LMMs exhibit acceptable generalization ability in learning new categories, there are still gaps compared to humans in many ways, such as fine-grained perception of spatial relationship and abstract category understanding. Through the study of categorization, we can provide inspiration for the further development of LMMs in terms of interpretability and generalization.

[Arxiv](https://arxiv.org/abs/2409.01560)