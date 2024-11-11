# 语音沙盒：用于情境化人机协作的持续学习和适应

发布时间：2024年11月04日

`Agent` `机器人` `人机协作`

> Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration

# 摘要

> 我们引入了 Vocal Sandbox，这是一个在特定环境中实现无缝人机协作的框架。我们框架中的系统的特点是能够从诸如口头对话、物体关键点和动觉演示等多种教学模式中在多个抽象层次上进行适应和持续学习。为了实现这种适应，我们设计了轻量级且可解释的学习算法，使用户能够在实时教授新行为时建立对机器人能力的理解并共同适应。例如，在为“围绕”一个物体展示新的低级技能后，当被要求跟踪一个新物体时，用户会获得机器人预期运动的轨迹可视化。同样，用户通过口头对话教授高级规划行为，使用预训练的语言模型将诸如“把物体收起来”等行为合成为低级技能的组合——这些概念可以被重复使用和构建。我们在两个场景中评估 Vocal Sandbox：协作礼品袋组装和乐高定格动画。在第一个场景中，我们与 8 名非专家参与者进行了系统的消融实验和用户研究，突出了多层次教学的影响。在总共 23 小时的机器人交互时间中，用户教授了 17 种新的高级行为，平均有 16 种新颖的低级技能，与基线相比需要的主动监督减少了 22.1％，产生了更复杂的自主性能（+19.7％），失败次数减少了 67.1％。从定性的角度来看，由于易用性（+20.6％）和整体性能（+13.9％），用户强烈偏爱 Vocal Sandbox 系统。最后，我们让一位经验丰富的系统用户与机器人合作拍摄定格动画；在两个多小时的持续协作中，用户逐步教授更复杂的运动技能，拍摄了一部 52 秒（232 帧）的电影。

> We introduce Vocal Sandbox, a framework for enabling seamless human-robot collaboration in situated environments. Systems in our framework are characterized by their ability to adapt and continually learn at multiple levels of abstraction from diverse teaching modalities such as spoken dialogue, object keypoints, and kinesthetic demonstrations. To enable such adaptation, we design lightweight and interpretable learning algorithms that allow users to build an understanding and co-adapt to a robot's capabilities in real-time, as they teach new behaviors. For example, after demonstrating a new low-level skill for "tracking around" an object, users are provided with trajectory visualizations of the robot's intended motion when asked to track a new object. Similarly, users teach high-level planning behaviors through spoken dialogue, using pretrained language models to synthesize behaviors such as "packing an object away" as compositions of low-level skills $-$ concepts that can be reused and built upon. We evaluate Vocal Sandbox in two settings: collaborative gift bag assembly and LEGO stop-motion animation. In the first setting, we run systematic ablations and user studies with 8 non-expert participants, highlighting the impact of multi-level teaching. Across 23 hours of total robot interaction time, users teach 17 new high-level behaviors with an average of 16 novel low-level skills, requiring 22.1% less active supervision compared to baselines and yielding more complex autonomous performance (+19.7%) with fewer failures (-67.1%). Qualitatively, users strongly prefer Vocal Sandbox systems due to their ease of use (+20.6%) and overall performance (+13.9%). Finally, we pair an experienced system-user with a robot to film a stop-motion animation; over two hours of continuous collaboration, the user teaches progressively more complex motion skills to shoot a 52 second (232 frame) movie.

[Arxiv](https://arxiv.org/abs/2411.02599)