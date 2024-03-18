# DEEP-ICL：致力于为语言模型的上下文学习注入更多定义性知识的专家系统

发布时间：2024年03月07日

`LLM应用`

> DEEP-ICL: Definition-Enriched Experts for Language Model In-Context Learning

> 长久以来，业界普遍认为LLMs中的庞大参数量是推动ICL能力的关键，只需借助针对特定任务的演示就能大幅提升效果。然而，我们提出了一项名为DEEP-ICL的新颖任务定义强化专家集成技术，以挑战这一传统观点。DEEP-ICL独辟蹊径，能够从现有演示中提炼出清晰的任务定义，并通过学习针对性任务实例生成回应。我们坚持认为，ICL性能的提升并非直接受益于模型规模的扩大，而更关键在于对任务定义的理解以及在任务指导下进行学习的过程。基于这一理念，DEEP-ICL巧妙地整合了两个各有分工的3B模型（一个负责推导任务定义，另一个专注于学习任务演示），其性能表现堪比LLaMA2-13B。另外，DEEP-ICL框架通过突破预训练序列长度限制，支持无限量的演示输入，成功超越了常规ICL方法。因此，DEEP-ICL为我们展示了一种全新的、更为高效的少量样本学习路径，进一步拓宽了ICL的传统边界。

> It has long been assumed that the sheer number of parameters in large language models (LLMs) drives in-context learning (ICL) capabilities, enabling remarkable performance improvements by leveraging task-specific demonstrations. Challenging this hypothesis, we introduce DEEP-ICL, a novel task Definition Enriched ExPert Ensembling methodology for ICL. DEEP-ICL explicitly extracts task definitions from given demonstrations and generates responses through learning task-specific examples. We argue that improvement from ICL does not directly rely on model size, but essentially stems from understanding task definitions and task-guided learning. Inspired by this, DEEP-ICL combines two 3B models with distinct roles (one for concluding task definitions and the other for learning task demonstrations) and achieves comparable performance to LLaMA2-13B. Furthermore, our framework outperforms conventional ICL by overcoming pretraining sequence length limitations, by supporting unlimited demonstrations. We contend that DEEP-ICL presents a novel alternative for achieving efficient few-shot learning, extending beyond the conventional ICL.

[Arxiv](https://arxiv.org/abs/2403.04233)