# 借助弱监督之力，精炼语言模型的推理之智

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在推理能力提升方面的自我强化方法，特别是在减少对人类专家注释数据集依赖的情况下。它提出了一种新的方法，通过监督微调（SFT）和比较模型回答差异来迭代提升模型性能，并且引入了新的弱监督基准数据集\textsc{PuzzleBen}。这些研究内容更偏向于LLM的理论发展和方法论创新，因此归类为LLM理论。` `人工智能`

> Optimizing Language Model's Reasoning Abilities with Weak Supervision

# 摘要

> 大型语言模型（LLMs）在处理复杂查询方面表现出色，但以往的研究多依赖于人类专家注释的详尽数据集。这种对完全监督注释的依赖限制了模型的可扩展性，尤其是在数据和模型需求日益增长，这一问题愈发凸显。为此，我们探索了在最小化人类干预的情况下提升LLMs推理能力的可能性。我们提出的自我强化方法，首先通过一小批注释问题对模型进行监督微调（SFT），随后通过比较SFT模型与原始模型在未标记问题上的回答差异，迭代提升LLMs的性能。这种方法高效且不依赖于大量的人工注释。然而，现有的推理基准通常仅包含标准答案或推理过程，为此我们推出了\textsc{PuzzleBen}，一个包含25,147个跨多个领域（如脑力挑战、谜题、谜语、段落重组和批判性思维任务）的复杂问题、答案及人类推理的弱监督基准。特别地，我们的数据集还包含了10,000个未注释问题，这使我们能够研究如何利用较少的大数据来增强LLMs的推理能力。实验结果表明，\textsc{PuzzleBen}及其方法在未来的研究中具有重要意义和应用前景。我们将在不久的将来在\texttt{Anonymity Link}上发布数据集和代码。

> While Large Language Models (LLMs) have demonstrated proficiency in handling complex queries, much of the past work has depended on extensively annotated datasets by human experts. However, this reliance on fully-supervised annotations poses scalability challenges, particularly as models and data requirements grow. To mitigate this, we explore the potential of enhancing LLMs' reasoning abilities with minimal human supervision. In this work, we introduce self-reinforcement, which begins with Supervised Fine-Tuning (SFT) of the model using a small collection of annotated questions. Then it iteratively improves LLMs by learning from the differences in responses from the SFT and unfinetuned models on unlabeled questions. Our approach provides an efficient approach without relying heavily on extensive human-annotated explanations. However, current reasoning benchmarks typically only include golden-reference answers or rationales. Therefore, we present \textsc{PuzzleBen}, a weakly supervised benchmark that comprises 25,147 complex questions, answers, and human-generated rationales across various domains, such as brainteasers, puzzles, riddles, parajumbles, and critical reasoning tasks. A unique aspect of our dataset is the inclusion of 10,000 unannotated questions, enabling us to explore utilizing fewer supersized data to boost LLMs' inference capabilities. Our experiments underscore the significance of \textsc{PuzzleBen}, as well as the effectiveness of our methodology as a promising direction in future endeavors. Our dataset and code will be published soon on \texttt{Anonymity Link}.

[Arxiv](https://arxiv.org/abs/2405.04086)