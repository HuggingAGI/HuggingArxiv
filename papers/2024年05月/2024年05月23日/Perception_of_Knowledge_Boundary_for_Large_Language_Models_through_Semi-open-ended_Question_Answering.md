# 借助半开放式问答探索大型语言模型的知识界限

发布时间：2024年05月23日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在处理半开放式问题（SoeQ）时的知识边界（KB）问题，特别是如何通过辅助模型来探索和评估模糊答案，以及如何构建数据集来评估LLMs的知识边界。这些研究内容涉及LLMs的理论理解和性能评估，因此属于LLM理论分类。` `知识探索`

> Perception of Knowledge Boundary for Large Language Models through Semi-open-ended Question Answering

# 摘要

> 大型语言模型（LLMs）虽广泛用于知识探索，却常陷入幻觉的困境。LLM的知识边界（KB）是其事实理解的界限，一旦超越，幻觉便可能产生。目前研究多聚焦于有明确答案的封闭式问题，而对答案多样的半开放式问题（SoeQ）关注不足。这些SoeQ问题部分可答，部分模糊，而模糊答案正是知识探索的关键，却常超出LLMs的KB。本文通过挖掘更多模糊答案来探索LLMs的KB。我们首先利用LLM构建SoeQ并获取答案，但主流黑盒LLM的低概率模糊答案难以采样。为此，我们借助开源辅助模型LLaMA-2-13B来探索这些答案。通过计算答案的语义接近度来评估其概率，我们降低了高概率答案的生成，以促进更有效的答案生成。最终，我们通过RAG评估和LLM自我评估，识别出四种超出目标LLM KB的模糊答案。我们据此构建了GPT-4的KB感知数据集，发现GPT-4在SoeQ上表现不佳，且对其KB认识不足。而辅助模型LLaMA-2-13B在发现模糊答案方面表现出色。

> Large Language Models (LLMs) are widely used for knowledge-seeking yet suffer from hallucinations. The knowledge boundary (KB) of an LLM limits its factual understanding, beyond which it may begin to hallucinate. Investigating the perception of LLMs' KB is crucial for detecting hallucinations and LLMs' reliable generation. Current studies perceive LLMs' KB on questions with a concrete answer (close-ended questions) while paying limited attention to semi-open-ended questions (SoeQ) that correspond to many potential answers. Some researchers achieve it by judging whether the question is answerable or not. However, this paradigm is unsuitable for SoeQ, which are usually partially answerable, containing both answerable and ambiguous (unanswerable) answers. Ambiguous answers are essential for knowledge-seeking, but they may go beyond the KB of LLMs. In this paper, we perceive the LLMs' KB with SoeQ by discovering more ambiguous answers. First, we apply an LLM-based approach to construct SoeQ and obtain answers from a target LLM. Unfortunately, the output probabilities of mainstream black-box LLMs are inaccessible to sample for low-probability ambiguous answers. Therefore, we apply an open-sourced auxiliary model to explore ambiguous answers for the target LLM. We calculate the nearest semantic representation for existing answers to estimate their probabilities, with which we reduce the generation probability of high-probability answers to achieve a more effective generation. Finally, we compare the results from the RAG-based evaluation and LLM self-evaluation to categorize four types of ambiguous answers that are beyond the KB of the target LLM. Following our method, we construct a dataset to perceive the KB for GPT-4. We find that GPT-4 performs poorly on SoeQ and is often unaware of its KB. Besides, our auxiliary model, LLaMA-2-13B, is effective in discovering more ambiguous answers.

[Arxiv](https://arxiv.org/abs/2405.14383)