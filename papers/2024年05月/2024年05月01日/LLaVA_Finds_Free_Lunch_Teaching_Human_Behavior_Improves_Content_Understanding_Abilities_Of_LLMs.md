# LLaVA 揭示了一个意外的收获：通过教授人类行为，我们能够显著提升大型语言模型对内容的理解力。

发布时间：2024年05月01日

`LLM应用` `机器学习`

> LLaVA Finds Free Lunch: Teaching Human Behavior Improves Content Understanding Abilities Of LLMs

# 摘要

> 通信即是“谁向谁传达了什么信息，产生了何种影响”。信息发送者的消息会在接收者端引发连锁反应，即行为。这些行为作为信息传递的结果，蕴含了丰富的信号。尽管如此，行为数据在大型语言模型的训练过程中常被忽视。本研究揭示，基于接收者行为对大型语言模型进行训练可以有效提升其对内容的理解力。具体而言，我们发现通过训练模型预测点赞和评论等接收者行为，能够显著提高其在多种下游内容理解任务上的表现。这一提升在23个基准数据集上的40个视频和图像理解任务中得到了验证，无论是零样本还是微调场景，均超越了众多监督学习基线。更重要的是，点赞和评论等接收者行为在互联网上自动收集，无需人工标注即可发挥作用，因此，利用这些数据进行训练所带来的性能提升可谓是意外的收获。我们还公开了从多个平台收集的750k图像和视频的接收者行为数据，包括清理后的评论和点赞，以及我们的指令调整数据集。

> Communication is defined as ``Who says what to whom with what effect.'' A message from a communicator generates downstream receiver effects, also known as behavior. Receiver behavior, being a downstream effect of the message, carries rich signals about it. Even after carrying signals about the message, the behavior data is often ignored while training large language models. We show that training LLMs on receiver behavior can actually help improve their content-understanding abilities. Specifically, we show that training LLMs to predict the receiver behavior of likes and comments improves the LLM's performance on a wide variety of downstream content understanding tasks. We show this performance increase over 40 video and image understanding tasks over 23 benchmark datasets across both 0-shot and fine-tuning settings, outperforming many supervised baselines. Moreover, since receiver behavior, such as likes and comments, is collected by default on the internet and does not need any human annotations to be useful, the performance improvement we get after training on this data is essentially free-lunch. We release the receiver behavior cleaned comments and likes of 750k images and videos collected from multiple platforms along with our instruction-tuning data.

[Arxiv](https://arxiv.org/abs/2405.00942)