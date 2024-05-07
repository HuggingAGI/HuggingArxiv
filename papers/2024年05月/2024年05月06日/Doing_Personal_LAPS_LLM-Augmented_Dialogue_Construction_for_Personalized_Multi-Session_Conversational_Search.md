# 个性化循环训练：借助大型语言模型，构建个性化的多轮对话，以优化个性化的多会话搜索体验。

发布时间：2024年05月06日

`Agent` `对话系统` `个性化推荐`

> Doing Personal LAPS: LLM-Augmented Dialogue Construction for Personalized Multi-Session Conversational Search

# 摘要

> 未来对话代理将为用户带来定制化的信息反馈。但构建这类模型的一大难题是缺少覆盖多轮对话、体现用户真实偏好的大型对话数据集。传统做法依赖于专家进行“幕后指导”，这在规模化尤其是个性化任务上存在难度。我们的解决方案LAPS，利用大型语言模型（LLMs）辅助单一人工操作者产出个性化对话，显著提升了制作效率和对话质量。LAPS能够收集到大规模、真人编写、跨多个会话和领域的对话内容，并从中提取用户偏好。与现有数据集相比，LAPS产出的对话在自然度和多样性上与专家水准相媲美，且优于完全合成的方法。该数据集非常适合用于训练偏好抽取和个性化响应生成模型。实验结果表明，基于提取的偏好生成的响应更贴近用户的实际偏好，这强调了利用提取偏好而非仅依赖对话历史的重要性。总体来看，LAPS提出了一种创新方法，通过LLMs高效、有效地生成更为真实的个性化对话数据，超越了以往的做法。

> The future of conversational agents will provide users with personalized information responses. However, a significant challenge in developing models is the lack of large-scale dialogue datasets that span multiple sessions and reflect real-world user preferences. Previous approaches rely on experts in a wizard-of-oz setup that is difficult to scale, particularly for personalized tasks. Our method, LAPS, addresses this by using large language models (LLMs) to guide a single human worker in generating personalized dialogues. This method has proven to speed up the creation process and improve quality. LAPS can collect large-scale, human-written, multi-session, and multi-domain conversations, including extracting user preferences. When compared to existing datasets, LAPS-produced conversations are as natural and diverse as expert-created ones, which stays in contrast with fully synthetic methods. The collected dataset is suited to train preference extraction and personalized response generation. Our results show that responses generated explicitly using extracted preferences better match user's actual preferences, highlighting the value of using extracted preferences over simple dialogue history. Overall, LAPS introduces a new method to leverage LLMs to create realistic personalized conversational data more efficiently and effectively than previous methods.

[Arxiv](https://arxiv.org/abs/2405.03480)