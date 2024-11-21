# 训练目标语言中存在数据约束的双语语言模型

发布时间：2024年11月19日

`LLM应用` `语言模型`

> Training Bilingual LMs with Data Constraints in the Targeted Language

# 摘要

> 大型语言模型依照当下的缩放定律，在海量的网络抓取数据上训练而成。英语因拥有大量优质的预训练数据，所以进展最为显著。但对于多数其他语言而言，如此高质量的预训练数据却难以获取。在此项工作中，我们致力于探究如何借助有高质量数据可用的辅助语言的数据，来提升数据受限目标语言中的预训练模型性能。我们通过衡量在数据丰富的辅助语言中训练与在目标语言中训练的性能差异来展开研究，探索翻译系统的益处，研究数据受限语言的模型缩放的局限性，并提出从辅助语言中进行数据上采样的新方法。我们的成果显示，对于相近语言，更强大的辅助数据集能带来性能提升，无需对模型或训练目标进行修改，特别是由于更具信息丰富度的英语预训练数据集的发展所带来的性能提升，能够延伸至数据有限的目标语言场景。

> Large language models are trained on massive scrapes of the web, as required by current scaling laws. Most progress is made for English, given its abundance of high-quality pretraining data. For most other languages, however, such high quality pretraining data is unavailable. In this work, we study how to boost pretrained model performance in a data constrained target language by enlisting data from an auxiliary language for which high quality data is available. We study this by quantifying the performance gap between training with data in a data-rich auxiliary language compared with training in the target language, exploring the benefits of translation systems, studying the limitations of model scaling for data constrained languages, and proposing new methods for upsampling data from the auxiliary language. Our results show that stronger auxiliary datasets result in performance gains without modification to the model or training objective for close languages, and, in particular, that performance gains due to the development of more information-rich English pretraining datasets can extend to targeted language settings with limited data.

[Arxiv](https://arxiv.org/abs/2411.12986)