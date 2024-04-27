# Boter：一种引导式的知识选择与问答方法，专为基于知识的 VQA（视觉问答）而设计。

发布时间：2024年04月22日

`LLM应用` `可视化问答` `人工智能`

> Boter: Bootstrapping Knowledge Selection and Question Answering for Knowledge-based VQA

# 摘要

> 基于知识的可视化问答（VQA）任务要求模型整合外部信息以回答视觉内容的问题。传统“检索-生成”范式的方法虽表现不俗，但存在不足：它们依赖独立检索器，仅基于查询与知识嵌入的相似性获取信息，忽略了知识文档是否真正有助于问题解答；同时，将图像信息转换为文本后进行检索和回答，可能无法全面捕捉图像的全部信息。为克服这些限制，我们设计了Boter框架，它通过利用多模态大型语言模型（MLLM）的多模态感知能力，优化了知识选择和问答过程。该框架包含选择器和回答器两个模块，均由MLLM初始化，并通过简洁的循环高效微调：选择器筛选出检索到的知识文档中的关键信息，回答器据此预测答案；基于回答器的预测结果和弱监督标签，为关键知识文档生成伪标签，进一步微调选择器以精选关键知识；如此循环。此框架在开放领域知识型VQA基准测试OK-VQA上显著提升了基线模型的性能，达到了62.83%的先进准确率。

> Knowledge-based Visual Question Answering (VQA) requires models to incorporate external knowledge to respond to questions about visual content. Previous methods mostly follow the "retrieve and generate" paradigm. Initially, they utilize a pre-trained retriever to fetch relevant knowledge documents, subsequently employing them to generate answers. While these methods have demonstrated commendable performance in the task, they possess limitations: (1) they employ an independent retriever to acquire knowledge solely based on the similarity between the query and knowledge embeddings, without assessing whether the knowledge document is truly conducive to helping answer the question; (2) they convert the image into text and then conduct retrieval and answering in natural language space, which may not ensure comprehensive acquisition of all image information. To address these limitations, we propose Boter, a novel framework designed to bootstrap knowledge selection and question answering by leveraging the robust multimodal perception capabilities of the Multimodal Large Language Model (MLLM). The framework consists of two modules: Selector and Answerer, where both are initialized by the MLLM and parameter-efficiently finetuned in a simple cycle: find key knowledge in the retrieved knowledge documents using the Selector, and then use them to finetune the Answerer to predict answers; obtain the pseudo-labels of key knowledge documents based on the predictions of the Answerer and weak supervision labels, and then finetune the Selector to select key knowledge; repeat. Our framework significantly enhances the performance of the baseline on the challenging open-domain Knowledge-based VQA benchmark, OK-VQA, achieving a state-of-the-art accuracy of 62.83%.

![Boter：一种引导式的知识选择与问答方法，专为基于知识的 VQA（视觉问答）而设计。](../../../paper_images/2404.13947/x1.png)

![Boter：一种引导式的知识选择与问答方法，专为基于知识的 VQA（视觉问答）而设计。](../../../paper_images/2404.13947/x2.png)

![Boter：一种引导式的知识选择与问答方法，专为基于知识的 VQA（视觉问答）而设计。](../../../paper_images/2404.13947/x3.png)

[Arxiv](https://arxiv.org/abs/2404.13947)