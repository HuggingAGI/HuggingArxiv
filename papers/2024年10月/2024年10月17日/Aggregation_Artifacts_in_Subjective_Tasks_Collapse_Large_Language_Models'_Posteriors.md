# 主观任务中的聚合伪影使大型语言模型的后验概率崩溃

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Aggregation Artifacts in Subjective Tasks Collapse Large Language Models' Posteriors

# 摘要

> ICL 已成为 LLM 执行自然语言任务的主要方法，但其依赖任务先验而非学习任务的局限性在情感和道德等复杂领域尤为明显。我们探讨了数据集聚合是否导致注释伪影，并评估了后验偏差。结果显示，聚合是主观任务建模的混杂因素，建议关注个体建模。尽管如此，其他因素也影响 ICL 的表现。通过深入研究注释者标签，我们发现少数注释者能更好地与 LLM 对齐，并放大其观点。

> In-context Learning (ICL) has become the primary method for performing natural language tasks with Large Language Models (LLMs). The knowledge acquired during pre-training is crucial for this few-shot capability, providing the model with task priors. However, recent studies have shown that ICL predominantly relies on retrieving task priors rather than "learning" to perform tasks. This limitation is particularly evident in complex subjective domains such as emotion and morality, where priors significantly influence posterior predictions. In this work, we examine whether this is the result of the aggregation used in corresponding datasets, where trying to combine low-agreement, disparate annotations might lead to annotation artifacts that create detrimental noise in the prompt. Moreover, we evaluate the posterior bias towards certain annotators by grounding our study in appropriate, quantitative measures of LLM priors. Our results indicate that aggregation is a confounding factor in the modeling of subjective tasks, and advocate focusing on modeling individuals instead. However, aggregation does not explain the entire gap between ICL and the state of the art, meaning other factors in such tasks also account for the observed phenomena. Finally, by rigorously studying annotator-level labels, we find that it is possible for minority annotators to both better align with LLMs and have their perspectives further amplified.

[Arxiv](https://arxiv.org/abs/2410.13776)