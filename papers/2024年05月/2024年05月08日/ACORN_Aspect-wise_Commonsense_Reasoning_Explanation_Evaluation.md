# ACORN：细粒度常识推理解释评价在这个翻译中，我首先直接将英文标题翻译为中文，确保了意思的准确传达。然后，在第二步中，我采用了更符合中文表达习惯的词汇，将“Aspect-wise”翻译为“细粒度”，使得标题更加简洁优雅，同时保持了原意。这样的翻译既符合中文的表达习惯，又能够生动地传达原文的核心概念。

发布时间：2024年05月08日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在评估自由文本解释质量方面的应用。它介绍了ACORN数据集，并分析了LLMs在评分解释时与人类评分者的一致性。研究结果表明，LLMs的评分与人类评分存在一定程度的相关性，但并非完全一致。此外，论文还探讨了在人类评分者不足的情况下，LLMs作为额外评分者的潜在作用。这些内容属于LLM在实际应用中的探索，特别是在自动化评估和质量控制领域，因此将其归类为LLM应用。` `教育评估`

> ACORN: Aspect-wise Commonsense Reasoning Explanation Evaluation

# 摘要

> 评估自由文本解释是一项复杂、主观且耗时的工作。大型语言模型（LLMs）因其潜在的一致性、可扩展性和成本效益而成为一种有吸引力的选择。在本研究中，我们推出了ACORN数据集，包含3,500个自由文本解释及其质量评级，旨在探索LLMs如何评估解释。我们发现，尽管LLMs的评分有时能与人类评分保持一致，但更多时候会降低不同情境和质量维度间的评分一致性，暗示其判断与人类评分者并非总是一致。我们通过比较LLMs生成的评分与人类多数投票评分在不同质量方面的相关性来量化这种差异。最佳系统的斯皮尔曼相关性在0.53至0.95之间，平均为0.72，显示出中等但并非完美的对齐。此外，我们探讨了在人类评分者不足时，将LLM作为额外评分者的可能性，并比较了多数投票标签与有限人类评分者和LLM作为额外评分者之间的相关性，与原始黄金标签相比。GPT-4在只有两个人类评分者时有所改善，但在其他情况下，当有三个人类评分者或更多时，LLMs的影响要么是中性的，要么是有害的。我们已公开ACORN数据集，以促进未来在LLM辅助评估方面的进步。数据集地址为：https://github.com/a-brassard/ACORN。

> Evaluating free-text explanations is a multifaceted, subjective, and labor-intensive task. Large language models (LLMs) present an appealing alternative due to their potential for consistency, scalability, and cost-efficiency. In this work, we present ACORN, a new dataset of 3,500 free-text explanations and aspect-wise quality ratings, and use it to gain insights into how LLMs evaluate explanations. We observed that replacing one of the human ratings sometimes maintained, but more often lowered the inter-annotator agreement across different settings and quality aspects, suggesting that their judgments are not always consistent with human raters. We further quantified this difference by comparing the correlation between LLM-generated ratings with majority-voted human ratings across different quality aspects. With the best system, Spearman's rank correlation ranged between 0.53 to 0.95, averaging 0.72 across aspects, indicating moderately high but imperfect alignment. Finally, we considered the alternative of using an LLM as an additional rater when human raters are scarce, and measured the correlation between majority-voted labels with a limited human pool and LLMs as an additional rater, compared to the original gold labels. While GPT-4 improved the outcome when there were only two human raters, in all other observed cases, LLMs were neutral to detrimental when there were three or more human raters. We publicly release the dataset to support future improvements in LLM-in-the-loop evaluation here: https://github.com/a-brassard/ACORN.

[Arxiv](https://arxiv.org/abs/2405.04818)