# 学习改写：广义 LLM 生成文本的识别

发布时间：2024年08月08日

`LLM应用` `网络安全` `人工智能`

> Learning to Rewrite: Generalized LLM-Generated Text Detection

# 摘要

> 大型语言模型（LLM）可能被滥用，用于大规模制造虚假信息。为了降低风险，检测这些模型生成的内容至关重要，但现有分类器在开放环境中表现不佳。研究发现，LLM 对自身生成的内容重写较少，这一特点可用于检测，且能适应新数据。然而，我们发现，在不同领域中，人类与 LLM 内容的编辑距离难以区分，导致检测失败。为此，我们训练 LLM 重写文本，使其对机器生成内容进行最小修改，对人类文本则进行更多修改，从而在各领域中形成可区分且通用的编辑距离。实验显示，我们的分类器在 AUROC 和 F1 分数上均优于现有技术，表明适当训练的 LLM 能有效识别机器生成文本。

> Large language models (LLMs) can be abused at scale to create non-factual content and spread disinformation. Detecting LLM-generated content is essential to mitigate these risks, but current classifiers often fail to generalize in open-world contexts. Prior work shows that LLMs tend to rewrite LLM-generated content less frequently, which can be used for detection and naturally generalizes to unforeseen data. However, we find that the rewriting edit distance between human and LLM content can be indistinguishable across domains, leading to detection failures. We propose training an LLM to rewrite input text, producing minimal edits for LLM-generated content and more edits for human-written text, deriving a distinguishable and generalizable edit distance difference across different domains. Experiments on text from 21 independent domains and three popular LLMs (e.g., GPT-4o, Gemini, and Llama-3) show that our classifier outperforms the state-of-the-art zero-shot classifier by up to 20.6% on AUROC score and the rewriting classifier by 9.2% on F1 score. Our work suggests that LLM can effectively detect machine-generated text if they are trained properly.

[Arxiv](https://arxiv.org/abs/2408.04237)