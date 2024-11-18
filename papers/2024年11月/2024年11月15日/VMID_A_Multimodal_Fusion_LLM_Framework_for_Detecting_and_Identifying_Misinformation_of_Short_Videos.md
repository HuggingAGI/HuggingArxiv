# VMID：一个用于检测和识别短视频错误信息的多模态融合 LLM 框架

发布时间：2024年11月15日

`LLM应用` `短视频` `新闻检测`

> VMID: A Multimodal Fusion LLM Framework for Detecting and Identifying Misinformation of Short Videos

# 摘要

> 短视频平台已成为新闻传播的重要渠道，为用户获取时事、分享信息提供了极具吸引力且即时的方式。然而，这些平台也成了错误信息迅速传播的重要渠道，假新闻和谣言能借助短视频的视觉吸引力和广泛传播力在观众中大肆传播。现有的假新闻检测方法多依赖单模态信息，比如文本或图像，或者仅采用基础的融合技术，这限制了它们处理短视频复杂多层信息的能力。为解决这些局限，本文提出一种基于多模态信息的新型假新闻检测方法，旨在通过对视频内容的多层分析来识别错误信息。该方法有效利用不同的模态表示生成统一的文本描述，再输入大型语言模型进行综合评估。所提框架成功整合了视频中的多模态特征，大幅提升了假新闻检测的准确性和可靠性。实验结果显示，所提方法在准确性、鲁棒性和多模态信息利用上优于现有模型，准确率达 90.93%，远高于最佳基线模型（SV-FEND）的 81.05%。此外，案例研究为该方法能准确区分假新闻、辟谣内容和真实事件的有效性提供了更多证据，凸显了其在实际应用中的可靠性和鲁棒性。

> Short video platforms have become important channels for news dissemination, offering a highly engaging and immediate way for users to access current events and share information. However, these platforms have also emerged as significant conduits for the rapid spread of misinformation, as fake news and rumors can leverage the visual appeal and wide reach of short videos to circulate extensively among audiences. Existing fake news detection methods mainly rely on single-modal information, such as text or images, or apply only basic fusion techniques, limiting their ability to handle the complex, multi-layered information inherent in short videos. To address these limitations, this paper presents a novel fake news detection method based on multimodal information, designed to identify misinformation through a multi-level analysis of video content. This approach effectively utilizes different modal representations to generate a unified textual description, which is then fed into a large language model for comprehensive evaluation. The proposed framework successfully integrates multimodal features within videos, significantly enhancing the accuracy and reliability of fake news detection. Experimental results demonstrate that the proposed approach outperforms existing models in terms of accuracy, robustness, and utilization of multimodal information, achieving an accuracy of 90.93%, which is significantly higher than the best baseline model (SV-FEND) at 81.05%. Furthermore, case studies provide additional evidence of the effectiveness of the approach in accurately distinguishing between fake news, debunking content, and real incidents, highlighting its reliability and robustness in real-world applications.

[Arxiv](https://arxiv.org/abs/2411.10032)