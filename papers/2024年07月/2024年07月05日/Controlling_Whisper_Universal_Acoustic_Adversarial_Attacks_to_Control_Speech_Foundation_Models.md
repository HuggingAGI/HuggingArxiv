# 操控“耳语”：针对语音基础模型实施的通用声学对抗策略

发布时间：2024年07月05日

`LLM应用` `语音识别`

> Controlling Whisper: Universal Acoustic Adversarial Attacks to Control Speech Foundation Models

# 摘要

> 语音基础模型，无论是灵活的语音识别系统还是音频提示的大型语言模型，正日益流行。这些模型的魅力之一在于它们能通过适当提示执行ASR之外的任务，如OpenAI的Whisper模型同时具备语音转录和翻译功能。然而，随着音频提示LLM的进步，我们发现这种灵活性可能使系统易受对抗攻击。即使不接触模型提示，通过调整音频输入也能改变系统行为。我们实验证明，只需在输入语音前加入一段通用对抗声学段，就能迫使ASR模型无视原提示。例如，我们成功操控Whisper，使其无视转录指令，始终执行翻译。这项研究揭示了多任务语音模型面临的新型对抗威胁，提醒我们在部署此类模型前需谨慎评估其安全性。

> Speech enabled foundation models, either in the form of flexible speech recognition based systems or audio-prompted large language models (LLMs), are becoming increasingly popular. One of the interesting aspects of these models is their ability to perform tasks other than automatic speech recognition (ASR) using an appropriate prompt. For example, the OpenAI Whisper model can perform both speech transcription and speech translation. With the development of audio-prompted LLMs there is the potential for even greater control options. In this work we demonstrate that with this greater flexibility the systems can be susceptible to model-control adversarial attacks. Without any access to the model prompt it is possible to modify the behaviour of the system by appropriately changing the audio input. To illustrate this risk, we demonstrate that it is possible to prepend a short universal adversarial acoustic segment to any input speech signal to override the prompt setting of an ASR foundation model. Specifically, we successfully use a universal adversarial acoustic segment to control Whisper to always perform speech translation, despite being set to perform speech transcription. Overall, this work demonstrates a new form of adversarial attack on multi-tasking speech enabled foundation models that needs to be considered prior to the deployment of this form of model.

![操控“耳语”：针对语音基础模型实施的通用声学对抗策略](../../../paper_images/2407.04482/main_figure.png)

![操控“耳语”：针对语音基础模型实施的通用声学对抗策略](../../../paper_images/2407.04482/bleu_vs_en_probability_fr.png)

![操控“耳语”：针对语音基础模型实施的通用声学对抗策略](../../../paper_images/2407.04482/bleu_vs_not_en_probability_fr.png)

![操控“耳语”：针对语音基础模型实施的通用声学对抗策略](../../../paper_images/2407.04482/p_en.png)

![操控“耳语”：针对语音基础模型实施的通用声学对抗策略](../../../paper_images/2407.04482/bleu_vs_en_probability_all.png)

![操控“耳语”：针对语音基础模型实施的通用声学对抗策略](../../../paper_images/2407.04482/bleu_vs_not_en_probability_all.png)

[Arxiv](https://arxiv.org/abs/2407.04482)