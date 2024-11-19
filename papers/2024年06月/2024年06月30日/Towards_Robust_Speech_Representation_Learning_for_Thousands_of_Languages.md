# 朝着实现数千种语言的稳健语音表示学习迈进

发布时间：2024年06月30日

`LLM应用` `语音技术` `自监督学习`

> Towards Robust Speech Representation Learning for Thousands of Languages

# 摘要

> 摘要：自监督学习（SSL）降低了对有标签数据的依赖，助力将语音技术拓展至更多语言。但模型距离支持全球 7000 多种语言仍有很大差距。我们推出了 XEUS，这是一种通用语音的跨语言编码器，基于超过 100 万小时、涵盖 4057 种语言的数据进行训练，使 SSL 模型的语言覆盖范围扩大了 4 倍。我们把现有公开语料库中的 100 万小时语音与新创建的来自 4057 种语言的 7400 多小时语料库加以整合，这些都将公开发布。为应对多语言语音数据的多样状况，我们在常见的 SSL 掩码预测方式中新增了去混响目标，增强了鲁棒性。我们在若干基准上对 XEUS 进行评估，结果显示它在各类任务中始终优于或与最先进（SOTA）的 SSL 模型表现相当。XEUS 在 ML-SUPERB 基准测试中创造了新的 SOTA：尽管参数或预训练数据较少，但分别比 MMS 1B 和 w2v-BERT 2.0 v2 高出 0.8％和 4.4％。检查点、代码和数据可在这个 https URL 中获取。

> 
Abstract:Self-supervised learning (SSL) has helped extend speech technologies to more languages by reducing the need for labeled data. However, models are still far from supporting the world's 7000+ languages. We propose XEUS, a Cross-lingual Encoder for Universal Speech, trained on over 1 million hours of data across 4057 languages, extending the language coverage of SSL models 4-fold. We combine 1 million hours of speech from existing publicly accessible corpora with a newly created corpus of 7400+ hours from 4057 languages, which will be publicly released. To handle the diverse conditions of multilingual speech data, we augment the typical SSL masked prediction approach with a novel dereverberation objective, increasing robustness. We evaluate XEUS on several benchmarks, and show that it consistently outperforms or achieves comparable results to state-of-the-art (SOTA) SSL models across a variety of tasks. XEUS sets a new SOTA on the ML-SUPERB benchmark: it outperforms MMS 1B and w2v-BERT 2.0 v2 by 0.8% and 4.4% respectively, despite having less parameters or pre-training data. Checkpoints, code, and data are found in this https URL.
    

[Arxiv](https://arxiv.org/pdf/2407.00837)