# CSS：大型语言模型不确定性量化中的对比语义相似性

发布时间：2024年06月05日

`LLM应用

理由：这篇论文主要探讨了如何利用CLIP（对比语言-图像预训练）模型来提取文本对的相似性特征，进而评估大型语言模型（LLMs）生成内容的不确定性，并应用于选择性自然语言生成（NLG）以增强LLMs的可信度。这种方法直接应用于LLMs的实际使用场景中，以提高其输出的可靠性，属于LLM的具体应用研究，而非理论探讨或Agent、RAG相关的研究。因此，将其归类为LLM应用是合适的。` `问答系统`

> CSS: Contrastive Semantic Similarity for Uncertainty Quantification of LLMs

# 摘要

> 尽管大型语言模型（LLMs）能力非凡，但何时信任其生成内容仍是一大挑战。近期研究利用传统自然语言推理（NLI）分类器评估LLMs输出的语义分散，通过NLI分类器的logits进行语义聚类以估算不确定性。然而，logits仅反映预测类别的概率，缺乏聚类所需的特征信息。相比之下，CLIP（对比语言-图像预训练）在提取图像-文本对特征及衡量相似性方面表现卓越。为此，我们提出基于CLIP的对比语义相似性模块，用以提取文本对的相似性特征，进而评估不确定性。此方法应用于选择性NLG，旨在识别并排除不可靠生成，增强LLMs的可信度。我们在多个问答数据集上对三个LLMs进行了详尽测试，并采用全面评估指标。实验结果表明，我们的方法在评估LLMs的可靠响应方面优于同类基线。相关代码已公开于\url{https://github.com/AoShuang92/css_uq_llms}。

> Despite the impressive capability of large language models (LLMs), knowing when to trust their generations remains an open challenge. The recent literature on uncertainty quantification of natural language generation (NLG) utilises a conventional natural language inference (NLI) classifier to measure the semantic dispersion of LLMs responses. These studies employ logits of NLI classifier for semantic clustering to estimate uncertainty. However, logits represent the probability of the predicted class and barely contain feature information for potential clustering. Alternatively, CLIP (Contrastive Language-Image Pre-training) performs impressively in extracting image-text pair features and measuring their similarity. To extend its usability, we propose Contrastive Semantic Similarity, the CLIP-based feature extraction module to obtain similarity features for measuring uncertainty for text pairs. We apply this method to selective NLG, which detects and rejects unreliable generations for better trustworthiness of LLMs. We conduct extensive experiments with three LLMs on several benchmark question-answering datasets with comprehensive evaluation metrics. Results show that our proposed method performs better in estimating reliable responses of LLMs than comparable baselines. Results show that our proposed method performs better in estimating reliable responses of LLMs than comparable baselines. The code are available at \url{https://github.com/AoShuang92/css_uq_llms}.

![CSS：大型语言模型不确定性量化中的对比语义相似性](../../../paper_images/2406.03158/x1.png)

![CSS：大型语言模型不确定性量化中的对比语义相似性](../../../paper_images/2406.03158/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03158)