# DM2RM：一种双模式多模态排序方法，针对开放词汇指令下的目标对象与接收器进行优化。

发布时间：2024年08月14日

`Agent` `家用服务机器人` `自动化`

> DM2RM: Dual-Mode Multimodal Ranking for Target Objects and Receptacles Based on Open-Vocabulary Instructions

# 摘要

> 本研究旨在打造一款家用服务机器人（DSR），它能遵循开放词汇指令，将日常物品准确搬运至指定家具。当前方法多未能妥善处理图像检索环境下的开放词汇移动操作任务，且鲜有能同时识别目标物与容器的。为此，我们创新提出双模态多模态排序模型（DM2RM），依托多模态基础模型，实现单一模型对目标物与容器图像的同步检索。模型中融入切换机制，通过模式标记与大型语言模型辅助的短语识别，灵活调整嵌入空间以适应不同预测需求。为验证DM2RM性能，我们精心构建了涵盖数百建筑规模环境真实图像及众包指代表达指令的新颖数据集。实测表明，在图像检索标准指标上，DM2RM显著超越既往方案。更进一步，我们在标准化真实DSR平台上应用DM2RM执行取放任务，即便在零-shot迁移场景下，仍达成高达82%的任务成功率。相关演示视频、代码及更多资料已公开于https://kkrr10.github.io/dm2rm/。

> In this study, we aim to develop a domestic service robot (DSR) that, guided by open-vocabulary instructions, can carry everyday objects to the specified pieces of furniture. Few existing methods handle mobile manipulation tasks with open-vocabulary instructions in the image retrieval setting, and most do not identify both the target objects and the receptacles. We propose the Dual-Mode Multimodal Ranking model (DM2RM), which enables images of both the target objects and receptacles to be retrieved using a single model based on multimodal foundation models. We introduce a switching mechanism that leverages a mode token and phrase identification via a large language model to switch the embedding space based on the prediction target. To evaluate the DM2RM, we construct a novel dataset including real-world images collected from hundreds of building-scale environments and crowd-sourced instructions with referring expressions. The evaluation results show that the proposed DM2RM outperforms previous approaches in terms of standard metrics in image retrieval settings. Furthermore, we demonstrate the application of the DM2RM on a standardized real-world DSR platform including fetch-and-carry actions, where it achieves a task success rate of 82% despite the zero-shot transfer setting. Demonstration videos, code, and more materials are available at https://kkrr10.github.io/dm2rm/.

[Arxiv](https://arxiv.org/abs/2408.07910)