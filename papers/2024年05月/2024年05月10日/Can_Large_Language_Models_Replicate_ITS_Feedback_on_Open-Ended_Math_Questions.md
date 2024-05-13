# 大型语言模型是否具备复制智能教学系统对开放式数学问题反馈的能力？

发布时间：2024年05月10日

`Agent

解释：这篇论文探讨了大型语言模型（LLMs）在智能辅导系统（ITSs）中生成自动反馈的潜力，特别是在处理开放式数学问题时。虽然它涉及LLMs的应用，但重点在于模型作为智能代理（Agent）在教育领域中的作用，即如何作为一个智能系统来提供反馈。因此，它更符合Agent分类，而不是LLM应用，因为后者通常指的是LLMs在特定应用场景中的使用，而不强调模型作为代理的角色。此外，这篇论文并没有特别关注LLMs的理论方面，因此LLM理论分类也不适用。最后，论文内容与检索增强生成（RAG）无关，因此RAG分类也不适用。` `教育技术` `智能辅导系统`

> Can Large Language Models Replicate ITS Feedback on Open-Ended Math Questions?

# 摘要

> 智能辅导系统（ITSs）中的自动反馈组件，通常依赖于模板来提供学生错误时的反馈。然而，这种方法在处理开放式数学问题时显得力不从心，因为错误的种类繁多。我们的研究探索了大型语言模型（LLMs）在生成此类问题反馈方面的潜力。通过微调开源和专有LLMs，我们发现它们能够模仿训练数据中的反馈格式，但在面对新的学生错误时，其泛化能力不足。这表明，尽管LLMs能够掌握反馈的格式，但在理解学生数学错误方面仍有局限。

> Intelligent Tutoring Systems (ITSs) often contain an automated feedback component, which provides a predefined feedback message to students when they detect a predefined error. To such a feedback component, we often resort to template-based approaches. These approaches require significant effort from human experts to detect a limited number of possible student errors and provide corresponding feedback. This limitation is exemplified in open-ended math questions, where there can be a large number of different incorrect errors. In our work, we examine the capabilities of large language models (LLMs) to generate feedback for open-ended math questions, similar to that of an established ITS that uses a template-based approach. We fine-tune both open-source and proprietary LLMs on real student responses and corresponding ITS-provided feedback. We measure the quality of the generated feedback using text similarity metrics. We find that open-source and proprietary models both show promise in replicating the feedback they see during training, but do not generalize well to previously unseen student errors. These results suggest that despite being able to learn the formatting of feedback, LLMs are not able to fully understand mathematical errors made by students.

[Arxiv](https://arxiv.org/abs/2405.06414)