# 本文旨在评估少样本学习在波兰语分类任务中的应用效果。

发布时间：2024年04月27日

`分类：LLM应用

这篇论文主要研究了针对波兰语的多任务分类基准，并通过对比不同的预训练模型和学习方法来评估它们在波兰语上的表现。论文中提到了多种预训练模型，如GPT-3.5、GPT-4、HerBERT-large、Mistral-7b、Llama-2-13b、Bielik-7b和Trurl-13b，这些都是大型语言模型（LLM）的应用实例。此外，论文还探讨了不同的学习方法，如微调、线性探测、SetFit和上下文学习（ICL），这些都是LLM在实际应用中的学习方法。因此，这篇论文可以归类为LLM应用。` `机器学习`

> Evaluation of Few-Shot Learning for Classification Tasks in the Polish Language

# 摘要

> 我们推出了一个针对波兰语的多任务分类基准，涵盖7种不同的分类任务。通过对比0样本和16样本的微调、线性探测、SetFit和上下文学习（ICL）方法，我们使用了一系列商业和开源的预训练模型进行实证研究。研究结果显示，ICL在性能上表现最佳，尤其是商业模型GPT-3.5和GPT-4表现尤为突出。尽管如此，即便是我们最佳的少量样本学习得分，与在完整训练集上微调的HerBERT-large模型相比，仍有14个百分点的差距。在所有技术中，SetFit紧随ICL之后，成为次优方法，而线性探测也表现不俗。相比之下，非线性头部微调的性能最差且波动最大。ICL的结果表明，对Mistral-7b或Llama-2-13b等模型进行持续的预训练，特别是在波兰语语料库上，能够带来性能提升，这一点从Bielik-7b和Trurl-13b的改进中得到了验证。为了推动波兰语少量样本学习的研究，我们还发布了为ICL量身定制的模板。

> We introduce a few-shot benchmark consisting of 7 different classification tasks native to the Polish language. We conducted an empirical comparison with 0 and 16 shots between fine-tuning, linear probing, SetFit, and in-context learning (ICL) using various pre-trained commercial and open-source models. Our findings reveal that ICL achieves the best performance, with commercial models like GPT-3.5 and GPT-4 attaining the best performance. However, there remains a significant 14 percentage points gap between our best few-shot learning score and the performance of HerBERT-large fine-tuned on the entire training dataset. Among the techniques, SetFit emerges as the second-best approach, closely followed by linear probing. We observed the worst and most unstable performance with non-linear head fine-tuning. Results for ICL indicate that continual pre-training of models like Mistral-7b or Llama-2-13b on Polish corpora is beneficial. This is confirmed by the improved performances of Bielik-7b and Trurl-13b, respectively. To further support experiments in few-shot learning for Polish, we are releasing handcrafted templates for the ICL.

[Arxiv](https://arxiv.org/abs/2404.17832)