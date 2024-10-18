# 在数据稀缺的情况下，REFINE 通过嵌入模型的融合微调，实现了检索能力的增强。

发布时间：2024年10月16日

`RAG` `问答系统`

> REFINE on Scarce Data: Retrieval Enhancement through Fine-Tuning via Model Fusion of Embedding Models

# 摘要

> RAG 管道常用于问答任务，依赖预训练嵌入模型从向量存储中检索相关文档。然而，若检索的上下文不准确，LLM 生成的答案可能出错或产生幻觉。尽管预训练嵌入模型有所进步，但适应新领域仍具挑战。微调虽是潜在方案，但行业中常缺乏微调数据。为此，我们提出 REFINE 技术，通过生成合成数据并结合模型融合方法，微调嵌入以提升新领域检索性能，同时保持域外能力。实验结果显示，即使标准微调结合数据增强技术，也优于普通预训练模型。而结合模型融合，该方法在 TOURISM 数据集上召回率提升 5.76%，SQUAD 和 RAG-12000 分别提升 6.58% 和 0.32%。

> Retrieval augmented generation (RAG) pipelines are commonly used in tasks such as question-answering (QA), relying on retrieving relevant documents from a vector store computed using a pretrained embedding model. However, if the retrieved context is inaccurate, the answers generated using the large language model (LLM) may contain errors or hallucinations. Although pretrained embedding models have advanced, adapting them to new domains remains challenging. Fine-tuning is a potential solution, but industry settings often lack the necessary fine-tuning data. To address these challenges, we propose REFINE, a novel technique that generates synthetic data from available documents and then uses a model fusion approach to fine-tune embeddings for improved retrieval performance in new domains, while preserving out-of-domain capability. We conducted experiments on the two public datasets: SQUAD and RAG-12000 and a proprietary TOURISM dataset. Results demonstrate that even the standard fine-tuning with the proposed data augmentation technique outperforms the vanilla pretrained model. Furthermore, when combined with model fusion, the proposed approach achieves superior performance, with a 5.76% improvement in recall on the TOURISM dataset, and 6.58 % and 0.32% enhancement on SQUAD and RAG-12000 respectively.

[Arxiv](https://arxiv.org/abs/2410.12890)