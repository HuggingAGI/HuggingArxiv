# LLMs 在标注时默认采用哪些人口统计特征？

发布时间：2024年10月11日

`LLM理论` `社会科学` `人工智能`

> Which Demographics do LLMs Default to During Annotation?

# 摘要

> 标注者的年龄、性别和文化背景会影响他们在文本标注中的标签分配。例如，老年女性可能觉得被称呼为“bro”冒犯，而男性青少年则可能觉得这很合适。因此，承认标签的差异性以避免低估社会成员的重要性至关重要。基于此，我们探讨了两个研究方向：一是研究 LLM 的偏见和固有知识，二是通过操纵包含人口统计信息的提示来增加输出多样性。我们结合这两个方向，探讨了在没有提供人口统计信息时，LLM 会依赖哪些特征。通过评估 LLM 模仿人类标注者的属性，我们发现人口统计提示对性别、种族和年龄有显著影响，这与之前的研究结果形成对比。

> Demographics and cultural background of annotators influence the labels they assign in text annotation -- for instance, an elderly woman might find it offensive to read a message addressed to a "bro", but a male teenager might find it appropriate. It is therefore important to acknowledge label variations to not under-represent members of a society. Two research directions developed out of this observation in the context of using large language models (LLM) for data annotations, namely (1) studying biases and inherent knowledge of LLMs and (2) injecting diversity in the output by manipulating the prompt with demographic information. We combine these two strands of research and ask the question to which demographics an LLM resorts to when no demographics is given. To answer this question, we evaluate which attributes of human annotators LLMs inherently mimic. Furthermore, we compare non-demographic conditioned prompts and placebo-conditioned prompts (e.g., "you are an annotator who lives in house number 5") to demographics-conditioned prompts ("You are a 45 year old man and an expert on politeness annotation. How do you rate {instance}"). We study these questions for politeness and offensiveness annotations on the POPQUORN data set, a corpus created in a controlled manner to investigate human label variations based on demographics which has not been used for LLM-based analyses so far. We observe notable influences related to gender, race, and age in demographic prompting, which contrasts with previous studies that found no such effects.

[Arxiv](https://arxiv.org/abs/2410.08820)