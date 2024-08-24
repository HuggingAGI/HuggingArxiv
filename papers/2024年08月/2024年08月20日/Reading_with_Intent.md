# 有目的地阅读

发布时间：2024年08月20日

`RAG` `人工智能`

> Reading with Intent

# 摘要

> RAG系统通过整合外部信息源，如维基百科和开放互联网，来提升知识语言模型的能力。然而，这些系统在处理人类交流的复杂性，尤其是讽刺，方面遇到了挑战。本文通过生成讽刺段落并测试其对RAG系统性能的影响，引入了一个提示系统来增强模型对讽刺的理解和响应生成能力，并通过消融研究验证了方法的有效性，显著提升了RAG系统处理讽刺内容的能力。

> Retrieval augmented generation (RAG) systems augment how knowledge language models are by integrating external information sources such as Wikipedia, internal documents, scientific papers, or the open internet. RAG systems that rely on the open internet as their knowledge source have to contend with the complexities of human-generated content. Human communication extends much deeper than just the words rendered as text. Intent, tonality, and connotation can all change the meaning of what is being conveyed. Recent real-world deployments of RAG systems have shown some difficulty in understanding these nuances of human communication. One significant challenge for these systems lies in processing sarcasm. Though the Large Language Models (LLMs) that make up the backbone of these RAG systems are able to detect sarcasm, they currently do not always use these detections for the subsequent processing of text. To address these issues, in this paper, we synthetically generate sarcastic passages from Natural Question's Wikipedia retrieval corpus. We then test the impact of these passages on the performance of both the retriever and reader portion of the RAG pipeline. We introduce a prompting system designed to enhance the model's ability to interpret and generate responses in the presence of sarcasm, thus improving overall system performance. Finally, we conduct ablation studies to validate the effectiveness of our approach, demonstrating improvements in handling sarcastic content within RAG systems.

[Arxiv](https://arxiv.org/abs/2408.11189)