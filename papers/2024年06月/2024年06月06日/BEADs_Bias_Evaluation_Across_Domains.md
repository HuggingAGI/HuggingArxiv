# 跨域偏差评估：BEADs

发布时间：2024年06月06日

`LLM应用

理由：这篇论文主要关注大型语言模型（LLMs）在处理偏见问题上的应用，通过引入跨领域偏见评估（BEADs）数据集来识别和减轻模型偏见。论文讨论了如何通过微调模型来减少偏见，同时保持模型的知识储备，这直接涉及到LLMs的实际应用和改进。因此，这篇论文属于LLM应用类别。` `数据集构建`

> BEADs: Bias Evaluation Across Domains

# 摘要

> 大型语言模型（LLMs）的进步，虽然极大地推动了自然语言处理（NLP）应用的发展，但也可能无意中传播了训练数据中的偏见。针对这一挑战，我们推出了跨领域偏见评估（BEADs）数据集，专为包括文本分类、偏见实体识别、偏见量化及良性语言生成在内的多种NLP任务设计。BEADs通过AI辅助标注与专家审核相结合，确保了标注的可靠性，有效弥补了传统数据集在偏见评估上的不足。实证研究表明，BEADs不仅有助于识别和减轻模型偏见，而且经过其微调的小模型在偏见分类上甚至超越了LLMs。尽管如此，模型对特定群体的偏见仍未完全消除。通过使用良性语言数据对LLMs进行微调，我们既能减少偏见，又能保持模型的知识储备。这些发现凸显了全面偏见评估的必要性，并指出了针对性微调在减少LLMs偏见方面的潜力。我们已在https://huggingface.co/datasets/shainar/BEADs公开BEADs数据集，供研究使用。注意：本文包含可能引起不适的内容。

> Recent improvements in large language models (LLMs) have significantly enhanced natural language processing (NLP) applications. However, these models can also inherit and perpetuate biases from their training data. Addressing this issue is crucial, yet many existing datasets do not offer evaluation across diverse NLP tasks. To tackle this, we introduce the Bias Evaluations Across Domains (BEADs) dataset, designed to support a wide range of NLP tasks, including text classification, bias entity recognition, bias quantification, and benign language generation. BEADs uses AI-driven annotation combined with experts' verification to provide reliable labels. This method overcomes the limitations of existing datasets that typically depend on crowd-sourcing, expert-only annotations with limited bias evaluations, or unverified AI labeling. Our empirical analysis shows that BEADs is effective in detecting and reducing biases across different language models, with smaller models fine-tuned on BEADs often outperforming LLMs in bias classification tasks. However, these models may still exhibit biases towards certain demographics. Fine-tuning LLMs with our benign language data also reduces biases while preserving the models' knowledge. Our findings highlight the importance of comprehensive bias evaluation and the potential of targeted fine-tuning for reducing the bias of LLMs. We are making BEADs publicly available at https://huggingface.co/datasets/shainar/BEAD
  Warning: This paper contains examples that may be considered offensive.

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/x1.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/multitask-arxiv.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/llama2-7b_bias_distribution.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/mistral2-7b_bias_distribution.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/x2.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/heatmap_sentiment_counts_per_aspect.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/readability_scores_correlation_heatmap.png)

![跨域偏差评估：BEADs](../../../paper_images/2406.04220/demo_counts.png)

[Arxiv](https://arxiv.org/abs/2406.04220)