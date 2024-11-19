# “在我不在时机器人做了啥？” 利用视频基础模型强化间歇性监督

发布时间：2024年11月15日

`LLM应用` `机器人` `人机交互`

> 'What did the Robot do in my Absence?' Video Foundation Models to Enhance Intermittent Supervision

# 摘要

> 这篇论文探讨了视频基础模型（ViFMs）在生成机器人数据摘要以强化对机器人团队的间歇性人工监管方面的运用。我们构建了一个全新的框架，能以三种形式（故事板、短视频和文本）为长期的机器人视觉数据生成通用型和查询驱动型的摘要。通过一个有 30 名参与者的用户研究，我们评估了这些摘要方法在让操作员精确找回机器人在长时间（40 分钟）无监管操作时发生的观察结果和动作方面的成效。我们的发现表明，相较于通用摘要或原始数据，查询驱动型摘要显著提升了检索的准确性，不过任务时长有所增加。故事板被认定是最有效的呈现形式，尤其对于与对象相关的查询。据我们所知，此项工作是 ViFMs 在间歇性监管情境下生成多模态机器人与人交流的首次零样本应用，展现了这些模型在人机交互（HRI）场景中的潜力与局限。

> This paper investigates the application of Video Foundation Models (ViFMs) for generating robot data summaries to enhance intermittent human supervision of robot teams. We propose a novel framework that produces both generic and query-driven summaries of long-duration robot vision data in three modalities: storyboards, short videos, and text. Through a user study involving 30 participants, we evaluate the efficacy of these summary methods in allowing operators to accurately retrieve the observations and actions that occurred while the robot was operating without supervision over an extended duration (40 min). Our findings reveal that query-driven summaries significantly improve retrieval accuracy compared to generic summaries or raw data, albeit with increased task duration. Storyboards are found to be the most effective presentation modality, especially for object-related queries. This work represents, to our knowledge, the first zero-shot application of ViFMs for generating multi-modal robot-to-human communication in intermittent supervision contexts, demonstrating both the promise and limitations of these models in human-robot interaction (HRI) scenarios.

[Arxiv](https://arxiv.org/abs/2411.10016)