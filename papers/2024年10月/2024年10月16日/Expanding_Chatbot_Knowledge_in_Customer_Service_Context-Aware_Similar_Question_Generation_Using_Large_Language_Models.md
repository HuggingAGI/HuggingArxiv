# 在客户服务中提升聊天机器人知识：利用大型语言模型生成上下文感知的相似问题

发布时间：2024年10月16日

`LLM应用` `客户服务` `人工智能`

> Expanding Chatbot Knowledge in Customer Service: Context-Aware Similar Question Generation Using Large Language Models

# 摘要

> 服务聊天机器人的可靠响应通常依赖于基于检索的方法，这些方法将答案限制在预定义的问答对知识库中。为了应对客户查询表达方式的多样性，增加语义一致的类似问题成为首选方案，这一任务被称为类似问题生成（SQG）。传统方法依赖人工或规则，多样性有限且语义偏差大，只能生成有限的有用问题。为解决这些问题，我们提出了一种基于大型语言模型（LLM）的SQG方法，能在保持语义一致性的同时生成大量多样问题。通过特别设计的提示进行微调，利用LLM的自然语言理解能力实现这一目标。实验表明，我们的方法在语义多样性上显著优于基线方法。人工评估进一步确认，整合反映客户意图的答案对于满足业务需求的生成问题数量至关重要。

> Reliable responses of service chatbots are often achieved by employing retrieval-based methods that restrict answers to a knowledge base comprising predefined question-answer pairs (QA pairs). To accommodate potential variations in how a customer's query may be expressed, it emerges as the favored solution to augment these QA pairs with similar questions that are possibly diverse while remaining semantic consistency. This augmentation task is known as Similar Question Generation (SQG). Traditional methods that heavily rely on human efforts or rule-based techniques suffer from limited diversity or significant semantic deviation from the source question, only capable of producing a finite number of useful questions.
  To address these limitations, we propose an SQG approach based on Large Language Models (LLMs), capable of producing a substantial number of diverse questions while maintaining semantic consistency to the source QA pair. This is achieved by leveraging LLMs' natural language understanding capability through fine-tuning with specially designed prompts. The experiments conducted on a real customer-service dataset demonstrate that our method surpasses baseline methods by a significant margin in terms of semantic diversity. Human evaluation further confirms that integrating the answer that reflects the customer's intention is crucial for increasing the number of generated questions that meet business requirements.

[Arxiv](https://arxiv.org/abs/2410.12444)