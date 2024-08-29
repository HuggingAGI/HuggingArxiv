# WildFeedback：实现 LLMs 与实时用户互动及反馈的协同

发布时间：2024年08月28日

`LLM应用` `人工智能` `语言模型`

> WildFeedback: Aligning LLMs With In-situ User Interactions And Feedback

# 摘要

> 随着大型语言模型的不断发展，如何使其与人类偏好相匹配成为一大挑战。传统对齐方法因资源密集、主观性强及可能加剧模型偏差而受限。为此，我们推出了WildFeedback框架，该框架通过实时用户互动，精准捕捉并反映真实的人类价值观。WildFeedback的运作分为三步：识别反馈信号、构建偏好数据、进行用户引导评估。我们将其应用于大量用户与模型的对话中，成功构建了一个能真实反映用户偏好的数据集。该数据集通过分析对话中的反馈信号，细致入微地捕捉用户偏好，从而生成更具代表性和情境敏感性的对齐数据。实验证明，经WildFeedback微调的模型在用户偏好对齐方面表现卓越，不仅在传统基准测试中表现优异，更在我们的用户引导评估中得到验证。WildFeedback通过实时用户反馈，有效解决了现有方法的可扩展性、主观性和偏差问题，为开发更贴近用户需求的语言模型迈出了关键一步。简而言之，WildFeedback为LLMs与人类价值观的对齐提供了一个强大且可扩展的解决方案，为以用户为中心的语言模型开发与评估树立了新标杆。

> As large language models (LLMs) continue to advance, aligning these models with human preferences has emerged as a critical challenge. Traditional alignment methods, relying on human or LLM annotated datasets, are limited by their resource-intensive nature, inherent subjectivity, and the risk of feedback loops that amplify model biases. To overcome these limitations, we introduce WildFeedback, a novel framework that leverages real-time, in-situ user interactions to create preference datasets that more accurately reflect authentic human values. WildFeedback operates through a three-step process: feedback signal identification, preference data construction, and user-guided evaluation. We applied this framework to a large corpus of user-LLM conversations, resulting in a rich preference dataset that reflects genuine user preferences. This dataset captures the nuances of user preferences by identifying and classifying feedback signals within natural conversations, thereby enabling the construction of more representative and context-sensitive alignment data. Our extensive experiments demonstrate that LLMs fine-tuned on WildFeedback exhibit significantly improved alignment with user preferences, as evidenced by both traditional benchmarks and our proposed user-guided evaluation. By incorporating real-time feedback from actual users, WildFeedback addresses the scalability, subjectivity, and bias challenges that plague existing approaches, marking a significant step toward developing LLMs that are more responsive to the diverse and evolving needs of their users. In summary, WildFeedback offers a robust, scalable solution for aligning LLMs with true human values, setting a new standard for the development and evaluation of user-centric language models.

[Arxiv](https://arxiv.org/abs/2408.15549)