# 分子图表示学习：融合大型语言模型与领域专用小模型

发布时间：2024年08月19日

`LLM应用` `药物发现`

> Molecular Graph Representation Learning Integrating Large Language Models with Domain-specific Small Models

# 摘要

> 分子属性预测是药物发现的核心，近年来，预训练深度学习模型在此领域大放异彩。一些结合了生物学先验知识的方法表现尤为出色，但这些方法高度依赖专家知识，且获取和整合大量文献既耗时又成本高昂。大型语言模型（LLM）虽在通用知识处理上表现卓越，但在特定领域知识生成上有时不够精确。而特定领域的小模型（DSM）虽在领域知识上精准，却因模型规模和功能限制，难以进行全面的表示学习。为此，我们创新性地提出了MolGraph-LarDo框架，融合LLM与DSM的优势，通过两阶段提示策略提升领域知识的精确性，并运用多模态对齐方法，整合分子图与描述文本，优化分子表示的预训练。实验结果充分验证了该方法的有效性。

> Molecular property prediction is a crucial foundation for drug discovery. In recent years, pre-trained deep learning models have been widely applied to this task. Some approaches that incorporate prior biological domain knowledge into the pre-training framework have achieved impressive results. However, these methods heavily rely on biochemical experts, and retrieving and summarizing vast amounts of domain knowledge literature is both time-consuming and expensive. Large Language Models (LLMs) have demonstrated remarkable performance in understanding and efficiently providing general knowledge. Nevertheless, they occasionally exhibit hallucinations and lack precision in generating domain-specific knowledge. Conversely, Domain-specific Small Models (DSMs) possess rich domain knowledge and can accurately calculate molecular domain-related metrics. However, due to their limited model size and singular functionality, they lack the breadth of knowledge necessary for comprehensive representation learning. To leverage the advantages of both approaches in molecular property prediction, we propose a novel Molecular Graph representation learning framework that integrates Large language models and Domain-specific small models (MolGraph-LarDo). Technically, we design a two-stage prompt strategy where DSMs are introduced to calibrate the knowledge provided by LLMs, enhancing the accuracy of domain-specific information and thus enabling LLMs to generate more precise textual descriptions for molecular samples. Subsequently, we employ a multi-modal alignment method to coordinate various modalities, including molecular graphs and their corresponding descriptive texts, to guide the pre-training of molecular representations. Extensive experiments demonstrate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2408.10124)