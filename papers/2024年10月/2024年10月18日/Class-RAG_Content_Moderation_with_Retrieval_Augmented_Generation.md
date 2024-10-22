# Class-RAG：通过检索增强生成技术实现内容审核

发布时间：2024年10月18日

`RAG` `内容审核` `人工智能安全`

> Class-RAG: Content Moderation with Retrieval Augmented Generation

# 摘要

> 内容审核分类器对生成式AI的安全性至关重要。然而，安全与不安全内容间的细微差别常令人难以区分。随着技术广泛应用，持续微调模型以应对风险变得愈发困难且昂贵。为此，我们提出Class-RAG方法，通过动态更新检索库，实现即时风险缓解。与传统微调模型相比，Class-RAG更具灵活性与透明度，且在分类与抗攻击方面表现更佳。研究还表明，扩大检索库能有效提升审核性能，成本低廉。

> Robust content moderation classifiers are essential for the safety of Generative AI systems. Content moderation, or safety classification, is notoriously ambiguous: differences between safe and unsafe inputs are often extremely subtle, making it difficult for classifiers (and indeed, even humans) to properly distinguish violating vs. benign samples without further context or explanation. Furthermore, as these technologies are deployed across various applications and audiences, scaling risk discovery and mitigation through continuous model fine-tuning becomes increasingly challenging and costly. To address these challenges, we propose a Classification approach employing Retrieval-Augmented Generation (Class-RAG). Class-RAG extends the capability of its base LLM through access to a retrieval library which can be dynamically updated to enable semantic hotfixing for immediate, flexible risk mitigation. Compared to traditional fine-tuned models, Class-RAG demonstrates flexibility and transparency in decision-making. As evidenced by empirical studies, Class-RAG outperforms on classification and is more robust against adversarial attack. Besides, our findings suggest that Class-RAG performance scales with retrieval library size, indicating that increasing the library size is a viable and low-cost approach to improve content moderation.

[Arxiv](https://arxiv.org/abs/2410.14881)