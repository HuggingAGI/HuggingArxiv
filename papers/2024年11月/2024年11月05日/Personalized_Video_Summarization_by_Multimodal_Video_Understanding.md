# 通过多模态视频理解实现个性化视频摘要

发布时间：2024年11月05日

`LLM应用` `用户偏好`

> Personalized Video Summarization by Multimodal Video Understanding

# 摘要

> 视频摘要技术已被证明在访问和理解视频内容方面能够改善整体用户体验。如果已知用户的偏好，视频摘要可以从输入视频中识别出重要信息或相关内容，帮助他们获取必要的信息或确定他们对观看原始视频的兴趣。使视频摘要适应各种类型的视频和用户偏好需要大量的训练数据和昂贵的人工标注。为了促进此类研究，我们提出了一个用于视频摘要的新基准，它涵盖了各种用户偏好。此外，我们提出了一个名为“具有语言的视频摘要（VSL）”的管道，用于基于预训练的视觉语言模型（VLMs）的用户偏好视频摘要，以避免需要在大型训练数据集上训练视频摘要系统。该管道将视频和隐藏字幕作为输入，并通过将视频帧转换为文本来在场景级别进行语义分析。随后，用户的类型偏好被用作选择相关文本场景的基础。实验结果表明，我们提出的管道优于当前最先进的无监督视频摘要模型。我们表明，与基于监督查询的视频摘要模型相比，我们的方法在不同数据集上更具适应性。最后，运行时分析表明，当增加用户偏好和视频的数量时，我们的管道更适合实际使用。

> Video summarization techniques have been proven to improve the overall user experience when it comes to accessing and comprehending video content. If the user's preference is known, video summarization can identify significant information or relevant content from an input video, aiding them in obtaining the necessary information or determining their interest in watching the original video. Adapting video summarization to various types of video and user preferences requires significant training data and expensive human labeling. To facilitate such research, we proposed a new benchmark for video summarization that captures various user preferences. Also, we present a pipeline called Video Summarization with Language (VSL) for user-preferred video summarization that is based on pre-trained visual language models (VLMs) to avoid the need to train a video summarization system on a large training dataset. The pipeline takes both video and closed captioning as input and performs semantic analysis at the scene level by converting video frames into text. Subsequently, the user's genre preference was used as the basis for selecting the pertinent textual scenes. The experimental results demonstrate that our proposed pipeline outperforms current state-of-the-art unsupervised video summarization models. We show that our method is more adaptable across different datasets compared to supervised query-based video summarization models. In the end, the runtime analysis demonstrates that our pipeline is more suitable for practical use when scaling up the number of user preferences and videos.

[Arxiv](https://arxiv.org/abs/2411.03531)