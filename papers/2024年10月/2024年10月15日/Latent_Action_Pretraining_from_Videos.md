# 视频中的潜在动作预训练

发布时间：2024年10月15日

`Agent` `机器人` `人工智能`

> Latent Action Pretraining from Videos

# 摘要

> 我们提出了一种名为LAPA的无监督预训练方法，用于视觉-语言-动作（VLA）模型，无需机器人动作标签。现有VLA模型在预训练时依赖人类操作员收集的动作标签，限制了数据源和规模。我们创新性地从无标签的互联网视频中学习，首先通过VQ-VAE目标训练动作量化模型，学习图像帧间的离散潜在动作；接着预训练VLA模型，从观察和任务描述中预测这些潜在动作；最后在少量机器人操作数据上微调，实现从潜在动作到机器人动作的映射。实验证明，我们的方法在机器人操作策略训练上超越现有技术，并在真实世界操作任务中表现出色，包括语言条件、对象泛化和指令泛化。此外，仅基于人类操作视频的训练也显示出积极效果，为机器人基础模型利用网络规模数据提供了新可能。

> We introduce Latent Action Pretraining for general Action models (LAPA), an unsupervised method for pretraining Vision-Language-Action (VLA) models without ground-truth robot action labels. Existing Vision-Language-Action models require action labels typically collected by human teleoperators during pretraining, which significantly limits possible data sources and scale. In this work, we propose a method to learn from internet-scale videos that do not have robot action labels. We first train an action quantization model leveraging VQ-VAE-based objective to learn discrete latent actions between image frames, then pretrain a latent VLA model to predict these latent actions from observations and task descriptions, and finally finetune the VLA on small-scale robot manipulation data to map from latent to robot actions. Experimental results demonstrate that our method significantly outperforms existing techniques that train robot manipulation policies from large-scale videos. Furthermore, it outperforms the state-of-the-art VLA model trained with robotic action labels on real-world manipulation tasks that require language conditioning, generalization to unseen objects, and semantic generalization to unseen instructions. Training only on human manipulation videos also shows positive transfer, opening up the potential for leveraging web-scale data for robotics foundation model.

[Arxiv](https://arxiv.org/abs/2410.11758)