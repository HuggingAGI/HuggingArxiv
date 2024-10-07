# AuroraCap：高效且强大的视频详细字幕生成工具，并带来全新的基准测试。

发布时间：2024年10月03日

`LLM应用` `视频内容` `人工智能`

> AuroraCap: Efficient, Performant Video Detailed Captioning and a New Benchmark

# 摘要

> 视频详细字幕生成旨在为视频内容提供全面且连贯的文本描述，对视频理解和生成至关重要。本文介绍的 AuroraCap 是一个基于大型多模态模型的视频字幕生成器，采用最简架构设计，并通过令牌合并策略有效减少长视频序列带来的开销，性能损失微乎其微。AuroraCap 在多个基准测试中表现优异，如在 Flickr30k 上 CIDEr 得分高达 88.9，超越了 GPT-4V 和 Gemini-1.5 Pro。然而，现有基准仅包含简短描述，限制了研究发展。为此，我们推出了 VDC，一个包含上千个精心注释字幕的详细字幕生成基准，并创新性地提出了 LLM 辅助的 VDCscore 指标，通过分而治之策略将长字幕评估简化为多个短问答对，实验证明该基准更贴合人类对字幕质量的判断。

> Video detailed captioning is a key task which aims to generate comprehensive and coherent textual descriptions of video content, benefiting both video understanding and generation. In this paper, we propose AuroraCap, a video captioner based on a large multimodal model. We follow the simplest architecture design without additional parameters for temporal modeling. To address the overhead caused by lengthy video sequences, we implement the token merging strategy, reducing the number of input visual tokens. Surprisingly, we found that this strategy results in little performance loss. AuroraCap shows superior performance on various video and image captioning benchmarks, for example, obtaining a CIDEr of 88.9 on Flickr30k, beating GPT-4V (55.3) and Gemini-1.5 Pro (82.2). However, existing video caption benchmarks only include simple descriptions, consisting of a few dozen words, which limits research in this field. Therefore, we develop VDC, a video detailed captioning benchmark with over one thousand carefully annotated structured captions. In addition, we propose a new LLM-assisted metric VDCscore for bettering evaluation, which adopts a divide-and-conquer strategy to transform long caption evaluation into multiple short question-answer pairs. With the help of human Elo ranking, our experiments show that this benchmark better correlates with human judgments of video detailed captioning quality.

[Arxiv](https://arxiv.org/abs/2410.03051)