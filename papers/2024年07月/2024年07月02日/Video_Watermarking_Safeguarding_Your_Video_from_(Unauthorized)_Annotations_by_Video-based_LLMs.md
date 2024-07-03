# 视频水印技术：保护您的视频内容，防止基于视频的 LLM 进行未经授权的注释。

发布时间：2024年07月02日

`LLM应用` `视频安全` `数字版权保护`

> Video Watermarking: Safeguarding Your Video from (Unauthorized) Annotations by Video-based LLMs

# 摘要

> 随着基于视频的 LLM 的兴起，视频理解能力得到了显著提升，但同时也带来了数据保护的安全隐患。本文提出的视频水印技术，通过在关键帧中巧妙嵌入水印，有效防止了未经授权的标注行为，尤其针对视频内容和描述。该技术不仅保持了视频的观赏体验，还通过多模态流式损失确保了水印的隐秘性和鲁棒性。实验证明，视频水印能显著降低 LLM 对视频的理解能力，为视频内容的安全提供了坚实保障，确保了其在不断进步的 LLM 技术中的完整性和保密性。

> The advent of video-based Large Language Models (LLMs) has significantly enhanced video understanding. However, it has also raised some safety concerns regarding data protection, as videos can be more easily annotated, even without authorization. This paper introduces Video Watermarking, a novel technique to protect videos from unauthorized annotations by such video-based LLMs, especially concerning the video content and description, in response to specific queries. By imperceptibly embedding watermarks into key video frames with multi-modal flow-based losses, our method preserves the viewing experience while preventing misuse by video-based LLMs. Extensive experiments show that Video Watermarking significantly reduces the comprehensibility of videos with various video-based LLMs, demonstrating both stealth and robustness. In essence, our method provides a solution for securing video content, ensuring its integrity and confidentiality in the face of evolving video-based LLMs technologies.

[Arxiv](https://arxiv.org/abs/2407.02411)