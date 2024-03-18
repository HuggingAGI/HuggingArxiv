# KEBench——专为评估大型视觉-语言模型在知识编辑任务上的表现而设立的权威基准

发布时间：2024年03月12日

`Agent`

> KEBench: A Benchmark on Knowledge Editing for Large Vision-Language Models

> 当前，关于LVLM（大型视觉-语言模型）知识编辑的研究尚不多见。编辑LVLM时，关键在于如何在保证内容连贯性和相关性的同时，有效地融合图像和文本两种模态信息。现有的一项基准测试采用了三个评价指标（可靠性、局部性和通用性）来衡量LVLM的知识编辑性能，然而，在评估过程中所用生成图像的质量欠佳，且未能判断模型是否能够有效利用已编辑知识与其关联内容的关系。因此，我们运用不同的数据采集策略，构建了一个全新基准——$\textbf{KEBench}$，并引入了新的度量维度“可移植性”，以实现全面评测。通过利用多模态知识图谱的优势，我们的图像数据具备明确的实体指向性，这一特性有助于抽取与实体相关的知识，并生成编辑数据。我们针对五种LVLM实施了不同编辑方法的实验，并细致分析了这些方法对模型的具体影响。实验结果显示了各种方法的优势与不足，期待能为未来的相关研究提供有价值的启示。

> Currently, little research has been done on knowledge editing for Large Vision-Language Models (LVLMs). Editing LVLMs faces the challenge of effectively integrating diverse modalities (image and text) while ensuring coherent and contextually relevant modifications. An existing benchmark has three metrics (Reliability, Locality and Generality) to measure knowledge editing for LVLMs. However, the benchmark falls short in the quality of generated images used in evaluation and cannot assess whether models effectively utilize edited knowledge in relation to the associated content. We adopt different data collection methods to construct a new benchmark, $\textbf{KEBench}$, and extend new metric (Portability) for a comprehensive evaluation. Leveraging a multimodal knowledge graph, our image data exhibits clear directionality towards entities. This directional aspect can be further utilized to extract entity-related knowledge and form editing data. We conducted experiments of different editing methods on five LVLMs, and thoroughly analyze how these methods impact the models. The results reveal strengths and deficiencies of these methods and, hopefully, provide insights into potential avenues for future research.

[Arxiv](https://arxiv.org/abs/2403.07350)