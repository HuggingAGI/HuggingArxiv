# BiosERC：结合 LLM 支持的传记演讲者，助力 ERC 任务

发布时间：2024年07月05日

`LLM应用` `情感识别` `对话系统`

> BiosERC: Integrating Biography Speakers Supported by LLMs for ERC Tasks

# 摘要

> 在对话情感识别领域，我们通过探索说话者间的语句关系，利用注意力机制模拟情感互动。然而，说话者的个性特征等属性尚未深入研究，且在跨任务应用和模型兼容性方面存在挑战。为此，我们提出了BiosERC框架，深入分析对话中的说话者特征。借助大型语言模型，我们提取说话者的“传记信息”，作为模型情感标签分类的补充知识。该方法在IEMOCAP、MELD和EmoryNLP三大数据集上创下佳绩，彰显了模型的卓越性能和广泛适用性。源代码已公开，供研究者参考。

> In the Emotion Recognition in Conversation task, recent investigations have utilized attention mechanisms exploring relationships among utterances from intra- and inter-speakers for modeling emotional interaction between them. However, attributes such as speaker personality traits remain unexplored and present challenges in terms of their applicability to other tasks or compatibility with diverse model architectures. Therefore, this work introduces a novel framework named BiosERC, which investigates speaker characteristics in a conversation. By employing Large Language Models (LLMs), we extract the "biographical information" of the speaker within a conversation as supplementary knowledge injected into the model to classify emotional labels for each utterance. Our proposed method achieved state-of-the-art (SOTA) results on three famous benchmark datasets: IEMOCAP, MELD, and EmoryNLP, demonstrating the effectiveness and generalization of our model and showcasing its potential for adaptation to various conversation analysis tasks. Our source code is available at https://github.com/yingjie7/BiosERC.

![BiosERC：结合 LLM 支持的传记演讲者，助力 ERC 任务](../../../paper_images/2407.04279/x1.png)

![BiosERC：结合 LLM 支持的传记演讲者，助力 ERC 任务](../../../paper_images/2407.04279/x2.png)

[Arxiv](https://arxiv.org/abs/2407.04279)