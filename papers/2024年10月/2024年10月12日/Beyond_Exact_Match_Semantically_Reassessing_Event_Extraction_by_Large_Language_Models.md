# 超越精确匹配：借助大型语言模型重新审视事件提取的语义层面

发布时间：2024年10月12日

`LLM应用` `人工智能`

> Beyond Exact Match: Semantically Reassessing Event Extraction by Large Language Models

# 摘要

> 事件抽取因其广泛应用而备受关注，但当前评估方法依赖于token级精确匹配，导致许多语义正确案例被误判。这使得模型评估结果与实际性能存在显著差异。为此，我们提出RAEE，一个基于语义而非token的自动评估框架。RAEE利用LLMs作为评估代理，结合思维链提示和自适应机制，实现对触发器和参数的精确率和召回率的可解释和自适应评估。实验表明，RAEE与人类评估高度一致，且在重新评估14个模型（包括先进LLMs）后，发现精确匹配显著低估了模型性能，尤其是LLMs的能力。RAEE的细粒度分析揭示了值得深入研究的现象。RAEE评估工具包即将公开发布。

> Event extraction has gained extensive research attention due to its broad range of applications. However, the current mainstream evaluation method for event extraction relies on token-level exact match, which misjudges numerous semantic-level correct cases. This reliance leads to a significant discrepancy between the evaluated performance of models under exact match criteria and their real performance. To address this problem, we propose RAEE, an automatic evaluation framework that accurately assesses event extraction results at semantic-level instead of token-level. Specifically, RAEE leverages Large Language Models (LLMs) as automatic evaluation agents, incorporating chain-of-thought prompting and an adaptive mechanism to achieve interpretable and adaptive evaluations for precision and recall of triggers and arguments. Extensive experimental results demonstrate that: (1) RAEE achieves a very high correlation with the human average; (2) after reassessing 14 models, including advanced LLMs, on 10 datasets, there is a significant performance gap between exact match and RAEE. The exact match evaluation significantly underestimates the performance of existing event extraction models, particularly underestimating the capabilities of LLMs; (3) fine-grained analysis under RAEE evaluation reveals insightful phenomena worth further exploration. The evaluation toolkit of our proposed RAEE will be publicly released.

[Arxiv](https://arxiv.org/abs/2410.09418)