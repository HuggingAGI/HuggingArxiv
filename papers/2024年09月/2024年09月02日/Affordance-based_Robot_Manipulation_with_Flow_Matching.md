# 机器人操作基于功能性，结合流匹配技术

发布时间：2024年09月02日

`Agent` `机器人技术` `人工智能`

> Affordance-based Robot Manipulation with Flow Matching

# 摘要

> 我们设计了一个辅助机器人操作框架，主要解决两大难题：一是如何高效地将大型模型应用于日常生活场景中的下游任务，这些场景涉及人类的多任务数据收集难度大；二是如何利用视觉可操作性模型有效规划机器人轨迹。为应对第一个挑战，我们采用了参数高效的提示调优技术，通过在冻结的视觉模型前加入可学习的文本提示，来预测多任务环境下的操作可操作性。接着，我们提出了一种监督流匹配方法，通过可操作性引导机器人轨迹的学习。流匹配技术将机器人的视觉运动策略转化为将随机路点引导至目标轨迹的过程。此外，我们还创建了一个包含10项日常活动任务的现实世界数据集，用于验证框架的有效性。经过广泛评估，我们的提示调优方法在操作可操作性学习方面表现优异，不仅在各种数据规模上与现有微调方法竞争，甚至在参数效率方面更胜一筹。通过单一流匹配策略实现的多任务机器人轨迹学习，其性能也显著优于传统的行为克隆方法，尤其是在处理多模态机器人动作分布时。我们的框架成功整合了可操作性模型学习与轨迹生成，为机器人操作提供了流畅的解决方案。

> We present a framework for assistive robot manipulation, which focuses on two fundamental challenges: first, efficiently adapting large-scale models to downstream scene affordance understanding tasks, especially in daily living scenarios where gathering multi-task data involving humans requires strenuous effort; second, effectively learning robot trajectories by grounding the visual affordance model. We tackle the first challenge by employing a parameter-efficient prompt tuning method that prepends learnable text prompts to the frozen vision model to predict manipulation affordances in multi-task scenarios. Then we propose to learn robot trajectories guided by affordances in a supervised Flow Matching method. Flow matching represents a robot visuomotor policy as a conditional process of flowing random waypoints to desired robot trajectories. Finally, we introduce a real-world dataset with 10 tasks across Activities of Daily Living to test our framework. Our extensive evaluation highlights that the proposed prompt tuning method for learning manipulation affordance with language prompter achieves competitive performance and even outperforms other finetuning protocols across data scales, while satisfying parameter efficiency. Learning multi-task robot trajectories with a single flow matching policy also leads to consistently better performance than alternative behavior cloning methods, especially given multimodal robot action distributions. Our framework seamlessly unifies affordance model learning and trajectory generation with flow matching for robot manipulation.

[Arxiv](https://arxiv.org/abs/2409.01083)