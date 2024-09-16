# 探索信息检索的新天地：调查创新评估技术与文档分割方法的比较

发布时间：2024年09月12日

`RAG` `信息检索`

> Exploring Information Retrieval Landscapes: An Investigation of a Novel Evaluation Techniques and Comparative Document Splitting Methods

# 摘要

> RAG 系统在信息检索中的表现深受文档特征影响。教科书的结构、文章的简洁、小说的复杂，均需独特检索策略。研究发现，Recursive Character Splitter 在保持上下文完整性上优于 Token-based Splitter。新评估技术利用开源模型生成问题-答案对数据集，模拟真实场景，提升测试效率与指标可靠性。采用 SequenceMatcher、BLEU、METEOR 和 BERT Score 等加权评分，精准评估系统。此法为 RAG 系统精确度评估立下新标，未来研究将聚焦于优化块与重叠大小，提升检索效率与准确性。

> The performance of Retrieval-Augmented Generation (RAG) systems in information retrieval is significantly influenced by the characteristics of the documents being processed. In this study, the structured nature of textbooks, the conciseness of articles, and the narrative complexity of novels are shown to require distinct retrieval strategies. A comparative evaluation of multiple document-splitting methods reveals that the Recursive Character Splitter outperforms the Token-based Splitter in preserving contextual integrity. A novel evaluation technique is introduced, utilizing an open-source model to generate a comprehensive dataset of question-and-answer pairs, simulating realistic retrieval scenarios to enhance testing efficiency and metric reliability. The evaluation employs weighted scoring metrics, including SequenceMatcher, BLEU, METEOR, and BERT Score, to assess the system's accuracy and relevance. This approach establishes a refined standard for evaluating the precision of RAG systems, with future research focusing on optimizing chunk and overlap sizes to improve retrieval accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2409.08479)