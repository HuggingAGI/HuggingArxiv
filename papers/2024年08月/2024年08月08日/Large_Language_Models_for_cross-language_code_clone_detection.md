# 利用大型语言模型进行跨语言代码克隆检测

发布时间：2024年08月08日

`LLM应用` `软件工程` `机器学习`

> Large Language Models for cross-language code clone detection

# 摘要

> 现代软件开发中多语言的融合，使得跨语言代码克隆检测备受软件工程界瞩目。众多研究纷纷涌现，各展其才。受近年来机器学习，尤其是大型语言模型（LLMs）在多任务处理上的显著成就所启发，本文再次聚焦跨语言代码克隆检测。我们深入探索了四款LLMs与八种提示在跨语言代码克隆识别中的表现。同时，我们评估了一款预训练嵌入模型，以检验其生成的代码表示在区分克隆与非克隆对中的效能。两项研究均基于XLCoST与CodeNet两大跨语言数据集展开。结果表明，LLMs在简单编程示例上可达到高达0.98的F1分数，但在复杂编程挑战面前表现欠佳，且在跨语言环境中对代码克隆的理解未必透彻。我们发现，通过嵌入模型将不同编程语言的代码片段映射至同一表示空间，能训练出一款基本分类器，其在XLCoST与CodeNet上的表现分别超越所有LLMs约2和24个百分点。这表明，尽管LLMs潜力巨大，但嵌入模型所提供的嵌入表示，仍是实现跨语言代码克隆检测顶尖性能的关键所在。

> With the involvement of multiple programming languages in modern software development, cross-lingual code clone detection has gained traction with the software engineering community. Numerous studies have explored this topic, proposing various promising approaches. Inspired by the significant advances in machine learning in recent years, particularly Large Language Models (LLMs), which have demonstrated their ability to tackle various tasks, this paper revisits cross-lingual code clone detection.
  We investigate the capabilities of four (04) LLMs and eight (08) prompts for the identification of cross-lingual code clones. Additionally, we evaluate a pre-trained embedding model to assess the effectiveness of the generated representations for classifying clone and non-clone pairs. Both studies (based on LLMs and Embedding models) are evaluated using two widely used cross-lingual datasets, XLCoST and CodeNet. Our results show that LLMs can achieve high F1 scores, up to 0.98, for straightforward programming examples (e.g., from XLCoST). However, they not only perform less well on programs associated with complex programming challenges but also do not necessarily understand the meaning of code clones in a cross-lingual setting. We show that embedding models used to represent code fragments from different programming languages in the same representation space enable the training of a basic classifier that outperforms all LLMs by ~2 and ~24 percentage points on the XLCoST and CodeNet datasets, respectively. This finding suggests that, despite the apparent capabilities of LLMs, embeddings provided by embedding models offer suitable representations to achieve state-of-the-art performance in cross-lingual code clone detection.

[Arxiv](https://arxiv.org/abs/2408.04430)