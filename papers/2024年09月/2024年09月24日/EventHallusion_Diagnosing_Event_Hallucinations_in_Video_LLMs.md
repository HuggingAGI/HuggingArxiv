# EventHallusion：揭秘视频 LLM 中的事件幻觉

发布时间：2024年09月24日

`LLM应用` `视频理解` `人工智能`

> EventHallusion: Diagnosing Event Hallucinations in Video LLMs

# 摘要

> 近期，多模态大型语言模型（MLLM）在视频理解领域取得了显著进展。尽管这些模型在内容推理和指令遵循方面表现出色，但其幻觉问题在视频领域的研究仍不如图像领域深入。为此，我们提出了 EventHallusion，一个专注于评估视频事件理解中幻觉现象的新基准。通过精心设计的视频和问题，我们引导模型基于先验知识而非准确理解视频内容来解释事件。同时，我们提出了时间对比解码（TCD）方法，通过比较原始视频与时间线索被打乱的构造视频，有效抑制模型对先验知识的依赖。实验表明，开源模型在幻觉问题上表现较差，而闭源模型则表现优异。通过应用 TCD 方法，开源模型在 EventHallusion 基准上取得了显著的性能提升。相关代码和数据已公开，详见 https://github.com/Stevetich/EventHallusion。

> Recently, Multimodal Large Language Models (MLLMs) have made significant progress in the video comprehension field. Despite remarkable content reasoning and instruction following capabilities they demonstrated, the hallucination problem of these VideoLLMs is less explored compared with its counterpart in the image domain. To mitigate this gap, we first propose EventHallusion, a novel benchmark that focuses on assessing the VideoLMMs' hallucination phenomenon on video event comprehension. Based on the observation that existing VideoLLMs are entangled with the priors stemming from their foundation models, our EventHallusion is curated by meticulously collecting videos and annotating questions to intentionally mislead the VideoLLMs into interpreting events based on these priors rather than accurately understanding the video content. On the other hand, we also propose a simple yet effective method, called Temporal Contrastive Decoding (TCD), to tackle the hallucination problems of VideoLLMs. The proposed TCD suppresses the model's preference toward their priors by comparing the original video with a constructed counterpart, whose temporal cues are disrupted, during the autoregressive decoding stage. Through comprehensive evaluation of eight open-source and two closed-source VideoLLMs on the proposed EventHallusion benchmark, we find that the open-source models suffer significantly from hallucination problems, whereas the closed-source models perform markedly better. By further equipping open-sourced VideoLLMs with the proposed TCD approach, evident performance improvements are achieved across most metrics in the EventHallusion benchmark. Our codes and benchmark data are available at https://github.com/Stevetich/EventHallusion.

[Arxiv](https://arxiv.org/abs/2409.16597)