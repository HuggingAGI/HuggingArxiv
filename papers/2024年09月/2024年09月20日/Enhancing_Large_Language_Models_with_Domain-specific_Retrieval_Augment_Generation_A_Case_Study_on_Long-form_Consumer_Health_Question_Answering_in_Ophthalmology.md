# 利用特定领域检索增强生成技术，提升大型语言模型在眼科长篇消费者健康问答中的表现。

发布时间：2024年09月20日

`RAG` `人工智能`

> Enhancing Large Language Models with Domain-specific Retrieval Augment Generation: A Case Study on Long-form Consumer Health Question Answering in Ophthalmology

# 摘要

> 尽管 LLM 在医学领域潜力巨大，但其生成的回答可能缺乏证据支持或基于虚幻信息。虽然 RAG 是解决此问题的热门方法，但在特定领域应用中的实施和评估却鲜有研究。我们构建了一个包含 70,000 份眼科文档的 RAG 系统，在推理时为 LLM 提供相关文档支持。在一项针对长篇健康问题的研究中，我们对比了 100 个问题在有无 RAG 情况下的回答，由 10 位医疗专家评估。评估涵盖证据的真实性、选择与排序、归属以及答案的准确性和完整性。未使用 RAG 的 LLM 提供了 252 个参考，其中 45.3% 为虚幻信息，34.1% 有小错误，20.6% 正确。而使用 RAG 的 LLM 准确率提升至 54.5%，错误率降至 18.8% 轻微幻觉和 26.7% 错误。RAG 检索的前 10 个文档中有 62.5% 被选为最佳参考，平均排名 4.9。RAG 还显著改善了证据归属（5 分制下从 1.85 提升至 2.49，P<0.001），尽管在准确性和完整性上略有下降。研究显示，LLM 在医学应用中常出现虚幻和错误证据，RAG 虽大幅减少此类问题，但仍需克服挑战。

> Despite the potential of Large Language Models (LLMs) in medicine, they may generate responses lacking supporting evidence or based on hallucinated evidence. While Retrieval Augment Generation (RAG) is popular to address this issue, few studies implemented and evaluated RAG in downstream domain-specific applications. We developed a RAG pipeline with 70,000 ophthalmology-specific documents that retrieve relevant documents to augment LLMs during inference time. In a case study on long-form consumer health questions, we systematically evaluated the responses including over 500 references of LLMs with and without RAG on 100 questions with 10 healthcare professionals. The evaluation focuses on factuality of evidence, selection and ranking of evidence, attribution of evidence, and answer accuracy and completeness. LLMs without RAG provided 252 references in total. Of which, 45.3% hallucinated, 34.1% consisted of minor errors, and 20.6% were correct. In contrast, LLMs with RAG significantly improved accuracy (54.5% being correct) and reduced error rates (18.8% with minor hallucinations and 26.7% with errors). 62.5% of the top 10 documents retrieved by RAG were selected as the top references in the LLM response, with an average ranking of 4.9. The use of RAG also improved evidence attribution (increasing from 1.85 to 2.49 on a 5-point scale, P<0.001), albeit with slight decreases in accuracy (from 3.52 to 3.23, P=0.03) and completeness (from 3.47 to 3.27, P=0.17). The results demonstrate that LLMs frequently exhibited hallucinated and erroneous evidence in the responses, raising concerns for downstream applications in the medical domain. RAG substantially reduced the proportion of such evidence but encountered challenges.

[Arxiv](https://arxiv.org/abs/2409.13902)