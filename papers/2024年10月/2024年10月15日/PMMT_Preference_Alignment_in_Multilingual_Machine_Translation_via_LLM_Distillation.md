# PMMT：利用 LLM 蒸馏技术，实现多语言机器翻译中的偏好对齐

发布时间：2024年10月15日

`LLM应用` `机器翻译`

> PMMT: Preference Alignment in Multilingual Machine Translation via LLM Distillation

# 摘要

> 翻译是跨语言交流的关键，尽管在提高准确性方面已有很多努力，但在匹配人类偏好（如语调和风格）方面投入较少。本文提出一种新方法，利用 LLM 生成符合特定偏好的大规模多语言平行语料库，并设计自动化流程，将人类偏好融入小型 MT 模型，以高效支持在线服务。实验显示，该方法在符合人类偏好的翻译任务中表现卓越，同时在未训练的 WMT 和 Flores 等基准上也展现出强劲竞争力。

> Translation is important for cross-language communication, and many efforts have been made to improve its accuracy. However, less investment is conducted in aligning translations with human preferences, such as translation tones or styles. In this paper, a new method is proposed to effectively generate large-scale multilingual parallel corpora with specific translation preferences using Large Language Models (LLMs). Meanwhile, an automatic pipeline is designed to distill human preferences into smaller Machine Translation (MT) models for efficiently and economically supporting large-scale calls in online services. Experiments indicate that the proposed method takes the lead in translation tasks with aligned human preferences by a large margin. Meanwhile, on popular public benchmarks like WMT and Flores, on which our models were not trained, the proposed method also shows a competitive performance compared to SOTA works.

[Arxiv](https://arxiv.org/abs/2410.11410)