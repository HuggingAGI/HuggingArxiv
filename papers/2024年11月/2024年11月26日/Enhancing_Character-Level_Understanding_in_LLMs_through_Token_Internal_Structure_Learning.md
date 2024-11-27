# 借助令牌内部结构学习提升大型语言模型中的字符级理解能力

发布时间：2024年11月26日

`LLM应用` `中文拼写纠正`

> Enhancing Character-Level Understanding in LLMs through Token Internal Structure Learning

# 摘要

> 像字节对编码（BPE）和字节级 BPE（BBPE）这样的标记化技术，将文本分割成标记，大大提升了大型语言模型（LLMs）的计算效率和词汇表征稳定性。但这种分割常常会掩盖标记内部的字符结构和序列，致使模型在训练时无法充分学习这些复杂细节。所以，LLMs 难以领会标记内的字符构成和位置关系，尤其是在有限数据的下游任务中进行微调时。在本文里，我们提出了标记内部位置感知（TIPA）这一全新方法，通过利用标记器自身的词汇在反向字符预测任务上训练模型，增强了 LLMs 对内部标记结构的理解。该方法能让模型有效地学习和推广字符位置及内部结构。实验结果显示，用 TIPA 训练的 LLMs 在标记层面的字符位置预测上优于基线模型。另外，在应用于中文拼写纠正（CSC）的下游任务时，TIPA 不但加快了模型收敛速度，还显著提升了任务表现。

> Tokenization techniques such as Byte-Pair Encoding (BPE) and Byte-Level BPE (BBPE) have significantly improved the computational efficiency and vocabulary representation stability of large language models (LLMs) by segmenting text into tokens. However, this segmentation often obscures the internal character structures and sequences within tokens, preventing models from fully learning these intricate details during training. Consequently, LLMs struggle to comprehend the character compositions and positional relationships within tokens, especially when fine-tuned on downstream tasks with limited data. In this paper, we introduce Token Internal Position Awareness (TIPA), a novel approach that enhances LLMs' understanding of internal token structures by training them on reverse character prediction tasks using the tokenizer's own vocabulary. This method enables models to effectively learn and generalize character positions and internal structures. Experimental results demonstrate that LLMs trained with TIPA outperform baseline models in predicting character positions at the token level. Furthermore, when applied to the downstream task of Chinese Spelling Correction (CSC), TIPA not only accelerates model convergence but also significantly improves task performance.

[Arxiv](https://arxiv.org/abs/2411.17679)