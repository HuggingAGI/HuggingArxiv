# 本文旨在评估少样本学习在波兰语分类任务中的应用效果。

发布时间：2024年04月27日

`分类：LLM应用` `机器学习`

> Evaluation of Few-Shot Learning for Classification Tasks in the Polish Language

# 摘要

> 本研究提出了一个包含7项特定于波兰语的分类任务的少样本基准测试。我们对微调、线性探测、SetFit和上下文学习（ICL）等不同方法进行了实证比较，涉及0到16个样本点，并采用了多种预训练的商业和开源模型。研究发现ICL在性能上独占鳌头，尤其是商业模型GPT-3.5和GPT-4表现最为出色。尽管如此，即便是我们最佳的少样本学习得分，与在完整训练集上进行微调的HerBERT-large模型相比，仍有14个百分点的差距。在所有技术中，SetFit紧随ICL之后，成为次佳选择，而线性探测也表现不俗。相比之下，非线性头部微调的表现最差，且波动较大。ICL的结果显示，对Mistral-7b或Llama-2-13b等模型在波兰语文本上的持续预训练能够带来益处，这一点从Bielik-7b和Trurl-13b的提升性能中得到了验证。为了进一步推动波兰语少样本学习的实验研究，我们发布了为ICL精心设计的模板。

> We introduce a few-shot benchmark consisting of 7 different classification tasks native to the Polish language. We conducted an empirical comparison with 0 and 16 shots between fine-tuning, linear probing, SetFit, and in-context learning (ICL) using various pre-trained commercial and open-source models. Our findings reveal that ICL achieves the best performance, with commercial models like GPT-3.5 and GPT-4 attaining the best performance. However, there remains a significant 14 percentage points gap between our best few-shot learning score and the performance of HerBERT-large fine-tuned on the entire training dataset. Among the techniques, SetFit emerges as the second-best approach, closely followed by linear probing. We observed the worst and most unstable performance with non-linear head fine-tuning. Results for ICL indicate that continual pre-training of models like Mistral-7b or Llama-2-13b on Polish corpora is beneficial. This is confirmed by the improved performances of Bielik-7b and Trurl-13b, respectively. To further support experiments in few-shot learning for Polish, we are releasing handcrafted templates for the ICL.

[Arxiv](https://arxiv.org/abs/2404.17832)