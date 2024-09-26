# 开启听觉大型语言模型，助力自动语音质量评估

发布时间：2024年09月25日

`LLM应用` `语音技术`

> Enabling Auditory Large Language Models for Automatic Speech Quality Evaluation

# 摘要

> 语音质量评估涉及多个方面，如MOS和SIM，这对单一任务的小模型来说颇具挑战。本文提出利用最新的听觉大型语言模型（LLM）进行自动评估。通过任务特定提示，听觉LLM被微调以预测MOS、SIM及A/B测试结果，这些常用于评估TTS系统。此外，微调后的LLM能生成自然语言描述，评估噪声、失真等，提供更易理解的输出。在NISQA、BVCC等数据集上，使用SALMONN等开源LLM进行了广泛实验，并评估了Google Gemini 1.5 Pro。结果显示，听觉LLM在MOS和SIM预测上与顶尖小模型相当，同时在A/B测试和自然语言描述方面表现出色。相关数据处理脚本和模型检查点将在接受后发布。

> Speech quality assessment typically requires evaluating audio from multiple aspects, such as mean opinion score (MOS) and speaker similarity (SIM) etc., which can be challenging to cover using one small model designed for a single task. In this paper, we propose leveraging recently introduced auditory large language models (LLMs) for automatic speech quality assessment. By employing task-specific prompts, auditory LLMs are finetuned to predict MOS, SIM and A/B testing results, which are commonly used for evaluating text-to-speech systems. Additionally, the finetuned auditory LLM is able to generate natural language descriptions assessing aspects like noisiness, distortion, discontinuity, and overall quality, providing more interpretable outputs. Extensive experiments have been performed on the NISQA, BVCC, SOMOS and VoxSim speech quality datasets, using open-source auditory LLMs such as SALMONN, Qwen-Audio, and Qwen2-Audio. For the natural language descriptions task, a commercial model Google Gemini 1.5 Pro is also evaluated. The results demonstrate that auditory LLMs achieve competitive performance compared to state-of-the-art task-specific small models in predicting MOS and SIM, while also delivering promising results in A/B testing and natural language descriptions. Our data processing scripts and finetuned model checkpoints will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2409.16644)