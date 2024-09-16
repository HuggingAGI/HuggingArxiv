# 提炼单语与跨语境的词表示

发布时间：2024年09月13日

`LLM理论` `机器学习`

> Distilling Monolingual and Crosslingual Word-in-Context Representations

# 摘要

> 本研究提出了一种从预训练掩码语言模型中提取上下文词义表示的方法，适用于单语和跨语言场景。与传统方法不同，我们的方法无需人工注释语料库或更新模型参数，这在实际应用中尤为实用。我们通过自注意力机制组合预训练模型的不同隐藏层输出，训练基于自编码器的模型，仅需自动生成语料库。实验结果显示，在单语任务中，我们的方法在上下文感知词汇语义任务中表现优异，且在 STS 估计中超越了以往研究。跨语言任务的结果则表明，该方法显著提升了多语言预训练模型的跨语言词表示能力。

> In this study, we propose a method that distils representations of word meaning in context from a pre-trained masked language model in both monolingual and crosslingual settings. Word representations are the basis for context-aware lexical semantics and unsupervised semantic textual similarity (STS) estimation. Different from existing approaches, our method does not require human-annotated corpora nor updates of the parameters of the pre-trained model. The latter feature is appealing for practical scenarios where the off-the-shelf pre-trained model is a common asset among different applications. Specifically, our method learns to combine the outputs of different hidden layers of the pre-trained model using self-attention. Our auto-encoder based training only requires an automatically generated corpus. To evaluate the performance of the proposed approach, we performed extensive experiments using various benchmark tasks. The results on the monolingual tasks confirmed that our representations exhibited a competitive performance compared to that of the previous study for the context-aware lexical semantic tasks and outperformed it for STS estimation. The results of the crosslingual tasks revealed that the proposed method largely improved crosslingual word representations of multilingual pre-trained models.

[Arxiv](https://arxiv.org/abs/2409.08719)