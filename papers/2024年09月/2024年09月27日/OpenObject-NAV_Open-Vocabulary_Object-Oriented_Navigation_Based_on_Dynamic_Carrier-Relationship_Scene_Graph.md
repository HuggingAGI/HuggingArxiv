# OpenObject-NAV：一种基于动态载体关系场景图的开放词汇面向对象导航系统

发布时间：2024年09月27日

`Agent` `机器人` `智能家居`

> OpenObject-NAV: Open-Vocabulary Object-Oriented Navigation Based on Dynamic Carrier-Relationship Scene Graph

# 摘要

> 日常生活中，常用物品如杯子位置不固定，且同一类别中存在多个实例，其载体也常变化。这使得机器人难以高效导航至特定物品。为此，机器人需持续捕捉并更新场景变化。然而，现有导航方法多聚焦于语义层面，缺乏动态更新能力。本文构建了开放词汇的载体关系场景图（CRSG），实时更新携带状态，反映场景动态。基于此，我们提出实例导航策略，将导航过程视为马尔可夫决策过程，每一步决策结合大型语言模型的常识与视觉语言特征。在Habitat模拟器中，我们设计了针对常用物品的长序列导航任务，结果显示，更新CRSG后，机器人能高效导航至移动目标。此外，我们在真实机器人上验证了算法的实用性。

> In everyday life, frequently used objects like cups often have unfixed positions and multiple instances within the same category, and their carriers frequently change as well. As a result, it becomes challenging for a robot to efficiently navigate to a specific instance. To tackle this challenge, the robot must capture and update scene changes and plans continuously. However, current object navigation approaches primarily focus on semantic-level and lack the ability to dynamically update scene representation. This paper captures the relationships between frequently used objects and their static carriers. It constructs an open-vocabulary Carrier-Relationship Scene Graph (CRSG) and updates the carrying status during robot navigation to reflect the dynamic changes of the scene. Based on the CRSG, we further propose an instance navigation strategy that models the navigation process as a Markov Decision Process. At each step, decisions are informed by Large Language Model's commonsense knowledge and visual-language feature similarity. We designed a series of long-sequence navigation tasks for frequently used everyday items in the Habitat simulator. The results demonstrate that by updating the CRSG, the robot can efficiently navigate to moved targets. Additionally, we deployed our algorithm on a real robot and validated its practical effectiveness.

[Arxiv](https://arxiv.org/abs/2409.18743)