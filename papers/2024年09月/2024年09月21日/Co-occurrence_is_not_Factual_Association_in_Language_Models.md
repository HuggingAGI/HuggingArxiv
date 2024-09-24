# 语言模型中的共现现象并不意味着事实上的关联。

发布时间：2024年09月21日

`LLM理论` `人工智能`

> Co-occurrence is not Factual Association in Language Models

# 摘要

> 预训练语言模型虽能编码大量知识并用于推理，但在有限文本演示中微调时，仍难以有效学习新事实。我们发现，这是因为模型更倾向于学习词共现而非真正的事实关联。我们区分了两种知识表示：共现统计编码于模型中间层，难以泛化至复杂推理；而事实关联则编码于较低层，适用于多种推理任务。基于此，我们提出两种策略：通过训练隐含事实关联的文本，迫使模型学习事实而非共现统计，显著提升新知识的泛化能力；同时，采用简单方法主动遗忘共现统计，解锁并增强事实关联的学习。实验证明，这些策略在合成与真实语料库上，均提升了微调知识在复杂推理场景中的泛化能力。

> Pretrained language models can encode a large amount of knowledge and utilize it for various reasoning tasks, yet they can still struggle to learn novel factual knowledge effectively from finetuning on limited textual demonstrations. In this work, we show that the reason for this deficiency is that language models are biased to learn word co-occurrence statistics instead of true factual associations. We identify the differences between two forms of knowledge representation in language models: knowledge in the form of co-occurrence statistics is encoded in the middle layers of the transformer model and does not generalize well to reasoning scenarios beyond simple question answering, while true factual associations are encoded in the lower layers and can be freely utilized in various reasoning tasks. Based on these observations, we propose two strategies to improve the learning of factual associations in language models. We show that training on text with implicit rather than explicit factual associations can force the model to learn factual associations instead of co-occurrence statistics, significantly improving the generalization of newly learned knowledge. We also propose a simple training method to actively forget the learned co-occurrence statistics, which unblocks and enhances the learning of factual associations when training on plain narrative text. On both synthetic and real-world corpora, the two proposed strategies improve the generalization of the knowledge learned during finetuning to reasoning scenarios such as indirect and multi-hop question answering.

[Arxiv](https://arxiv.org/abs/2409.14057)