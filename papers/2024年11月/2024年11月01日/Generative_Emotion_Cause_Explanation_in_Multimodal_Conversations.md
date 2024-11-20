# 多模态对话中的生成式情感原因阐释

发布时间：2024年11月01日

`LLM应用` `多模态对话` `情感分析`

> Generative Emotion Cause Explanation in Multimodal Conversations

# 摘要

> 多模态对话是人类交流的重要形式，蕴含丰富情感内容，对其情感成因的探究是一项意义重大的研究工作。然而，现有的情感成因研究往往采用从句选择法来定位原因话语，却未对情感成因给出详尽解释。本文提出了一个新任务——	extbf{多模态对话情感成因解释（MCECE）}，旨在为多模态对话场景中的目标话语生成情感成因的详细阐释。基于 MELD 数据集，我们构建了新的数据集（ECEM），它将视频片段与角色情感的详细解释相融合，有利于深入探究多模态对话中情感表达的因果因素。还提出了一种新颖的方法——FAME-Net，它借助大型语言模型（LLMs）的力量分析视觉数据，精准解读视频中通过面部表情传递的情感。利用面部情感的传染效应，FAME-Net 有效地捕捉到了参与对话者的情感成因。在新构建的数据集上的实验结果表明，FAME-Net 显著优于几个出色的大型语言模型基线。代码和数据集可在 url{https://github.com/3222345200/ECEMdataset.git}获取。

> Multimodal conversation, a crucial form of human communication, carries rich emotional content, making the exploration of the causes of emotions within it a research endeavor of significant importance. However, existing research on the causes of emotions typically uses clause selection methods to locate the reason utterance, without providing a detailed explanation of the emotional causes. In this paper, we propose a new task, \textbf{M}ultimodal \textbf{C}onversation \textbf{E}motion \textbf{C}ause \textbf{E}xplanation (MCECE), aiming to generate a detailed explanation of the emotional cause to the target utterance within a multimodal conversation scenario. Building upon the MELD dataset, we develop a new dataset (ECEM) that integrates video clips with detailed explanations of character emotions, facilitating an in-depth examination of the causal factors behind emotional expressions in multimodal conversations.A novel approach, FAME-Net, is further proposed, that harnesses the power of Large Language Models (LLMs) to analyze visual data and accurately interpret the emotions conveyed through facial expressions in videos. By exploiting the contagion effect of facial emotions, FAME-Net effectively captures the emotional causes of individuals engaged in conversations. Our experimental results on the newly constructed dataset show that FAME-Net significantly outperforms several excellent large language model baselines. Code and dataset are available at url{https://github.com/3222345200/ECEMdataset.git}

[Arxiv](https://arxiv.org/abs/2411.02430)