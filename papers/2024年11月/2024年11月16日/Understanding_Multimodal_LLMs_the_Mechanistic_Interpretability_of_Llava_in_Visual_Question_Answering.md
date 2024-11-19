# 理解多模态 LLMs：Llava 在视觉问答中的机制可解释性

发布时间：2024年11月16日

`LLM理论` `多模态` `视觉问答`

> Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering

# 摘要

> 理解大型语言模型（LLMs）背后的机制对于设计更优的模型和策略意义重大。尽管近期研究为文本型 LLMs 的机制带来了宝贵的见解，但多模态大型语言模型（MLLMs）的机制仍有待深入探索。在本文中，我们运用机械可解释性方法剖析了首个 MLLM——Llava 中的视觉问答（VQA）机制。在颜色回答任务中，我们对 VQA 和文本问答（TQA）的机制进行了比较，发现：a）VQA 呈现出与 TQA 中所观察到的上下文学习机制相似的情况；b）将视觉嵌入投影至嵌入空间时，视觉特征具有显著的可解释性；c）在视觉指令调整过程中，Llava 增强了相应文本 LLMs Vicuna 的现有能力。基于这些发现，我们开发了一款可解释性工具，帮助用户和研究人员确定对最终预测至关重要的视觉位置，助力理解视觉幻觉。与现有的可解释性方法相比，我们的方法成果更快、更有效。代码：url{https://github.com/zepingyu0512/llava-mechanism}

> Understanding the mechanisms behind Large Language Models (LLMs) is crucial for designing improved models and strategies. While recent studies have yielded valuable insights into the mechanisms of textual LLMs, the mechanisms of Multi-modal Large Language Models (MLLMs) remain underexplored. In this paper, we apply mechanistic interpretability methods to analyze the visual question answering (VQA) mechanisms in the first MLLM, Llava. We compare the mechanisms between VQA and textual QA (TQA) in color answering tasks and find that: a) VQA exhibits a mechanism similar to the in-context learning mechanism observed in TQA; b) the visual features exhibit significant interpretability when projecting the visual embeddings into the embedding space; and c) Llava enhances the existing capabilities of the corresponding textual LLM Vicuna during visual instruction tuning. Based on these findings, we develop an interpretability tool to help users and researchers identify important visual locations for final predictions, aiding in the understanding of visual hallucination. Our method demonstrates faster and more effective results compared to existing interpretability approaches. Code: url{https://github.com/zepingyu0512/llava-mechanism}

[Arxiv](https://arxiv.org/abs/2411.10950)