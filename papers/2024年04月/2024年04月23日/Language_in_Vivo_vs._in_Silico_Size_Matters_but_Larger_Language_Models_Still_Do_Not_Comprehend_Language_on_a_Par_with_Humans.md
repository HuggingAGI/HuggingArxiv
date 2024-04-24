# 活体语言与模拟语言：规模至关重要，然而即便是更庞大的语言模型，其对语言的理解也未能与人类相提并论。

发布时间：2024年04月23日

`分类：LLM理论` `机器学习`

> Language in Vivo vs. in Silico: Size Matters but Larger Language Models Still Do Not Comprehend Language on a Par with Humans

# 摘要

> 掌握语言的边界对于大型语言模型（LLMs）成为自然语言的理论模型至关重要。在某些语言任务上，LLMs的表现在数量和质量上都与人类有所不同，但目前尚不清楚这些差异是否能够通过扩大模型规模来弥补。本研究探讨了模型规模扩展的关键影响，即模型尺寸的增加是否能够消除人类与模型之间的差异。我们对三个不同系列的LLMs（Bard，拥有1370亿参数；ChatGPT-3.5，1750亿参数；ChatGPT-4，1.5万亿参数）进行了语法判断测试，测试内容包括指代、中心嵌入、比较级和负极性等语法现象。共收集了1200个判断，并对其准确性、稳定性以及在重复提示后的准确性提升进行了评分。表现最佳的模型ChatGPT-4的结果与80名人类参与者在相同测试中的得分进行了比较。研究发现，虽然模型规模的增加可能带来性能的提升，但LLMs对于语法的敏感度仍然不如人类。单独依靠规模扩展来解决这一问题似乎可能性不大。我们通过对比自然语言的学习和机器学习，对这些结果进行了解读，并指出了三个关键差异：（i）证据的类型，（ii）语言刺激的不足，以及（iii）由于语言参照的不可穿透性导致的语义幻觉现象。

> Understanding the limits of language is a prerequisite for Large Language Models (LLMs) to act as theories of natural language. LLM performance in some language tasks presents both quantitative and qualitative differences from that of humans, however it remains to be determined whether such differences are amenable to model size. This work investigates the critical role of model scaling, determining whether increases in size make up for such differences between humans and models. We test three LLMs from different families (Bard, 137 billion parameters; ChatGPT-3.5, 175 billion; ChatGPT-4, 1.5 trillion) on a grammaticality judgment task featuring anaphora, center embedding, comparatives, and negative polarity. N=1,200 judgments are collected and scored for accuracy, stability, and improvements in accuracy upon repeated presentation of a prompt. Results of the best performing LLM, ChatGPT-4, are compared to results of n=80 humans on the same stimuli. We find that increased model size may lead to better performance, but LLMs are still not sensitive to (un)grammaticality as humans are. It seems possible but unlikely that scaling alone can fix this issue. We interpret these results by comparing language learning in vivo and in silico, identifying three critical differences concerning (i) the type of evidence, (ii) the poverty of the stimulus, and (iii) the occurrence of semantic hallucinations due to impenetrable linguistic reference.

[Arxiv](https://arxiv.org/abs/2404.14883)