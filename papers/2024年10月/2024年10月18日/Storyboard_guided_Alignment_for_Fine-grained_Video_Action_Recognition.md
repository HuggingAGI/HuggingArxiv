# 故事板引导的对齐技术，助力细粒度视频动作识别

发布时间：2024年10月18日

`LLM应用` `视频分析`

> Storyboard guided Alignment for Fine-grained Video Action Recognition

# 摘要

> 细粒度视频动作识别可视为视频与文本的匹配问题。传统方法常依赖全局视频语义整合嵌入，但因缺乏对动作细节的理解，易导致视频与文本对的不匹配。为此，我们提出多粒度框架，基于两点观察：一是不同视频可能共享相似的微观动作或外观；二是视频中的微观动作可能短暂、缓慢，甚至与整体语义无关。借鉴故事板将剧本拆解为单个镜头的思路，我们用预训练大模型生成细粒度描述，增强全局语义。通过筛选与视频中微观动作匹配的描述，我们能更精准地识别关键帧，优化嵌入。实验证明，该方法在监督、少样本和零样本场景下均表现出色。

> Fine-grained video action recognition can be conceptualized as a video-text matching problem. Previous approaches often rely on global video semantics to consolidate video embeddings, which can lead to misalignment in video-text pairs due to a lack of understanding of action semantics at an atomic granularity level. To tackle this challenge, we propose a multi-granularity framework based on two observations: (i) videos with different global semantics may share similar atomic actions or appearances, and (ii) atomic actions within a video can be momentary, slow, or even non-directly related to the global video semantics. Inspired by the concept of storyboarding, which disassembles a script into individual shots, we enhance global video semantics by generating fine-grained descriptions using a pre-trained large language model. These detailed descriptions capture common atomic actions depicted in videos. A filtering metric is proposed to select the descriptions that correspond to the atomic actions present in both the videos and the descriptions. By employing global semantics and fine-grained descriptions, we can identify key frames in videos and utilize them to aggregate embeddings, thereby making the embedding more accurate. Extensive experiments on various video action recognition datasets demonstrate superior performance of our proposed method in supervised, few-shot, and zero-shot settings.

[Arxiv](https://arxiv.org/abs/2410.14238)