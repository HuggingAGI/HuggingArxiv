# 用眼动追踪和大型语言模型，探索你的阅读轨迹

发布时间：2024年09月28日

`LLM应用` `用户体验`

> See Where You Read with Eye Gaze Tracking and Large Language Model

# 摘要

> 行切换时丢失阅读进度令人烦恼。眼动追踪技术通过高亮已读段落，帮助用户避免误切行，但精度与行距的差距使其难以直接应用。现有方法在跳读时失效。本文提出支持线性和跳读的追踪系统。基于16名用户的注视研究，设计两种误差模型，实现跳读检测与重定位。系统还利用大语言模型的上下文感知能力，并利用行-注视对齐机会，实现动态校准。实验显示，线性阅读追踪可靠，跳读追踪准确率达84%。18名志愿者的实地测试证明，该系统有效提升阅读效率和用户体验。

> Losing track of reading progress during line switching can be frustrating. Eye gaze tracking technology offers a potential solution by highlighting read paragraphs, aiding users in avoiding wrong line switches. However, the gap between gaze tracking accuracy (2-3 cm) and text line spacing (3-5 mm) makes direct application impractical. Existing methods leverage the linear reading pattern but fail during jump reading. This paper presents a reading tracking and highlighting system that supports both linear and jump reading. Based on experimental insights from the gaze nature study of 16 users, two gaze error models are designed to enable both jump reading detection and relocation. The system further leverages the large language model's contextual perception capability in aiding reading tracking. A reading tracking domain-specific line-gaze alignment opportunity is also exploited to enable dynamic and frequent calibration of the gaze results. Controlled experiments demonstrate reliable linear reading tracking, as well as 84% accuracy in tracking jump reading. Furthermore, real field tests with 18 volunteers demonstrated the system's effectiveness in tracking and highlighting read paragraphs, improving reading efficiency, and enhancing user experience.

[Arxiv](https://arxiv.org/abs/2409.19454)