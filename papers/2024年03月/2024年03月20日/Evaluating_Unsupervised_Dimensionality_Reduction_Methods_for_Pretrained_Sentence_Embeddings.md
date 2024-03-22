# 本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。

发布时间：2024年03月20日

`LLM应用`

> Evaluating Unsupervised Dimensionality Reduction Methods for Pretrained Sentence Embeddings

> PLM产生的句子嵌入凭借其在众多下游应用中的卓越表现而备受NLP界青睐，但面对内存或计算力有限的设备处理大量句子时，其高维度特性却成为挑战。为此，我们探讨了采用无监督降维方法来压缩PLM生成的句子嵌入维度。实验揭示，PCA等简洁算法可有效将句子嵌入维度削减约一半，且在多个下游任务中几乎不损失性能；更有趣的是，在特定任务中，对部分PLM生成的句子嵌入进一步降维后，其性能竟优于原始高维版本。

> Sentence embeddings produced by Pretrained Language Models (PLMs) have received wide attention from the NLP community due to their superior performance when representing texts in numerous downstream applications. However, the high dimensionality of the sentence embeddings produced by PLMs is problematic when representing large numbers of sentences in memory- or compute-constrained devices. As a solution, we evaluate unsupervised dimensionality reduction methods to reduce the dimensionality of sentence embeddings produced by PLMs. Our experimental results show that simple methods such as Principal Component Analysis (PCA) can reduce the dimensionality of sentence embeddings by almost $50\%$, without incurring a significant loss in performance in multiple downstream tasks. Surprisingly, reducing the dimensionality further improves performance over the original high-dimensional versions for the sentence embeddings produced by some PLMs in some tasks.

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/x1.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/x2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/x3.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/x4.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/x5.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/x6.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/trans_stsb-bert-base.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/trans_stsb-bert-large.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/trans_all-mpnet-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/trans_STSB_SimCSE.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/in_stsb-bert-base.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/in_stsb-bert-large.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/in_all-mpnet-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/in_STSB_SimCSE.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_trans_all-mpnet-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_trans_msmarco-roberta-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_trans_paraphrase-xlm-r-multilingual-v1.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_trans_SimCSE.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_in_all-mpnet-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_in_msmarco-roberta-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_in_paraphrase-xlm-r-multilingual-v1.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/TREC_in_SimCSE.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_trans_all-mpnet-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_trans_msmarco-roberta-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_trans_paraphrase-xlm-r-multilingual-v1.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_trans_SimCSE.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_in_all-mpnet-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_in_msmarco-roberta-base-v2.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_in_paraphrase-xlm-r-multilingual-v1.jpg)

![本研究致力于评估预训练句子嵌入在无监督维度降低方法中的表现，旨在探索这些方法对提升句子表示效果的影响。](../../../paper_images/2403.14001/SICKE_in_SimCSE.jpg)

[Arxiv](https://arxiv.org/abs/2403.14001)