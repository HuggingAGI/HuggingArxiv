# 利用小型语言模型集成提升上下文学习效果

发布时间：2024年10月29日

`LLM应用`

> Improving In-Context Learning with Small Language Model Ensembles

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了非凡的能力，然而在特定领域任务方面的表现仍有局限。尽管诸如检索增强生成和微调之类的方法能应对此问题，可它们需要大量资源。上下文学习（ICL）是一种经济高效的替代方式，却难以企及先进方法的精准度。我们推出了集成超级 ICL 这一创新方法，它借助多个微调的小型语言模型（SLMs）的专长来强化 ICL。集成超级 ICL 在若干自然语言理解的基准测试中斩获了最前沿（SoTA）的成果。另外，我们在医疗领域的标注任务中对其加以测试，利用在通用语言任务上微调的现成 SLMs 彰显了其实用性，在大规模数据标注里达成了比所有基线更优的精度。最后，我们开展了消融研究和敏感性分析，以阐释集成超级 ICL 的内在机制。我们的研究顺应了 LLMs 对高效领域专业化方法与日俱增的需求，为从业者提供了一种既实惠又有效的途径。

> Large language models (LLMs) have shown impressive capabilities across various tasks, but their performance on domain-specific tasks remains limited. While methods like retrieval augmented generation and fine-tuning can help to address this, they require significant resources. In-context learning (ICL) is a cheap and efficient alternative but cannot match the accuracies of advanced methods. We present Ensemble SuperICL, a novel approach that enhances ICL by leveraging the expertise of multiple fine-tuned small language models (SLMs). Ensemble SuperICL achieves state of the art (SoTA) results on several natural language understanding benchmarks. Additionally, we test it on a medical-domain labelling task and showcase its practicality by using off-the-shelf SLMs fine-tuned on a general language task, achieving superior accuracy in large-scale data labelling compared to all baselines. Finally, we conduct an ablation study and sensitivity analyses to elucidate the underlying mechanism of Ensemble SuperICL. Our research contributes to the growing demand for efficient domain specialisation methods in LLMs, offering a cheap and effective method for practitioners.

[Arxiv](https://arxiv.org/abs/2410.21868)