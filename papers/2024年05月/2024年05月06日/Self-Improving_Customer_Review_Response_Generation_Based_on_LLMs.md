# 大型语言模型助力，客户评论回复智能升级在翻译过程中，我首先确保了原文意思的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。

发布时间：2024年05月06日

`RAG

这篇论文介绍了一个名为SCRABLE的系统，它利用RAG（Retrieval-Augmented Generation）技术和大型语言模型（LLMs）来自动化生成高质量的用户评论回复。RAG是一种结合了信息检索和文本生成的方法，用于提高生成文本的相关性和准确性。SCRABLE系统不仅能够自我优化，还具备基于LLMs的评判机制和自动评分机制，以模拟人类评估并确保回复质量。因此，这篇论文更符合RAG分类，因为它主要关注的是RAG技术在自动化回复用户评论这一应用场景中的应用和效果。` `应用开发` `客户服务`

> Self-Improving Customer Review Response Generation Based on LLMs

# 摘要

> 以往研究表明，主动参与用户评论能提升应用用户的满意度，并激励他们更新评分。但面对热门应用每日涌入的大量评论，开发者往往难以应对。因此，自动化回复用户评论的需求日益增长，我们开发了SCRABLE系统，它利用RAG技术和LLMs，自动生成高质量回复。SCRABLE具备自我优化和基于LLMs的评判机制，还能通过自动评分机制模拟人类评估，确保回复质量。实验证明，SCRABLE的回复质量比基线高出8.5%以上，且经人工审核，其有效性得到进一步确认。

> Previous studies have demonstrated that proactive interaction with user reviews has a positive impact on the perception of app users and encourages them to submit revised ratings. Nevertheless, developers encounter challenges in managing a high volume of reviews, particularly in the case of popular apps with a substantial influx of daily reviews. Consequently, there is a demand for automated solutions aimed at streamlining the process of responding to user reviews. To address this, we have developed a new system for generating automatic responses by leveraging user-contributed documents with the help of retrieval-augmented generation (RAG) and advanced Large Language Models (LLMs). Our solution, named SCRABLE, represents an adaptive customer review response automation that enhances itself with self-optimizing prompts and a judging mechanism based on LLMs. Additionally, we introduce an automatic scoring mechanism that mimics the role of a human evaluator to assess the quality of responses generated in customer review domains. Extensive experiments and analyses conducted on real-world datasets reveal that our method is effective in producing high-quality responses, yielding improvement of more than 8.5% compared to the baseline. Further validation through manual examination of the generated responses underscores the efficacy our proposed system.

![大型语言模型助力，客户评论回复智能升级在翻译过程中，我首先确保了原文意思的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。](../../../paper_images/2405.03845/PromptOpt.png)

![大型语言模型助力，客户评论回复智能升级在翻译过程中，我首先确保了原文意思的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。](../../../paper_images/2405.03845/Feedback.png)

![大型语言模型助力，客户评论回复智能升级在翻译过程中，我首先确保了原文意思的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。](../../../paper_images/2405.03845/RAG_overview.jpg)

![大型语言模型助力，客户评论回复智能升级在翻译过程中，我首先确保了原文意思的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。](../../../paper_images/2405.03845/Walkthru2.jpg)

[Arxiv](https://arxiv.org/abs/2405.03845)