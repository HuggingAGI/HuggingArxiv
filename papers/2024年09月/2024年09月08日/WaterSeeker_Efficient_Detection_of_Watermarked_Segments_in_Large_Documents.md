# WaterSeeker：快速识别大文档中的水印片段

发布时间：2024年09月08日

`LLM应用` `网络安全` `人工智能`

> WaterSeeker: Efficient Detection of Watermarked Segments in Large Documents

# 摘要

> 水印算法在LLM中检测生成文本的准确性很高，但现有方法多关注完全水印与非水印文本的区分，忽视了LLM在大文档中仅生成小部分内容的实际场景。这种情况下，平衡检测性能与时间复杂性极具挑战。本文提出WaterSeeker，一种能在大量自然文本中高效检测并定位水印段的新方法。首先，它通过高效异常提取法初步定位可疑水印区，再进行局部遍历与全文检测以精确验证。理论与实验证明，WaterSeeker在检测准确性与计算效率间达到优越平衡，其定位能力还助力可解释AI检测系统的发展。此研究开创了水印段检测新方向，推动了更可靠的AI生成内容识别。

> Watermarking algorithms for large language models (LLMs) have attained high accuracy in detecting LLM-generated text. However, existing methods primarily focus on distinguishing fully watermarked text from non-watermarked text, overlooking real-world scenarios where LLMs generate only small sections within large documents. In this scenario, balancing time complexity and detection performance poses significant challenges. This paper presents WaterSeeker, a novel approach to efficiently detect and locate watermarked segments amid extensive natural text. It first applies an efficient anomaly extraction method to preliminarily locate suspicious watermarked regions. Following this, it conducts a local traversal and performs full-text detection for more precise verification. Theoretical analysis and experimental results demonstrate that WaterSeeker achieves a superior balance between detection accuracy and computational efficiency. Moreover, WaterSeeker's localization ability supports the development of interpretable AI detection systems. This work pioneers a new direction in watermarked segment detection, facilitating more reliable AI-generated content identification.

[Arxiv](https://arxiv.org/abs/2409.05112)