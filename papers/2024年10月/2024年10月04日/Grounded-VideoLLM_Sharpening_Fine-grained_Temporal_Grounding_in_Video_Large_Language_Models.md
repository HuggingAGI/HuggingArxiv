# Grounded-VideoLLM：精炼视频大型语言模型中的细粒度时间定位

发布时间：2024年10月04日

`LLM应用` `视频分析` `人工智能`

> Grounded-VideoLLM: Sharpening Fine-grained Temporal Grounding in Video Large Language Models

# 摘要

> 视频大型语言模型（Video-LLMs）在粗粒度视频理解上表现出色，但在细粒度时间定位上却力不从心。为此，我们推出了 Grounded-VideoLLM，一种擅长细粒度视频时刻感知与推理的新型模型。我们发现，现有模型在细粒度理解上的不足源于缺乏有效的时间建模和时间戳表示。因此，我们通过增加时间流编码帧间关系，并引入富含时间知识的离散时间令牌来优化模型。训练方面，我们采用多阶段策略，从简单的视频字幕任务逐步过渡到复杂的时间定位任务。此外，我们还通过自动注释创建了一个基于时间定位的视频问答数据集，以提升模型的时间推理能力。实验结果显示，Grounded-VideoLLM 在细粒度定位任务中表现卓越，并展现出作为通用视频助手的巨大潜力。

> Video Large Language Models (Video-LLMs) have demonstrated remarkable capabilities in coarse-grained video understanding, however, they struggle with fine-grained temporal grounding. In this paper, we introduce Grounded-VideoLLM, a novel Video-LLM adept at perceiving and reasoning over specific video moments in a fine-grained manner. We identify that current Video-LLMs have limitations for fine-grained video understanding since they lack effective temporal modeling and timestamp representation. In light of this, we sharpen our model by incorporating (1) an additional temporal stream to encode the relationships between frames and (2) discrete temporal tokens enriched with specific time knowledge to represent timestamps. To optimize the training of Grounded-VideoLLM, we employ a multi-stage training scheme, beginning with simple video-captioning tasks and progressively introducing video temporal grounding tasks of increasing complexity. To further enhance Grounded-VideoLLM's temporal reasoning capability, we also curate a grounded VideoQA dataset by an automatic annotation pipeline. Extensive experiments demonstrate that Grounded-VideoLLM not only excels in fine-grained grounding tasks such as temporal sentence grounding, dense video captioning, and grounded VideoQA, but also shows great potential as a versatile video assistant for general video understanding.

[Arxiv](https://arxiv.org/abs/2410.03290)