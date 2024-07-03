# 本研究探讨了基于大型语言模型的排行榜生成中，如何进行有效的上下文选择。

发布时间：2024年06月06日

`LLM应用` `人工智能` `学术研究`

> Effective Context Selection in LLM-based Leaderboard Generation: An Empirical Study

# 摘要

> 本文深入研究了上下文选择如何影响 LLM 在生成 AI 研究排行榜的效率，这一任务涉及从学术文章中提取关键四元组。我们通过将此挑战转化为文本生成任务，并利用 FLAN-T5 进行指令微调，提出了一种创新方法，该方法在适应新进展方面超越了传统 NLI 方法，无需预设分类。实验结果显示，精心选择的上下文能显著提升 LLM 的准确性并减少错误信息，为高效生成可靠的 AI 排行榜开辟了新路径。这一研究不仅提升了排行榜生成的技术水平，也为解决 LLM 信息提取中的常见问题提供了新思路。

> This paper explores the impact of context selection on the efficiency of Large Language Models (LLMs) in generating Artificial Intelligence (AI) research leaderboards, a task defined as the extraction of (Task, Dataset, Metric, Score) quadruples from scholarly articles. By framing this challenge as a text generation objective and employing instruction finetuning with the FLAN-T5 collection, we introduce a novel method that surpasses traditional Natural Language Inference (NLI) approaches in adapting to new developments without a predefined taxonomy. Through experimentation with three distinct context types of varying selectivity and length, our study demonstrates the importance of effective context selection in enhancing LLM accuracy and reducing hallucinations, providing a new pathway for the reliable and efficient generation of AI leaderboards. This contribution not only advances the state of the art in leaderboard generation but also sheds light on strategies to mitigate common challenges in LLM-based information extraction.

[Arxiv](https://arxiv.org/abs/2407.02409)