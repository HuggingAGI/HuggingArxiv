# [本研究致力于设计针对少量示例选择的有效度量标准，以期提升模型在有限数据下的学习与泛化能力。](https://arxiv.org/abs/2403.03861)

发布时间：2024年03月06日

`LLM应用`

> Designing Informative Metrics for Few-Shot Example Selection

> 预训练语言模型在面对精心设计的例子时，展现出了惊人的少量示例学习才能，但挑选“最优”例子仍是一个待解难题。我们为此提出一种适用于序列标注任务的基于复杂度的提示选择策略。无需额外训练专用模型来筛选例子，该策略通过特定指标衡量并匹配测试句子与示例间的句法语义复杂度，实现二者对齐。我们采用句子级和词级双重度量方式确保示例与目标（测试）句子的复杂度相适应。实验证明，此方法能让 PLMs 发挥更大潜能，不仅在少量样本命名实体识别任务中达到最新技术水平，还在 CoNLL2003 数据集中使 GPT-4 的 F1 分数提升了5%；即便是小规模如 GPT-j-6B 的模型，也获得了最高达28.85点（F1/Acc.）的重大突破。

> Pretrained language models (PLMs) have shown remarkable few-shot learning capabilities when provided with properly formatted examples. However, selecting the "best" examples remains an open challenge. We propose a complexity-based prompt selection approach for sequence tagging tasks. This approach avoids the training of a dedicated model for selection of examples, and instead uses certain metrics to align the syntactico-semantic complexity of test sentences and examples. We use both sentence- and word-level metrics to match the complexity of examples to the (test) sentence being considered. Our results demonstrate that our approach extracts greater performance from PLMs: it achieves state-of-the-art performance on few-shot NER, achieving a 5% absolute improvement in F1 score on the CoNLL2003 dataset for GPT-4. We also see large gains of upto 28.85 points (F1/Acc.) in smaller models like GPT-j-6B.

[Arxiv](https://arxiv.org/abs/2403.03861)