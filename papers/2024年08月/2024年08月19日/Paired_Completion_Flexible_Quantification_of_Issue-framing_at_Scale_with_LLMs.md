# Paired Completion 方法利用 LLM 实现大规模问题框架的灵活量化。

发布时间：2024年08月19日

`LLM应用` `社会科学` `政治学`

> Paired Completion: Flexible Quantification of Issue-framing at Scale with LLMs

# 摘要

> 在文本分析中，识别和量化问题框架——即对特定议题的不同视角——对社会科学、政治学、项目评估和政策分析等领域至关重要。然而，由于争议双方常共享相似的词汇，仅在表达风格上有所差异，这使得自动NLP技术难以准确捕捉。为此，我们研发并严格测试了新的问题框架检测技术，并在大规模文本数据集中进行叙事分析。我们创新性地利用生成式LLM的下一个词对数概率，展示了“配对完成”方法能在大规模语料库中高效且准确地识别问题框架，仅需少量示例。通过192次独立实验，我们对比了“配对完成”与传统NLP和LLM方法的性能，并进行了成本和偏差分析。我们的研究为实现大规模、高准确性和低偏差的文本问题框架分析提供了可行方案。

> Detecting and quantifying issue framing in textual discourse - the perspective one takes to a given topic (e.g. climate science vs. denialism, misogyny vs. gender equality) - is highly valuable to a range of end-users from social and political scientists to program evaluators and policy analysts. However, conceptual framing is notoriously challenging for automated natural language processing (NLP) methods since the words and phrases used by either `side' of an issue are often held in common, with only subtle stylistic flourishes separating their use. Here we develop and rigorously evaluate new detection methods for issue framing and narrative analysis within large text datasets. By introducing a novel application of next-token log probabilities derived from generative large language models (LLMs) we show that issue framing can be reliably and efficiently detected in large corpora with only a few examples of either perspective on a given issue, a method we call `paired completion'. Through 192 independent experiments over three novel, synthetic datasets, we evaluate paired completion against prompt-based LLM methods and labelled methods using traditional NLP and recent LLM contextual embeddings. We additionally conduct a cost-based analysis to mark out the feasible set of performant methods at production-level scales, and a model bias analysis. Together, our work demonstrates a feasible path to scalable, accurate and low-bias issue-framing in large corpora.

[Arxiv](https://arxiv.org/abs/2408.09742)