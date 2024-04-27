# Apollonion：专注于个人资料的对话代理

发布时间：2024年04月09日

`Agent` `对话系统` `个性化推荐`

> Apollonion: Profile-centric Dialog Agent

# 摘要

> 大型语言模型（LLMs）的崛起为对话代理的发展带来了创新。一个经过良好训练的LLM，作为核心处理单元，能够为用户提供流畅且合理的响应。辅助工具如外部知识检索、个性化角色设定、以及短/长期记忆管理等，进一步提升了LLM驱动的对话代理的用户体验。尽管如此，现有技术仍未能解决用户个性化的问题：不同用户的响应千篇一律，忽略了他们的习惯、兴趣和经验等个性化特征。换句话说，现有的对话代理在“了解用户”方面仍有所欠缺。用户特征的详细描述和表示仍在不断进步中。在本研究中，我们提出了一个对话代理框架，旨在整合用户画像的创建和更新：通过分析和整理用户的查询与反馈，构建结构化的用户画像，以便提供更加个性化和精准的响应。此外，我们还设计了一系列评估个性化程度的协议。这个框架被命名为\method{}，灵感源自古希腊阿波罗神庙中的“认识你自己”这一格言。在将个性化融入LLM的探索中，\method{}是首次尝试通过对话代理引导LLM的个性化响应，同时提供了一套评估个性化效果的方法。

> The emergence of Large Language Models (LLMs) has innovated the development of dialog agents. Specially, a well-trained LLM, as a central process unit, is capable of providing fluent and reasonable response for user's request. Besides, auxiliary tools such as external knowledge retrieval, personalized character for vivid response, short/long-term memory for ultra long context management are developed, completing the usage experience for LLM-based dialog agents. However, the above-mentioned techniques does not solve the issue of \textbf{personalization from user perspective}: agents response in a same fashion to different users, without consideration of their features, such as habits, interests and past experience. In another words, current implementation of dialog agents fail in ``knowing the user''. The capacity of well-description and representation of user is under development. In this work, we proposed a framework for dialog agent to incorporate user profiling (initialization, update): user's query and response is analyzed and organized into a structural user profile, which is latter served to provide personal and more precise response. Besides, we proposed a series of evaluation protocols for personalization: to what extend the response is personal to the different users.
  The framework is named as \method{}, inspired by inscription of ``Know Yourself'' in the temple of Apollo (also known as \method{}) in Ancient Greek. Few works have been conducted on incorporating personalization into LLM, \method{} is a pioneer work on guiding LLM's response to meet individuation via the application of dialog agents, with a set of evaluation methods for measurement in personalization.

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/logo2.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x1.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x2.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x3.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x4.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x5.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x6.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x7.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x8.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x9.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x10.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x11.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x12.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x13.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x14.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x15.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x16.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x17.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x18.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x19.png)

![Apollonion：专注于个人资料的对话代理](../../../paper_images/2404.08692/x20.png)

[Arxiv](https://arxiv.org/abs/2404.08692)