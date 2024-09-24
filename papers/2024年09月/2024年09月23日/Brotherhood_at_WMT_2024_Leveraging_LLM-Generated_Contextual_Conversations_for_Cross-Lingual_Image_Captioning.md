# WMT 2024 兄弟会：借助 LLM 生成的上下文对话，实现跨语言图像描述

发布时间：2024年09月23日

`LLM应用` `多语言`

> Brotherhood at WMT 2024: Leveraging LLM-Generated Contextual Conversations for Cross-Lingual Image Captioning

# 摘要

> 本文中，我们以 Brotherhood 团队的名义，介绍了在英语到低资源多模态翻译任务中的系统。我们参与了英语与印地语、豪萨语、孟加拉语和马拉雅拉姆语的多模态翻译任务。我们利用 GPT-4o 和 Claude 3.5 Sonnet 等多模态大型语言模型，提出了一种无需传统训练或微调的跨语言图像描述增强方法。通过指令调整的提示，我们生成关于裁剪图像的丰富对话，并将其翻译成目标语言。最终，我们采用加权提示策略，结合原始英语描述与翻译对话，生成目标语言的描述。该方法在英语-印地语挑战集上获得了 37.90 BLEU 分数，并在英语-豪萨语的挑战和评估排行榜上分别排名第一和第二。此外，我们还对 250 张图像进行了实验，探讨了不同加权方案下 BLEU 分数与语义相似性之间的平衡。

> In this paper, we describe our system under the team name Brotherhood for the English-to-Lowres Multi-Modal Translation Task. We participate in the multi-modal translation tasks for English-Hindi, English-Hausa, English-Bengali, and English-Malayalam language pairs. We present a method leveraging multi-modal Large Language Models (LLMs), specifically GPT-4o and Claude 3.5 Sonnet, to enhance cross-lingual image captioning without traditional training or fine-tuning. Our approach utilizes instruction-tuned prompting to generate rich, contextual conversations about cropped images, using their English captions as additional context. These synthetic conversations are then translated into the target languages. Finally, we employ a weighted prompting strategy, balancing the original English caption with the translated conversation to generate captions in the target language. This method achieved competitive results, scoring 37.90 BLEU on the English-Hindi Challenge Set and ranking first and second for English-Hausa on the Challenge and Evaluation Leaderboards, respectively. We conduct additional experiments on a subset of 250 images, exploring the trade-offs between BLEU scores and semantic similarity across various weighting schemes.

[Arxiv](https://arxiv.org/abs/2409.15052)