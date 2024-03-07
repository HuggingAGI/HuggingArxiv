# [GPTSee 利用描述性相似性特征提升关键时刻检索与精彩片段检测能力](https://arxiv.org/abs/2403.01437)

发布时间：2024年03月03日

`LLM应用`

> GPTSee: Enhancing Moment Retrieval and Highlight Detection via Description-Based Similarity Features

> MR和HD技术致力于通过自然语言查询定位视频中的关键时刻和精彩瞬间，而LLMs在各类视觉任务上展现出了不俗实力。但目前这两种技术尚未能有效融入LLMs的工作流程。本文创新性地提出了一种两步走模型，第一步是利用MiniGPT-4为视频帧生成详尽描述，并对查询语句进行改写，以新特征形式注入编码器。随后，计算生成描述与改写查询之间的语义关联程度。最后，将一系列高关联度视频帧转化为跨度锚点，作为解码器预测位置先验信息的基础。实验证明，这种方法达到当前最优效果，而且仅凭借跨度锚点和相似度得分便能实现比传统方法如Moment-DETR更精准的位置定位。

> Moment retrieval (MR) and highlight detection (HD) aim to identify relevant moments and highlights in video from corresponding natural language query. Large language models (LLMs) have demonstrated proficiency in various computer vision tasks. However, existing methods for MR\&HD have not yet been integrated with LLMs. In this letter, we propose a novel two-stage model that takes the output of LLMs as the input to the second-stage transformer encoder-decoder. First, MiniGPT-4 is employed to generate the detailed description of the video frame and rewrite the query statement, fed into the encoder as new features. Then, semantic similarity is computed between the generated description and the rewritten queries. Finally, continuous high-similarity video frames are converted into span anchors, serving as prior position information for the decoder. Experiments demonstrate that our approach achieves a state-of-the-art result, and by using only span anchors and similarity scores as outputs, positioning accuracy outperforms traditional methods, like Moment-DETR.