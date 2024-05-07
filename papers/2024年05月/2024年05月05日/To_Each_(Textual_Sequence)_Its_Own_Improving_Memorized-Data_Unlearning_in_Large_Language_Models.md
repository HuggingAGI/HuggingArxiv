# 为每个文本序列量身定制：优化大型语言模型中的记忆数据忘却机制

发布时间：2024年05月05日

`LLM理论` `隐私保护`

> To Each (Textual Sequence) Its Own: Improving Memorized-Data Unlearning in Large Language Models

# 摘要

> 研究发现，大型语言模型（LLMs）在文本生成过程中会记忆并精确复现训练时的文本序列，这一现象是引发隐私及版权等相关问题的根源。为了解决这一问题，LLMs中的“去学习”过程需要设计新算法，以妥善处理记忆数据带来的副作用，同时保持模型的效用。我们提出了一种新的思路：在进行去学习时，应根据文本序列在LLM中的记忆力程度，采取不同的处理策略。我们引入了一种新的度量去学习质量的指标，并展示了一个对抗性攻击，证明缺少这种视角的现有顶尖算法在隐私保护方面存在不足。此外，我们还提出了两种新的去学习方法，分别基于梯度上升和任务算术。通过在一系列广泛的自然语言处理（NLP）任务上的全面性能评估，我们绘制了解决方案空间，找出了不同模型容量和忘却集大小下的最佳解决方案，并评估了这些新方法的优势。

> LLMs have been found to memorize training textual sequences and regurgitate verbatim said sequences during text generation time. This fact is known to be the cause of privacy and related (e.g., copyright) problems. Unlearning in LLMs then takes the form of devising new algorithms that will properly deal with these side-effects of memorized data, while not hurting the model's utility. We offer a fresh perspective towards this goal, namely, that each textual sequence to be forgotten should be treated differently when being unlearned based on its degree of memorization within the LLM. We contribute a new metric for measuring unlearning quality, an adversarial attack showing that SOTA algorithms lacking this perspective fail for privacy, and two new unlearning methods based on Gradient Ascent and Task Arithmetic, respectively. A comprehensive performance evaluation across an extensive suite of NLP tasks then mapped the solution space, identifying the best solutions under different scales in model capacities and forget set sizes and quantified the gains of the new approaches.

[Arxiv](https://arxiv.org/abs/2405.03097)