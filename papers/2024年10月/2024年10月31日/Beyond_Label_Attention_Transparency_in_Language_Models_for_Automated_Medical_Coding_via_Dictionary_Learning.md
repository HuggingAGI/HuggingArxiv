# 超越标签关注：借助字典学习提升语言模型在自动医疗编码中的透明度

发布时间：2024年10月31日

`LLM应用` `医疗编码`

> Beyond Label Attention: Transparency in Language Models for Automated Medical Coding via Dictionary Learning

# 摘要

> 医疗编码，也就是把非结构化临床文本转化为标准化医疗代码，是医疗保健领域关键却又耗时的一项工作。尽管大型语言模型（LLM）能够让编码流程自动化，提升这类任务的效率，然而可解释性对于维系患者的信任依旧极为重要。当下在医疗编码应用的可解释性方面所做的努力，很大程度上依赖于标签注意力机制，这往往会导致突出与ICD代码无关的多余标记。为推动医疗语言模型实现准确的可解释性，本文借助字典学习，它能够从叠加的密集语言模型嵌入中高效提取稀疏激活的表征。和常见的标签注意力机制相比，我们的模型通过构建一个可解释的字典，超越了标记层面的表征，强化了对每个ICD代码预测基于机制的解释，哪怕突出显示的标记在医学上不相关。我们证明，字典特征能够引导模型行为，阐释高达90%医学上不相关标记的隐藏含义，并且是人类能够理解的。

> Medical coding, the translation of unstructured clinical text into standardized medical codes, is a crucial but time-consuming healthcare practice. Though large language models (LLM) could automate the coding process and improve the efficiency of such tasks, interpretability remains paramount for maintaining patient trust. Current efforts in interpretability of medical coding applications rely heavily on label attention mechanisms, which often leads to the highlighting of extraneous tokens irrelevant to the ICD code. To facilitate accurate interpretability in medical language models, this paper leverages dictionary learning that can efficiently extract sparsely activated representations from dense language model embeddings in superposition. Compared with common label attention mechanisms, our model goes beyond token-level representations by building an interpretable dictionary which enhances the mechanistic-based explanations for each ICD code prediction, even when the highlighted tokens are medically irrelevant. We show that dictionary features can steer model behavior, elucidate the hidden meanings of upwards of 90% of medically irrelevant tokens, and are human interpretable.

[Arxiv](https://arxiv.org/abs/2411.00173)