# SpeechVerse：一款大规模且具备广泛适用性的语音语言模型

发布时间：2024年05月13日

`LLM应用

这篇论文介绍了一个名为SpeechVerse的多任务训练框架，它结合了预训练的语音和文本模型，旨在提高大型语言模型在处理多样化语音处理任务上的性能。该框架通过使用语音基础模型的连续潜在表示进行指令微调，实现了在多个语音处理任务上的卓越零-shot性能。这与LLM应用的分类相符，因为它关注的是如何应用大型语言模型来解决实际的多模态感知问题，而不是探讨LLM的理论基础或Agent的设计与实现，也不是关于检索增强生成（RAG）技术的研究。` `语音处理` `多任务学习`

> SpeechVerse: A Large-scale Generalizable Audio Language Model

# 摘要

> 大型语言模型（LLMs）在处理需要深刻理解自然语言指令的任务时展现出了非凡的能力。然而，现有的多模态感知模型往往局限于特定的微调任务，如语音识别和翻译。为此，我们推出了SpeechVerse，一个结合了预训练语音和文本模型的多任务训练框架，通过少量可学习参数实现，同时保持预训练模型在训练过程中不变。通过使用语音基础模型的连续潜在表示进行指令微调，SpeechVerse在多样化的语音处理任务上实现了卓越的零-shot性能。我们进行了全面的基准测试，与传统模型在多个数据集和任务上进行了比较，并评估了模型对新颖指令的泛化能力。实验结果显示，SpeechVerse在11个任务中的9个上超越了传统特定任务基线，展现了其在多任务处理上的优越性。

> Large language models (LLMs) have shown incredible proficiency in performing tasks that require semantic understanding of natural language instructions. Recently, many works have further expanded this capability to perceive multimodal audio and text inputs, but their capabilities are often limited to specific fine-tuned tasks such as automatic speech recognition and translation. We therefore develop SpeechVerse, a robust multi-task training and curriculum learning framework that combines pre-trained speech and text foundation models via a small set of learnable parameters, while keeping the pre-trained models frozen during training. The models are instruction finetuned using continuous latent representations extracted from the speech foundation model to achieve optimal zero-shot performance on a diverse range of speech processing tasks using natural language instructions. We perform extensive benchmarking that includes comparing our model performance against traditional baselines across several datasets and tasks. Furthermore, we evaluate the model's capability for generalized instruction following by testing on out-of-domain datasets, novel prompts, and unseen tasks. Our empirical experiments reveal that our multi-task SpeechVerse model is even superior to conventional task-specific baselines on 9 out of the 11 tasks.

[Arxiv](https://arxiv.org/abs/2405.08295)