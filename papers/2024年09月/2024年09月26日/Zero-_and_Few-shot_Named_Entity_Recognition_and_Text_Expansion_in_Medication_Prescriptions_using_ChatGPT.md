# 利用 ChatGPT 在药物处方中实现零-shot 和少-shot 的命名实体识别与文本扩展

发布时间：2024年09月26日

`LLM应用`

> Zero- and Few-shot Named Entity Recognition and Text Expansion in Medication Prescriptions using ChatGPT

# 摘要

> 药物处方常以自由文本形式出现，混合了两种语言、本地品牌名称及各种独特格式和缩写。大型语言模型（LLM）在生成文本方面表现出色。我们利用 ChatGPT 3.5 自动整理和扩展出院总结中的药物信息，使其更易解读。通过命名实体识别（NER）和文本扩展（EX）技术，结合零-shot 和少-shot 提示策略，我们对 100 条药物声明进行了手动注释。NER 性能通过严格和部分匹配评估，EX 任务则由两位专家评估语义等价性。结果显示，NER 最佳提示的平均 F1 分数为 0.94，EX 少-shot 提示的平均 F1 分数为 0.87。研究表明，ChatGPT 在处理自由文本药物信息时表现优异，少-shot 方法有效避免了系统幻觉，确保了药物数据处理的准确性。

> Introduction: Medication prescriptions are often in free text and include a mix of two languages, local brand names, and a wide range of idiosyncratic formats and abbreviations. Large language models (LLMs) have shown promising ability to generate text in response to input prompts. We use ChatGPT 3.5 to automatically structure and expand medication statements in discharge summaries and thus make them easier to interpret for people and machines. Methods: Named-entity Recognition (NER) and Text Expansion (EX) are used in a zero- and few-shot setting with different prompt strategies. 100 medication statements were manually annotated and curated. NER performance was measured by using strict and partial matching. For the task EX, two experts interpreted the results by assessing semantic equivalence between original and expanded statements. The model performance was measured by precision, recall, and F1 score. Results: For NER, the best-performing prompt reached an average F1 score of 0.94 in the test set. For EX, the few-shot prompt showed superior performance among other prompts, with an average F1 score of 0.87. Conclusion: Our study demonstrates good performance for NER and EX tasks in free-text medication statements using ChatGPT. Compared to a zero-shot baseline, a few-shot approach prevented the system from hallucinating, which would be unacceptable when processing safety-relevant medication data.

[Arxiv](https://arxiv.org/abs/2409.17683)