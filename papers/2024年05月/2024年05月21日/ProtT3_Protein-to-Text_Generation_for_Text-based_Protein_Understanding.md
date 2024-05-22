# ProtT3：蛋白质至文本生成，助力基于文本的蛋白质理解

发布时间：2024年05月21日

`LLM应用

理由：这篇论文介绍了一个名为ProtT3的框架，该框架旨在通过集成蛋白质语言模型（PLM）和语言模型（LM）来提高对蛋白质文本描述的理解能力。这种集成是通过一个跨模态投影器（Q-Former）实现的，该投影器连接了两种模型的表示空间。论文的重点在于开发和评估一个具体的应用框架，用于蛋白质到文本的生成，这属于大型语言模型（LLM）的具体应用领域。因此，它适合归类为LLM应用。` `生物医学` `蛋白质研究`

> ProtT3: Protein-to-Text Generation for Text-based Protein Understanding

# 摘要

> 语言模型（LMs）在生物医学问答任务中展现了理解蛋白质文本描述的卓越能力，但在处理原始蛋白质数据，如氨基酸序列时，因缺乏相关预训练而表现不佳。相比之下，蛋白质语言模型（PLMs）能将蛋白质数据转化为高质量的表示，却难以处理文本。为此，我们推出了ProtT3框架，旨在通过文本理解蛋白质。ProtT3通过集成PLM作为蛋白质理解模块，使LM能够有效生成蛋白质到文本的内容。PLM与LM之间的协同作用得益于跨模态投影器（Q-Former），它连接了两种模型的表示空间。我们的研究不同于以往专注于蛋白质属性预测和检索的探索，而是深入研究了蛋白质到文本生成的领域。为了推动这一领域的研究，我们建立了包括蛋白质标注、问答和检索在内的蛋白质-文本建模任务的定量评估。实验结果显示，ProtT3大幅超越现有基准，消融研究也证实了其核心组件的高效性。项目代码已公开于https://github.com/acharkq/ProtT3。

> Language Models (LMs) excel in understanding textual descriptions of proteins, as evident in biomedical question-answering tasks. However, their capability falters with raw protein data, such as amino acid sequences, due to a deficit in pretraining on such data. Conversely, Protein Language Models (PLMs) can understand and convert protein data into high-quality representations, but struggle to process texts. To address their limitations, we introduce ProtT3, a framework for Protein-to-Text Generation for Text-based Protein Understanding. ProtT3 empowers an LM to understand protein sequences of amino acids by incorporating a PLM as its protein understanding module, enabling effective protein-to-text generation. This collaboration between PLM and LM is facilitated by a cross-modal projector (i.e., Q-Former) that bridges the modality gap between the PLM's representation space and the LM's input space. Unlike previous studies focusing on protein property prediction and protein-text retrieval, we delve into the largely unexplored field of protein-to-text generation. To facilitate comprehensive benchmarks and promote future research, we establish quantitative evaluations for protein-text modeling tasks, including protein captioning, protein question-answering, and protein-text retrieval. Our experiments show that ProtT3 substantially surpasses current baselines, with ablation studies further highlighting the efficacy of its core components. Our code is available at https://github.com/acharkq/ProtT3.

[Arxiv](https://arxiv.org/abs/2405.12564)