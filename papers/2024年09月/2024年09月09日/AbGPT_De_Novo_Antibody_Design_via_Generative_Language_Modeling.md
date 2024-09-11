# AbGPT：利用生成语言模型实现全新抗体设计

发布时间：2024年09月09日

`LLM应用` `生物医药` `免疫学`

> AbGPT: De Novo Antibody Design via Generative Language Modeling

# 摘要

> 适应性免疫反应主要由 B 细胞受体 (BCR) 介导，因其多样性和抗原特异性，在病原体中和过程中至关重要。然而，从头设计 BCR 因其复杂结构和多样结合要求而颇具挑战。蛋白质语言模型 (PLM) 虽在上下文化及下游任务中表现卓越，但缺乏对整个蛋白质空间的全面理解，限制了其在抗体设计中的应用。为此，我们推出了抗体生成预训练变压器 (AbGPT)，通过微调基础 PLM，实现更精准的 BCR 序列设计。借助自定义生成与过滤流程，AbGPT 成功构建了包含 15,000 个高质量 BCR 序列的库，充分展现了对抗体库内变异与保守区域的理解。

> The adaptive immune response, largely mediated by B-cell receptors (BCRs), plays a crucial role for effective pathogen neutralization due to its diversity and antigen specificity. Designing BCRs de novo, or from scratch, has been challenging because of their complex structure and diverse binding requirements. Protein language models (PLMs) have shown remarkable performance in contextualizing and performing various downstream tasks without relying on structural information. However, these models often lack a comprehensive understanding of the entire protein space, which limits their application in antibody design. In this study, we introduce Antibody Generative Pretrained Transformer (AbGPT), a model fine-tuned from a foundational PLM to enable a more informed design of BCR sequences. Using a custom generation and filtering pipeline, AbGPT successfully generated a high-quality library of 15,000 BCR sequences, demonstrating a strong understanding of the intrinsic variability and conserved regions within the antibody repertoire.

[Arxiv](https://arxiv.org/abs/2409.06090)