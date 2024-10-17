# MlingConf：大型语言模型多语言置信度估计的全面探索

发布时间：2024年10月16日

`LLM应用` `人工智能`

> MlingConf: A Comprehensive Study of Multilingual Confidence Estimation on Large Language Models

# 摘要

> LLM 的幻觉问题引发了对其可靠性的质疑，因此置信度估计显得尤为重要。然而，非英语语言的置信度估计研究尚不充分。本文通过全面调查多语言置信度估计 (MlingConf)，探讨了其在语言无关 (LA) 和语言特定 (LS) 任务中的表现及语言主导效应。实验发现，在 LA 任务中，英语的置信度估计优于其他语言；而在 LS 任务中，使用问题相关语言提示能提升多语言置信度估计的效果。这一发现启发了一种简单有效的本地化提示策略，显著提高了 LLM 在 LS 任务中的可靠性和准确性。

> The tendency of Large Language Models (LLMs) to generate hallucinations raises concerns regarding their reliability. Therefore, confidence estimations indicating the extent of trustworthiness of the generations become essential. However, current LLM confidence estimations in languages other than English remain underexplored. This paper addresses this gap by introducing a comprehensive investigation of Multilingual Confidence estimation (MlingConf) on LLMs, focusing on both language-agnostic (LA) and language-specific (LS) tasks to explore the performance and language dominance effects of multilingual confidence estimations on different tasks. The benchmark comprises four meticulously checked and human-evaluate high-quality multilingual datasets for LA tasks and one for the LS task tailored to specific social, cultural, and geographical contexts of a language. Our experiments reveal that on LA tasks English exhibits notable linguistic dominance in confidence estimations than other languages, while on LS tasks, using question-related language to prompt LLMs demonstrates better linguistic dominance in multilingual confidence estimations. The phenomena inspire a simple yet effective native-tone prompting strategy by employing language-specific prompts for LS tasks, effectively improving LLMs' reliability and accuracy on LS tasks.

[Arxiv](https://arxiv.org/abs/2410.12478)