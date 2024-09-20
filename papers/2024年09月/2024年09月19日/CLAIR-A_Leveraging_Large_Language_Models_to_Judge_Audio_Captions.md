# CLAIR-A：借助大型语言模型，精准评判音频字幕

发布时间：2024年09月19日

`LLM应用` `音频处理`

> CLAIR-A: Leveraging Large Language Models to Judge Audio Captions

# 摘要

> 自动音频字幕 (AAC) 任务要求模型生成音频的自然语言描述。评估这些机器生成的字幕涉及听觉场景理解、声音对象推理、时间一致性和环境背景等多重因素。现有方法虽关注特定方面，但难以提供与人类判断一致的整体评分。为此，我们提出 CLAIR-A，一种利用大型语言模型 (LLM) 零-shot 能力，通过直接请求语义距离评分来评估音频字幕的简单灵活方法。评估显示，CLAIR-A 在预测人类判断方面优于传统指标，相对准确性提升 5.8%（对比 FENSE 指标），在 Clotho-Eval 数据集上提升 11%（对比最佳通用度量）。此外，CLAIR-A 通过语言模型解释评分背后的推理，提供更高透明度，其解释在人类评估者中评分高出基线方法 30%。CLAIR-A 已在 https://github.com/DavidMChan/clair-a 公开发布。

> The Automated Audio Captioning (AAC) task asks models to generate natural language descriptions of an audio input. Evaluating these machine-generated audio captions is a complex task that requires considering diverse factors, among them, auditory scene understanding, sound-object inference, temporal coherence, and the environmental context of the scene. While current methods focus on specific aspects, they often fail to provide an overall score that aligns well with human judgment. In this work, we propose CLAIR-A, a simple and flexible method that leverages the zero-shot capabilities of large language models (LLMs) to evaluate candidate audio captions by directly asking LLMs for a semantic distance score. In our evaluations, CLAIR-A better predicts human judgements of quality compared to traditional metrics, with a 5.8% relative accuracy improvement compared to the domain-specific FENSE metric and up to 11% over the best general-purpose measure on the Clotho-Eval dataset. Moreover, CLAIR-A offers more transparency by allowing the language model to explain the reasoning behind its scores, with these explanations rated up to 30% better by human evaluators than those provided by baseline methods. CLAIR-A is made publicly available at https://github.com/DavidMChan/clair-a.

[Arxiv](https://arxiv.org/abs/2409.12962)