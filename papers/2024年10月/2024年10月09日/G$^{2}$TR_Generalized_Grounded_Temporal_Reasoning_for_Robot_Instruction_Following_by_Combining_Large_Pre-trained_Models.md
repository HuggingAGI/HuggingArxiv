# G$^{2}$TR：结合大型预训练模型，为机器人指令跟随提供广义的时间推理能力

发布时间：2024年10月09日

`Agent` `机器人` `人工智能`

> G$^{2}$TR: Generalized Grounded Temporal Reasoning for Robot Instruction Following by Combining Large Pre-trained Models

# 摘要

> 想象一下，一个人在清洁桌子，而机器人则在一旁观察。机器人接到指令：“用我擦桌子的布把布拿走。” 要完成这个任务，机器人需要回顾过去的动作，识别出相关的物体，并在当前场景中找到它，然后按照指令执行。由于过去动作的复杂性和视频流中物体位置的多样性，直接将指令与实际物体对应起来并不容易。我们的解决方案是将这个复杂任务分解为三个步骤：首先，确定与指令相关的时间段；其次，在相关时间段内进行空间推理，找出目标物体；最后，持续追踪物体的位置，直到当前场景，以便机器人能够顺利执行任务。我们利用了现有的、具有强大泛化能力的大型预训练模型，并将其巧妙结合，用于处理这类时间定位任务。实验结果显示，在复杂场景中，机器人能够以70.10%的平均准确率完成任务。所有数据、代码和视频都可以在https://reail-iitdelhi.github.io/temporalreasoning.github.io/找到。

> Consider the scenario where a human cleans a table and a robot observing the scene is instructed with the task "Remove the cloth using which I wiped the table". Instruction following with temporal reasoning requires the robot to identify the relevant past object interaction, ground the object of interest in the present scene, and execute the task according to the human's instruction. Directly grounding utterances referencing past interactions to grounded objects is challenging due to the multi-hop nature of references to past interactions and large space of object groundings in a video stream observing the robot's workspace. Our key insight is to factor the temporal reasoning task as (i) estimating the video interval associated with event reference, (ii) performing spatial reasoning over the interaction frames to infer the intended object (iii) semantically track the object's location till the current scene to enable future robot interactions. Our approach leverages existing large pre-trained models (which possess inherent generalization capabilities) and combines them appropriately for temporal grounding tasks. Evaluation on a video-language corpus acquired with a robot manipulator displaying rich temporal interactions in spatially-complex scenes displays an average accuracy of 70.10%. The dataset, code, and videos are available at https://reail-iitdelhi.github.io/temporalreasoning.github.io/ .

[Arxiv](https://arxiv.org/abs/2410.07494)