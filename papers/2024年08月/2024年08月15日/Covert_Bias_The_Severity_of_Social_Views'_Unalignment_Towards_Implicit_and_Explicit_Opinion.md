# 隐蔽偏见：社会观点在隐性与显性意见间的不一致之严重性

发布时间：2024年08月15日

`LLM理论` `社会科学` `人工智能`

> Covert Bias: The Severity of Social Views' Unalignment Towards Implicit and Explicit Opinion

# 摘要

> 尽管偏见识别方法多样，但隐含语言对大型模型偏见放大的影响仍鲜为人知。我们通过两个下游任务，利用社会群体的隐含与显性知识，评估了偏见的严重性。首先，在极端偏见情境中进行压力测试。随后，考察LLM如何应对冲突观点下的隐含与显性意见。研究发现，LLM在识别隐含与显性意见时存在性能差异，更偏向于显性反对意见。与偏见一致的模型通过不确定性表达更为谨慎，而未对齐模型则需通过不确定性标记提升决断性，特别是在高度主观的社会话题上。

> While various approaches have recently been studied for bias identification, little is known about how implicit language that does not explicitly convey a viewpoint affects bias amplification in large language models.To examine the severity of bias toward a view, we evaluated the performance of two downstream tasks where the implicit and explicit knowledge of social groups were used. First, we present a stress test evaluation by using a biased model in edge cases of excessive bias scenarios. Then, we evaluate how LLMs calibrate linguistically in response to both implicit and explicit opinions when they are aligned with conflicting viewpoints. Our findings reveal a discrepancy in LLM performance in identifying implicit and explicit opinions, with a general tendency of bias toward explicit opinions of opposing stances. Moreover, the bias-aligned models generate more cautious responses using uncertainty phrases compared to the unaligned (zero-shot) base models. The direct, incautious responses of the unaligned models suggest a need for further refinement of decisiveness by incorporating uncertainty markers to enhance their reliability, especially on socially nuanced topics with high subjectivity.

[Arxiv](https://arxiv.org/abs/2408.08212)