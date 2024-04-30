# 基础性的大型语言模型是否能够帮助我们开展药品制造业的调查研究？

发布时间：2024年04月23日

`LLM应用` `制药制造`

> Can Foundational Large Language Models Assist with Conducting Pharmaceuticals Manufacturing Investigations?

# 摘要

> 近年来，诸如生成预训练变换器（GPT）和大型语言模型元人工智能（LLaMA）等通用大型语言模型（LLM）备受瞩目，并在自然语言处理任务中展现出卓越性能。但如何有效利用这些模型以适应特定领域的应用场景，仍是一个待解之谜。本研究着眼于制药制造业调查这一特定用例，提出通过利用企业中制造事故和偏差的历史档案，有助于处理新案例或降低新生产活动的潜在风险。我们选取了来自不同生产线的真实制造偏差数据，虽规模不大但类型多样，以此评估了三款主流LLM（GPT-3.5、GPT-4和Claude-2）在相关任务上的表现。研究特别关注了：（1）LLM自动从非结构化数据中提取关键信息，如案例根本原因的能力；（2）通过语义搜索历史记录数据库，识别相似或相关偏差的可能性。GPT-4和Claude-2在信息提取任务上的高准确率表现引人注目，同时我们也探讨了LLM在推理与幻觉行为间的复杂互动，及其作为风险因素的考量。此外，我们还展示了通过向量嵌入进行语义搜索，能够高效识别具有相似缺陷类型的相关记录。文章进一步讨论了如何提升识别相似记录的准确性的潜在改进措施。

> General purpose Large Language Models (LLM) such as the Generative Pretrained Transformer (GPT) and Large Language Model Meta AI (LLaMA) have attracted much attention in recent years. There is strong evidence that these models can perform remarkably well in various natural language processing tasks. However, how to leverage them to approach domain-specific use cases and drive value remains an open question. In this work, we focus on a specific use case, pharmaceutical manufacturing investigations, and propose that leveraging historical records of manufacturing incidents and deviations in an organization can be beneficial for addressing and closing new cases, or de-risking new manufacturing campaigns. Using a small but diverse dataset of real manufacturing deviations selected from different product lines, we evaluate and quantify the power of three general purpose LLMs (GPT-3.5, GPT-4, and Claude-2) in performing tasks related to the above goal. In particular, (1) the ability of LLMs in automating the process of extracting specific information such as root cause of a case from unstructured data, as well as (2) the possibility of identifying similar or related deviations by performing semantic search on the database of historical records are examined. While our results point to the high accuracy of GPT-4 and Claude-2 in the information extraction task, we discuss cases of complex interplay between the apparent reasoning and hallucination behavior of LLMs as a risk factor. Furthermore, we show that semantic search on vector embedding of deviation descriptions can be used to identify similar records, such as those with a similar type of defect, with a high level of accuracy. We discuss further improvements to enhance the accuracy of similar record identification.

[Arxiv](https://arxiv.org/abs/2404.15578)