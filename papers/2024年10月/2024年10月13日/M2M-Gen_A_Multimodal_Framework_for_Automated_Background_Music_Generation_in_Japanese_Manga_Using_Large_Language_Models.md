# M2M-Gen：一个利用大型语言模型自动为日本漫画生成背景音乐的多模态框架

发布时间：2024年10月13日

`LLM应用`

> M2M-Gen: A Multimodal Framework for Automated Background Music Generation in Japanese Manga Using Large Language Models

# 摘要

> 本文推出 M2M Gen，一个专为日本漫画定制背景音乐的多模态框架。面对缺乏数据集和基线的挑战，我们设计了自动音乐生成流程。首先，通过漫画对话和角色表情分析场景情感，再由 GPT4o 转化为音乐指令。随后，GPT 4o 生成音乐字幕，指导模型创作与漫画情节同步的音乐。大量主观评估证实，M2M Gen 生成的音乐在质量、相关性和一致性上均超越基线，完美契合漫画场景。

> This paper introduces M2M Gen, a multi modal framework for generating background music tailored to Japanese manga. The key challenges in this task are the lack of an available dataset or a baseline. To address these challenges, we propose an automated music generation pipeline that produces background music for an input manga book. Initially, we use the dialogues in a manga to detect scene boundaries and perform emotion classification using the characters faces within a scene. Then, we use GPT4o to translate this low level scene information into a high level music directive. Conditioned on the scene information and the music directive, another instance of GPT 4o generates page level music captions to guide a text to music model. This produces music that is aligned with the mangas evolving narrative. The effectiveness of M2M Gen is confirmed through extensive subjective evaluations, showcasing its capability to generate higher quality, more relevant and consistent music that complements specific scenes when compared to our baselines.

[Arxiv](https://arxiv.org/abs/2410.09928)