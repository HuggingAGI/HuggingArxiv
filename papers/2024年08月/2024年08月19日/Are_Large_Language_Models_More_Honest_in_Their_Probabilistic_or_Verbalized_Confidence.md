# 大型语言模型在表达自信时，是通过概率性还是口头方式更显得诚实？

发布时间：2024年08月19日

`LLM理论` `人工智能`

> Are Large Language Models More Honest in Their Probabilistic or Verbalized Confidence?

# 摘要

> 大型语言模型（LLM）在问题超出其知识边界时易产生幻觉。理想的模型应能清晰界定其知识范围，正确作答或明智拒绝。当前研究多以生成词的概率或模型口头表达的信心来衡量其自我认知，却忽略了这两者间的差异与联系。本文深入分析并比较了LLM对其知识边界的概率感知与口头感知，探讨了它们的优劣及在不同频率问题下的表现，并评估了两者间的相关性。实验表明，概率感知虽更精确，但需领域验证集调整信心阈值；两者在处理低频问题时表现更佳；而LLM用自然语言准确表达内部信心则颇具挑战。

> Large language models (LLMs) have been found to produce hallucinations when the question exceeds their internal knowledge boundaries. A reliable model should have a clear perception of its knowledge boundaries, providing correct answers within its scope and refusing to answer when it lacks knowledge. Existing research on LLMs' perception of their knowledge boundaries typically uses either the probability of the generated tokens or the verbalized confidence as the model's confidence in its response. However, these studies overlook the differences and connections between the two. In this paper, we conduct a comprehensive analysis and comparison of LLMs' probabilistic perception and verbalized perception of their factual knowledge boundaries. First, we investigate the pros and cons of these two perceptions. Then, we study how they change under questions of varying frequencies. Finally, we measure the correlation between LLMs' probabilistic confidence and verbalized confidence. Experimental results show that 1) LLMs' probabilistic perception is generally more accurate than verbalized perception but requires an in-domain validation set to adjust the confidence threshold. 2) Both perceptions perform better on less frequent questions. 3) It is challenging for LLMs to accurately express their internal confidence in natural language.

[Arxiv](https://arxiv.org/abs/2408.09773)