# 借助半开放式问答探索大型语言模型的知识界限
发布时间：2024年05月23日

`知识图谱`
> Perception of Knowledge Boundary for Large Language Models through Semi-open-ended Question Answering
>
> 大型语言模型（LLMs）虽广泛用于知识探索，却常陷入幻觉的困境。LLM的知识边界（KB）是其事实理解的界限，一旦超越，幻觉便可能产生。目前研究多聚焦于有明确答案的封闭式问题，而对答案多样的半开放式问题（SoeQ）关注不足。这些SoeQ问题部分可答，部分模糊，而模糊答案正是知识探索的关键，却常超出LLMs的KB。本文通过挖掘更多模糊答案来探索LLMs的KB。我们首先利用LLM构建SoeQ并获取答案，但主流黑盒LLM的低概率模糊答案难以采样。为此，我们借助开源辅助模型LLaMA-2-13B来探索这些答案。通过计算答案的语义接近度来评估其概率，我们降低了高概率答案的生成，以促进更有效的答案生成。最终，我们通过RAG评估和LLM自我评估，识别出四种超出目标LLM KB的模糊答案。我们据此构建了GPT-4的KB感知数据集，发现GPT-4在SoeQ上表现不佳，且对其KB认识不足。而辅助模型LLaMA-2-13B在发现模糊答案方面表现出色。
>
> https://arxiv.org/abs/2405.14383


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14383](https://arxiv.org/abs/2405.14383)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886