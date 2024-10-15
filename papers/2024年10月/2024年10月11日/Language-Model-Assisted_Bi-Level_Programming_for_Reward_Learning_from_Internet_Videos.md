# 借助语言模型的双层编程，从网络视频中学习奖励机制

发布时间：2024年10月11日

`Agent` `人工智能` `生物学`

> Language-Model-Assisted Bi-Level Programming for Reward Learning from Internet Videos

# 摘要

> 从生物专家（如人类和动物）的演示中学习，常面临数据获取的难题。虽然现有方法利用网络视频，但需复杂的任务专用流程来提取和重定向运动数据。为此，我们提出了一种语言模型辅助的双层编程框架，使强化学习代理能直接从网络视频中学习奖励，无需专门数据准备。框架分两层：上层由视觉语言模型（VLM）通过对比学习者与专家视频的行为提供反馈；下层由大型语言模型（LLM）将反馈转化为奖励更新。VLM与LLM协同，采用“链式法则”推导有效搜索方向。实验证明，该方法能高效从生物代理的专家视频中设计复杂行为的奖励。

> Learning from Demonstrations, particularly from biological experts like humans and animals, often encounters significant data acquisition challenges. While recent approaches leverage internet videos for learning, they require complex, task-specific pipelines to extract and retarget motion data for the agent. In this work, we introduce a language-model-assisted bi-level programming framework that enables a reinforcement learning agent to directly learn its reward from internet videos, bypassing dedicated data preparation. The framework includes two levels: an upper level where a vision-language model (VLM) provides feedback by comparing the learner's behavior with expert videos, and a lower level where a large language model (LLM) translates this feedback into reward updates. The VLM and LLM collaborate within this bi-level framework, using a "chain rule" approach to derive a valid search direction for reward learning. We validate the method for reward learning from YouTube videos, and the results have shown that the proposed method enables efficient reward design from expert videos of biological agents for complex behavior synthesis.

[Arxiv](https://arxiv.org/abs/2410.09286)