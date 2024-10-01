# 揭秘个性：对话中可解释个性识别的新基准数据集

发布时间：2024年09月29日

`LLM应用` `心理健康` `数据挖掘`

> Revealing Personality Traits: A New Benchmark Dataset for Explainable Personality Recognition on Dialogues

# 摘要

> 人格识别旨在从用户数据中挖掘隐含的人格特质。现有研究多将其视为分类任务，却忽略了揭示人格特质背后的支持证据。本文提出“可解释人格识别”新任务，旨在揭示人格特质的推理过程。受人格理论启发，我们构建了“人格证据链”（CoPE）框架，从具体情境到短期状态再到长期特质，层层推理。基于此，我们创建了PersonalityEvd数据集，并设计了两个任务，要求模型不仅识别人格标签，还需提供支持证据。实验表明，揭示人格特质极具挑战，为未来研究提供了新思路。数据和代码已公开，详见https://github.com/Lei-Sun-RUC/PersonalityEvd。

> Personality recognition aims to identify the personality traits implied in user data such as dialogues and social media posts. Current research predominantly treats personality recognition as a classification task, failing to reveal the supporting evidence for the recognized personality. In this paper, we propose a novel task named Explainable Personality Recognition, aiming to reveal the reasoning process as supporting evidence of the personality trait. Inspired by personality theories, personality traits are made up of stable patterns of personality state, where the states are short-term characteristic patterns of thoughts, feelings, and behaviors in a concrete situation at a specific moment in time. We propose an explainable personality recognition framework called Chain-of-Personality-Evidence (CoPE), which involves a reasoning process from specific contexts to short-term personality states to long-term personality traits. Furthermore, based on the CoPE framework, we construct an explainable personality recognition dataset from dialogues, PersonalityEvd. We introduce two explainable personality state recognition and explainable personality trait recognition tasks, which require models to recognize the personality state and trait labels and their corresponding support evidence. Our extensive experiments based on Large Language Models on the two tasks show that revealing personality traits is very challenging and we present some insights for future research. Our data and code are available at https://github.com/Lei-Sun-RUC/PersonalityEvd.

[Arxiv](https://arxiv.org/abs/2409.19723)