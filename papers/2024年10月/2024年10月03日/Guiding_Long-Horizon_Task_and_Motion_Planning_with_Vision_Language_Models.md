# 视觉语言模型助力长时任务与运动规划

发布时间：2024年10月03日

`Agent` `机器人` `人工智能`

> Guiding Long-Horizon Task and Motion Planning with Vision Language Models

# 摘要

> 视觉-语言模型 (VLM) 能根据目标、场景图像和规划约束生成合理的高级计划，但无法确保这些动作对特定机器人实体在几何和运动学上是可行的。因此，许多必要的步骤，如打开抽屉，常被忽略。机器人任务和运动规划器虽能生成符合几何可行性的轨迹，并插入必要的物理动作，但难以应对需要常识和大状态空间的日常问题。为此，我们提出了 VLM-TAMP，一种利用 VLM 生成语义丰富且视野缩小的中间子目标的分层规划算法，以指导任务和运动规划。若子目标或动作无法细化，则再次查询 VLM 进行重新规划。在厨房任务中，VLM-TAMP 在成功率和任务完成率上显著优于传统方法。更多详情请访问项目网站 https://zt-yang.github.io/vlm-tamp-robot/。

> Vision-Language Models (VLM) can generate plausible high-level plans when prompted with a goal, the context, an image of the scene, and any planning constraints. However, there is no guarantee that the predicted actions are geometrically and kinematically feasible for a particular robot embodiment. As a result, many prerequisite steps such as opening drawers to access objects are often omitted in their plans. Robot task and motion planners can generate motion trajectories that respect the geometric feasibility of actions and insert physically necessary actions, but do not scale to everyday problems that require common-sense knowledge and involve large state spaces comprised of many variables. We propose VLM-TAMP, a hierarchical planning algorithm that leverages a VLM to generate goth semantically-meaningful and horizon-reducing intermediate subgoals that guide a task and motion planner. When a subgoal or action cannot be refined, the VLM is queried again for replanning. We evaluate VLM- TAMP on kitchen tasks where a robot must accomplish cooking goals that require performing 30-50 actions in sequence and interacting with up to 21 objects. VLM-TAMP substantially outperforms baselines that rigidly and independently execute VLM-generated action sequences, both in terms of success rates (50 to 100% versus 0%) and average task completion percentage (72 to 100% versus 15 to 45%). See project site https://zt-yang.github.io/vlm-tamp-robot/ for more information.

[Arxiv](https://arxiv.org/abs/2410.02193)