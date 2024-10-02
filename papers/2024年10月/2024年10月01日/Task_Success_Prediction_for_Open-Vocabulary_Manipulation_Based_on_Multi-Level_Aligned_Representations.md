# 开放词汇操作任务的成功预测，依赖于多层次对齐表示的精准分析。

发布时间：2024年10月01日

`LLM应用` `机器人` `计算机视觉`

> Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations

# 摘要

> 本研究探讨了如何通过操作前后的指令句子和自我视角图像，预测开放词汇操作任务的成功。传统方法，包括多模态大型语言模型 (MLLM)，往往难以捕捉对象的细节特征和位置变化。为此，我们提出了对比 $λ$-Repformer，通过图像与指令的对齐来预测任务成功。该方法融合了三种关键特征：保留局部图像信息、与自然语言对齐、以及通过自然语言结构化的特征。这使得模型能通过图像间的差异识别重要变化。实验结果表明，我们的方法在 RT-1 数据集和物理机器人平台上均优于现有方法，最佳模型在准确性上提升了 8.66 分。

> In this study, we consider the problem of predicting task success for open-vocabulary manipulation by a manipulator, based on instruction sentences and egocentric images before and after manipulation. Conventional approaches, including multimodal large language models (MLLMs), often fail to appropriately understand detailed characteristics of objects and/or subtle changes in the position of objects. We propose Contrastive $λ$-Repformer, which predicts task success for table-top manipulation tasks by aligning images with instruction sentences. Our method integrates the following three key types of features into a multi-level aligned representation: features that preserve local image information; features aligned with natural language; and features structured through natural language. This allows the model to focus on important changes by looking at the differences in the representation between two images. We evaluate Contrastive $λ$-Repformer on a dataset based on a large-scale standard dataset, the RT-1 dataset, and on a physical robot platform. The results show that our approach outperformed existing approaches including MLLMs. Our best model achieved an improvement of 8.66 points in accuracy compared to the representative MLLM-based model.

[Arxiv](https://arxiv.org/abs/2410.00436)