# 机器人操作通过功能性匹配流实现

发布时间：2024年09月02日

`Agent` `机器人技术` `人工智能`

> Affordance-based Robot Manipulation with Flow Matching

# 摘要

> 我们设计了一个辅助机器人操作框架，直面两大挑战：一是如何高效地将庞大数据模型应用于日常生活场景中的下游任务，尤其是在涉及人类的多任务数据收集方面；二是如何通过视觉可操作性模型有效学习机器人轨迹。为应对首个挑战，我们采用了参数高效的提示调优技术，通过在冻结的视觉模型前加入可学习的文本提示，精准预测多任务场景中的操作可操作性。接着，我们提出了一种监督流匹配方法，引导机器人轨迹学习。流匹配技术将机器人视觉运动策略转化为将随机路点导向理想轨迹的条件过程。此外，我们还构建了一个包含10项日常活动任务的现实世界数据集，用于验证框架的有效性。经过广泛评估，我们发现，通过语言提示器进行的提示调优方法在各种数据规模上均表现出色，不仅参数效率高，而且在性能上超越了其他微调方法。同时，单一流匹配策略在多任务机器人轨迹学习中也展现出优于传统行为克隆方法的性能，尤其是在处理多模态机器人动作分布时。我们的框架巧妙地将可操作性模型学习与轨迹生成通过流匹配技术融为一体，为机器人操作提供了强有力的支持。

> We present a framework for assistive robot manipulation, which focuses on two fundamental challenges: first, efficiently adapting large-scale models to downstream scene affordance understanding tasks, especially in daily living scenarios where gathering multi-task data involving humans requires strenuous effort; second, effectively learning robot trajectories by grounding the visual affordance model. We tackle the first challenge by employing a parameter-efficient prompt tuning method that prepends learnable text prompts to the frozen vision model to predict manipulation affordances in multi-task scenarios. Then we propose to learn robot trajectories guided by affordances in a supervised Flow Matching method. Flow matching represents a robot visuomotor policy as a conditional process of flowing random waypoints to desired robot trajectories. Finally, we introduce a real-world dataset with 10 tasks across Activities of Daily Living to test our framework. Our extensive evaluation highlights that the proposed prompt tuning method for learning manipulation affordance with language prompter achieves competitive performance and even outperforms other finetuning protocols across data scales, while satisfying parameter efficiency. Learning multi-task robot trajectories with a single flow matching policy also leads to consistently better performance than alternative behavior cloning methods, especially given multimodal robot action distributions. Our framework seamlessly unifies affordance model learning and trajectory generation with flow matching for robot manipulation.

[Arxiv](https://arxiv.org/abs/2409.01083)