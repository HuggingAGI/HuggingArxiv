# 视频海中寻针：构建一个可扩展的合成框架，旨在为视频多模态大型语言模型提供基准测试。

发布时间：2024年06月13日

`LLM应用

理由：这篇论文主要讨论了视频理解在多模态大型语言模型（MLLMs）中的应用，并提出了一种新的基准构建框架VideoNIAH，用于评估视频模型的性能。这涉及到实际应用中的技术和方法，因此属于LLM应用类别。` `视频理解` `基准测试`

> Needle In A Video Haystack: A Scalable Synthetic Framework for Benchmarking Video MLLMs

# 摘要

> 视频理解是多模态大型语言模型（MLLMs）发展的关键一步。为了深入探究视频理解能力，现有的视频基准通常需要精心挑选视频并耗费大量时间标注查询-响应对，以确保与视频内容匹配。这一过程既复杂又耗资源。为此，我们提出了VideoNIAH（视频中的针），一个通过合成视频生成的基准构建框架。VideoNIAH巧妙地在原始视频中插入无关的图像/文本“针”，以此分离测试视频内容与其查询-响应，仅从这些“针”生成标注，确保了视频来源的多样性和查询-响应的丰富性。此外，通过插入多个“针”，VideoNIAH严格测试了模型的时序理解能力。我们基于VideoNIAH创建了视频基准VNBench，涵盖检索、排序和计数等任务，有效评估了视频模型的细粒度理解能力和时空建模能力，并支持长上下文评估。我们还对近期以视频为中心的MLLMs进行了评估，发现尽管专有模型在某些方面优于开源模型，但所有模型在处理长距离依赖任务时仍有不足。VideoNIAH是一个简单而高度可扩展的基准构建框架，我们期待它能为未来的视频基准研究带来启发。相关代码和数据已公开于https://github.com/joez17/VideoNIAH。

> Video understanding is a crucial next step for multimodal large language models (MLLMs). To probe specific aspects of video understanding ability, existing video benchmarks typically require careful video selection based on the target capability, along with laborious annotation of query-response pairs to match the specific video content. This process is both challenging and resource-intensive. In this paper, we propose VideoNIAH (Video Needle In A Haystack), a benchmark construction framework through synthetic video generation. VideoNIAH decouples test video content from their query-responses by inserting unrelated image/text 'needles' into original videos. It generates annotations solely from these needles, ensuring diversity in video sources and a variety of query-responses. Additionally, by inserting multiple needles, VideoNIAH rigorously evaluates the temporal understanding capabilities of models. We utilized VideoNIAH to compile a video benchmark VNBench, including tasks such as retrieval, ordering, and counting. VNBench can efficiently evaluate the fine-grained understanding ability and spatio-temporal modeling ability of a video model, while also supporting the long-context evaluation. Additionally, we evaluated recent video-centric multimodal large language models (MLLMs), both open-source and proprietary, providing a comprehensive analysis. We found that although proprietary models have significant advantages over open-source models, all existing video models still perform poorly on long-distance dependency tasks. VideoNIAH is a simple yet highly scalable benchmark construction framework, and we believe it will inspire future video benchmark works. The code and data are available at https://github.com/joez17/VideoNIAH.

[Arxiv](https://arxiv.org/abs/2406.09367)