# 利用大型语言模型设计蛋白质：提升性能与对比研究

发布时间：2024年08月12日

`LLM应用` `生物学` `计算生物学`

> Design Proteins Using Large Language Models: Enhancements and Comparative Analyses

# 摘要

> 本文探讨了预训练大型语言模型（LLMs）在生成高质量蛋白质序列中的应用。我们采用Mistral-7B1、Llama-2-7B2、Llama-3-8B3和gemma-7B4等模型，利用仅含42,000个人类蛋白质序列的小数据集，重新训练模型以生成生物学上可行的蛋白质结构。研究表明，即使数据有限，这些模型在效率上与ProGen系列、ProtGPT2和ProLLaMA等专业模型相当。我们通过pLDDT、RMSD、TM-score和REU等标准指标进行性能验证，并承诺公开所有模型的训练版本，以促进计算生物学领域的透明度和合作。

> Pre-trained LLMs have demonstrated substantial capabilities across a range of conventional natural language processing (NLP) tasks, such as summarization and entity recognition. In this paper, we explore the application of LLMs in the generation of high-quality protein sequences. Specifically, we adopt a suite of pre-trained LLMs, including Mistral-7B1, Llama-2-7B2, Llama-3-8B3, and gemma-7B4, to produce valid protein sequences. All of these models are publicly available.5 Unlike previous work in this field, our approach utilizes a relatively small dataset comprising 42,000 distinct human protein sequences. We retrain these models to process protein-related data, ensuring the generation of biologically feasible protein structures. Our findings demonstrate that even with limited data, the adapted models exhibit efficiency comparable to established protein-focused models such as ProGen varieties, ProtGPT2, and ProLLaMA, which were trained on millions of protein sequences. To validate and quantify the performance of our models, we conduct comparative analyses employing standard metrics such as pLDDT, RMSD, TM-score, and REU. Furthermore, we commit to making the trained versions of all four models publicly available, fostering greater transparency and collaboration in the field of computational biology.

[Arxiv](https://arxiv.org/abs/2408.06396)