# 借助弱监督之力，精炼语言模型的推理之智

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在推理能力提升方面的自我强化方法，特别是在减少人类干预的情况下。它提出了一种新的方法，通过监督微调（SFT）和迭代提升来增强LLMs的能力，而不依赖于大量的人工解释。此外，论文还推出了一个名为\textsc{PuzzleBen}的新基准数据集，用于研究如何利用较少的大规模数据来增强LLMs的推理力。这些内容更偏向于LLM的理论研究，因为它关注的是模型自身的改进方法和推理能力的理论探讨，而不是具体的应用场景或Agent的设计。因此，这篇论文应归类于LLM理论。` `人工智能推理`

> Optimizing Language Model's Reasoning Abilities with Weak Supervision

# 摘要

> 大型语言模型（LLMs）虽能熟练应对复杂查询，但过往研究多依赖于人类专家精心注释的数据集。这种对全监督注释的依赖，随着模型和数据需求的膨胀，带来了可扩展性的难题。为此，我们探索了在减少人类干预的情况下，提升LLMs推理能力的可能性。我们提出的自我强化方法，首先通过一小批注释问题对模型进行监督微调（SFT），随后通过比较SFT模型与原始模型在未标记问题上的回答差异，迭代提升LLMs。这种方法高效且不依赖于大量的人工解释。然而，现有的推理基准往往只提供标准答案或推理过程。鉴于此，我们推出了\textsc{PuzzleBen}，一个包含25,147个跨领域复杂问题、答案及人类推理过程的弱监督基准，其中特别包含了10,000个未注释问题，旨在探索如何利用较少的大规模数据来增强LLMs的推理力。实验结果凸显了\textsc{PuzzleBen}的重要性，并证明了我们的方法在未来研究中的潜力。我们的数据集和代码即将在\texttt{Anonymity Link}上公开。

> While Large Language Models (LLMs) have demonstrated proficiency in handling complex queries, much of the past work has depended on extensively annotated datasets by human experts. However, this reliance on fully-supervised annotations poses scalability challenges, particularly as models and data requirements grow. To mitigate this, we explore the potential of enhancing LLMs' reasoning abilities with minimal human supervision. In this work, we introduce self-reinforcement, which begins with Supervised Fine-Tuning (SFT) of the model using a small collection of annotated questions. Then it iteratively improves LLMs by learning from the differences in responses from the SFT and unfinetuned models on unlabeled questions. Our approach provides an efficient approach without relying heavily on extensive human-annotated explanations. However, current reasoning benchmarks typically only include golden-reference answers or rationales. Therefore, we present \textsc{PuzzleBen}, a weakly supervised benchmark that comprises 25,147 complex questions, answers, and human-generated rationales across various domains, such as brainteasers, puzzles, riddles, parajumbles, and critical reasoning tasks. A unique aspect of our dataset is the inclusion of 10,000 unannotated questions, enabling us to explore utilizing fewer supersized data to boost LLMs' inference capabilities. Our experiments underscore the significance of \textsc{PuzzleBen}, as well as the effectiveness of our methodology as a promising direction in future endeavors. Our dataset and code will be published soon on \texttt{Anonymity Link}.

[Arxiv](https://arxiv.org/abs/2405.04086)