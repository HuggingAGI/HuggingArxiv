# TI-PREGO：用于在以自我为中心的程序性视频中进行在线错误检测的思维链和上下文学习

发布时间：2024年11月04日

`LLM应用` `制造业` `医疗保健`

> TI-PREGO: Chain of Thought and In-Context Learning for Online Mistake Detection in PRocedural EGOcentric Videos

# 摘要

> 从以自我为中心的视频中在线识别程序性错误是包括制造业、医疗保健和基于技能的培训等各个领域中的一项关键但具有挑战性的任务。这类错误的性质本质上是开放式的，因为可能会出现不可预见或新颖的错误，这就需要强大的检测系统，而不是依赖于先前的失败示例。然而，目前还没有技术能有效地在线检测开放式程序性错误。

我们提出了一种双分支架构以在线方式解决这个问题：一个分支从输入的以自我为中心的视频中持续进行步骤识别，而另一个分支根据识别模块的输出预测未来步骤。错误被检测为当前识别的动作与预测模块预测的动作之间的不匹配。识别分支接收输入帧，预测当前动作，并将帧级结果聚合为动作标记。特别是，预测分支利用大型语言模型（LLM）强大的模式匹配能力，根据先前预测的动作标记来预测动作标记。

鉴于任务的在线性质，我们还全面衡量了与逐帧评估相关的困难，特别是在动态在线场景中对准确和及时预测的需求。

在两个程序性数据集上进行的大量实验展示了利用双分支架构进行错误检测的挑战和机遇，展示了我们提出的方法的有效性。在包括识别和预测变体以及最先进模型的全面评估中，我们的方法显示了其在在线应用中的稳健性和有效性。

> Identifying procedural errors online from egocentric videos is a critical yet challenging task across various domains, including manufacturing, healthcare, and skill-based training. The nature of such mistakes is inherently open-set, as unforeseen or novel errors may occur, necessitating robust detection systems that do not rely on prior examples of failure. Currently, however, no technique effectively detects open-set procedural mistakes online.
  We propose a dual branch architecture to address this problem in an online fashion: one branch continuously performs step recognition from the input egocentric video, while the other anticipates future steps based on the recognition module's output. Mistakes are detected as mismatches between the currently recognized action and the action predicted by the anticipation module. The recognition branch takes input frames, predicts the current action, and aggregates frame-level results into action tokens. The anticipation branch, specifically, leverages the solid pattern-matching capabilities of Large Language Models (LLMs) to predict action tokens based on previously predicted ones.
  Given the online nature of the task, we also thoroughly benchmark the difficulties associated with per-frame evaluations, particularly the need for accurate and timely predictions in dynamic online scenarios.
  Extensive experiments on two procedural datasets demonstrate the challenges and opportunities of leveraging a dual-branch architecture for mistake detection, showcasing the effectiveness of our proposed approach. In a thorough evaluation including recognition and anticipation variants and state-of-the-art models, our method reveals its robustness and effectiveness in online applications.

[Arxiv](https://arxiv.org/abs/2411.02570)