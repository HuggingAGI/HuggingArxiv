# DYNA：专为变异致病性分析设计的疾病特异性语言模型

发布时间：2024年05月31日

`Agent

理由：该论文介绍了一种名为DYNA的技术，它通过孪生神经网络对基因组基础模型进行疾病特异性微调，以提升特定疾病环境下的变异效应预测能力。这种技术可以被视为一个智能代理（Agent），因为它能够针对特定任务（区分致病性与良性遗传变异）进行优化，并在临床遗传学领域中发挥作用。此外，DYNA的开发和应用涉及到对预训练模型的微调和特定任务的优化，这与Agent在特定环境中执行任务的概念相符。因此，将该论文归类为Agent是合适的。` `遗传学`

> DYNA: Disease-Specific Language Model for Variant Pathogenicity

# 摘要

> 在临床遗传学领域，区分致病性与良性遗传变异的分类仍是一大挑战。基因组基础模型的出现，通过弱监督或无监督训练提升了通用变异效应预测（VEP）的准确性，但这些VEP缺乏疾病特异性，限制了其在临床实践中的应用。为此，我们开发了DYNA：一种利用孪生神经网络对所有基因组基础模型进行疾病特异性微调的技术，旨在提升疾病特异性环境下的变异效应预测能力。我们在两个与疾病紧密相关的任务中测试了DYNA的效果。对于编码VEP，我们专注于多种心血管疾病，其中基因与疾病的关系（功能丧失与功能获得）是疾病特异性VEP的关键。对于非编码VEP，DYNA被应用于RNA剪接的关键转录后调控机制，这是临床VEP指南中最常见的非编码致病途径。在这两种情况下，DYNA都对预先训练的基因组基础模型在罕见变异集上进行了微调。DYNA微调的模型在罕见变异测试集上表现出色，并在ClinVAR的大型临床相关变异注释中得到了验证。因此，DYNA不仅在基因内泛化方面表现卓越，还能有效泛化到未见的遗传变异，对于疾病关联研究和临床应用具有极高的价值。

> Clinical variant classification of pathogenic versus benign genetic variants remains a challenge in clinical genetics. Recently, the proposition of genomic foundation models has improved the generic variant effect prediction (VEP) accuracy via weakly-supervised or unsupervised training. However, these VEPs are not disease-specific, limiting their adaptation at the point of care. To address this problem, we propose DYNA: Disease-specificity fine-tuning via a Siamese neural network broadly applicable to all genomic foundation models for more effective variant effect predictions in disease-specific contexts. We evaluate DYNA in two distinct disease-relevant tasks. For coding VEPs, we focus on various cardiovascular diseases, where gene-disease relationships of loss-of-function vs. gain-of-function dictate disease-specific VEP. For non-coding VEPs, we apply DYNA to an essential post-transcriptional regulatory axis of RNA splicing, the most common non-coding pathogenic mechanism in established clinical VEP guidelines. In both cases, DYNA fine-tunes various pre-trained genomic foundation models on small, rare variant sets. The DYNA fine-tuned models show superior performance in the held-out rare variant testing set and are further replicated in large, clinically-relevant variant annotations in ClinVAR. Thus, DYNA offers a potent disease-specific variant effect prediction method, excelling in intra-gene generalization and generalization to unseen genetic variants, making it particularly valuable for disease associations and clinical applicability.

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x1.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/input_genomic_foundation_model_v3.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/dyna_framework_v3.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x2.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x3.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x4.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x5.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x6.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x7.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x8.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x9.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x10.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x11.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x12.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x13.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x14.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x15.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x16.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x17.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x18.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x19.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x20.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x21.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x22.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x23.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x24.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x25.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x26.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x27.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x28.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x29.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x30.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x31.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x32.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x33.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x34.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x35.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/cm-esm2-auc.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/cm-esm2-pr.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/cm-esm2-ft-auc.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/cm-esm2-ft-pr.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/arm-esm2-auc.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/arm-esm2-pr.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/arm-esm2-ft-auc.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/arm-esm2-ft-pr.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x36.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x37.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x38.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x39.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x40.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x41.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x42.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x43.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x44.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x45.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x46.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x47.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x48.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x49.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x50.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x51.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x52.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x53.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x54.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x55.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x56.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x57.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x58.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x59.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x60.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x61.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x62.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x63.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x64.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x65.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x66.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x67.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x68.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x69.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x70.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x71.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x72.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x73.png)

![DYNA：专为变异致病性分析设计的疾病特异性语言模型](../../../paper_images/2406.00164/x74.png)

[Arxiv](https://arxiv.org/abs/2406.00164)