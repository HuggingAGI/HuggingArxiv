# PatentEdits：把专利新颖性表述为文本蕴含

发布时间：2024年11月20日

`LLM应用`

> PatentEdits: Framing Patent Novelty as Textual Entailment

# 摘要

> 一项专利要想获得美国专利局（USPTO）的授权，必须具备新颖性和非显而易见性。倘若不然，美国的专利审查员就会援引先前的成果，也就是现有技术，来否定其新颖性，并给出非最终驳回。预测鉴于现有技术，发明的哪些权利要求应当变更，这是保障发明权利的关键步骤，然而此前却未曾作为可学习的任务加以研究。在本项工作中，我们引入了 PatentEdits 数据集，其中涵盖 105K 个成功修订从而克服新颖性异议的实例。我们设计算法对编辑进行逐句标注，接着探究大型语言模型（LLMs）对这些编辑的预测效果。我们表明，评估所引用的参考文献与草案句子之间的文本蕴含关系，对于预测哪些发明权利要求相对于现有技术保持不变或者具有新颖性，效果尤为显著。

> A patent must be deemed novel and non-obvious in order to be granted by the US Patent Office (USPTO). If it is not, a US patent examiner will cite the prior work, or prior art, that invalidates the novelty and issue a non-final rejection. Predicting what claims of the invention should change given the prior art is an essential and crucial step in securing invention rights, yet has not been studied before as a learnable task. In this work we introduce the PatentEdits dataset, which contains 105K examples of successful revisions that overcome objections to novelty. We design algorithms to label edits sentence by sentence, then establish how well these edits can be predicted with large language models (LLMs). We demonstrate that evaluating textual entailment between cited references and draft sentences is especially effective in predicting which inventive claims remained unchanged or are novel in relation to prior art.

[Arxiv](https://arxiv.org/abs/2411.13477)