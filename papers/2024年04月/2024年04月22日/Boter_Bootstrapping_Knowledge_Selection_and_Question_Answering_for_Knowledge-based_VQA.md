# Boter：通过引导启动提升基于知识的视觉问答中的知识选择与问题回答。

发布时间：2024年04月22日

`分类：LLM应用` `视觉问答` `人工智能`

> Boter: Bootstrapping Knowledge Selection and Question Answering for Knowledge-based VQA

# 摘要

> 知识驱动的视觉问答（VQA）需要模型整合外部信息，以回应关于视觉内容的询问。传统“检索后生成”的方法虽然表现出色，但存在不足：一是仅依靠查询与知识嵌入的相似性来独立检索知识，忽略了知识文档是否真正有助于回答问题；二是将图像信息转换为文本后进行检索和回答，可能无法全面捕捉图像的全部信息。为此，我们设计了Boter框架，它通过利用多模态大型语言模型（MLLM）的先进感知能力，优化了知识选择和问题回答的流程。该框架包括选择器和回答器两个模块，均由MLLM初始化，并通过简洁的循环进行高效微调：首先，使用选择器从检索到的文档中筛选关键知识；接着，利用这些知识微调回答器以预测答案；然后，根据回答器的预测结果和弱监督标签，为关键知识文档生成伪标签，进而微调选择器以更精准地选择知识；如此循环。在难度较高的开放领域知识驱动VQA基准测试OK-VQA中，Boter显著提升了性能，达到了62.83%的先进准确率。

> Knowledge-based Visual Question Answering (VQA) requires models to incorporate external knowledge to respond to questions about visual content. Previous methods mostly follow the "retrieve and generate" paradigm. Initially, they utilize a pre-trained retriever to fetch relevant knowledge documents, subsequently employing them to generate answers. While these methods have demonstrated commendable performance in the task, they possess limitations: (1) they employ an independent retriever to acquire knowledge solely based on the similarity between the query and knowledge embeddings, without assessing whether the knowledge document is truly conducive to helping answer the question; (2) they convert the image into text and then conduct retrieval and answering in natural language space, which may not ensure comprehensive acquisition of all image information. To address these limitations, we propose Boter, a novel framework designed to bootstrap knowledge selection and question answering by leveraging the robust multimodal perception capabilities of the Multimodal Large Language Model (MLLM). The framework consists of two modules: Selector and Answerer, where both are initialized by the MLLM and parameter-efficiently finetuned in a simple cycle: find key knowledge in the retrieved knowledge documents using the Selector, and then use them to finetune the Answerer to predict answers; obtain the pseudo-labels of key knowledge documents based on the predictions of the Answerer and weak supervision labels, and then finetune the Selector to select key knowledge; repeat. Our framework significantly enhances the performance of the baseline on the challenging open-domain Knowledge-based VQA benchmark, OK-VQA, achieving a state-of-the-art accuracy of 62.83%.

![Boter：通过引导启动提升基于知识的视觉问答中的知识选择与问题回答。](../../../paper_images/2404.13947/x1.png)

![Boter：通过引导启动提升基于知识的视觉问答中的知识选择与问题回答。](../../../paper_images/2404.13947/x2.png)

![Boter：通过引导启动提升基于知识的视觉问答中的知识选择与问题回答。](../../../paper_images/2404.13947/x3.png)

[Arxiv](https://arxiv.org/abs/2404.13947)