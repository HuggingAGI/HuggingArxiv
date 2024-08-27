# MEDSAGE：利用 LLM 生成的合成对话，提升医疗对话摘要对 ASR 错误的抗干扰能力

发布时间：2024年08月26日

`LLM应用` `语音识别`

> MEDSAGE: Enhancing Robustness of Medical Dialogue Summarization to ASR Errors with LLM-generated Synthetic Dialogues

# 摘要

> 自动语音识别（ASR）系统虽能将语音转录为文本，但其错误却可能严重损害下游任务如摘要的性能。在临床对话摘要这一低资源领域，由于缺乏足够的监督数据进行微调，ASR模型常被视为黑箱解决方案。传统的数据增强方法因缺乏足够的医疗对话音频录音和相应转录而难以实施。为此，我们提出MEDSAGE，一种利用大型语言模型（LLM）生成合成样本进行数据增强的方法。我们利用LLM的上下文学习能力，指导其根据有限的医疗对话示例生成类似ASR的错误。实验表明，LLM能有效模拟ASR噪声，将这些噪声数据融入训练过程，显著提升医疗对话摘要系统的鲁棒性与准确性。这一方法有效解决了关键应用中ASR输出噪声的问题，为临床对话摘要的可靠性提供了强有力的保障。

> Automatic Speech Recognition (ASR) systems are pivotal in transcribing speech into text, yet the errors they introduce can significantly degrade the performance of downstream tasks like summarization. This issue is particularly pronounced in clinical dialogue summarization, a low-resource domain where supervised data for fine-tuning is scarce, necessitating the use of ASR models as black-box solutions. Employing conventional data augmentation for enhancing the noise robustness of summarization models is not feasible either due to the unavailability of sufficient medical dialogue audio recordings and corresponding ASR transcripts. To address this challenge, we propose MEDSAGE, an approach for generating synthetic samples for data augmentation using Large Language Models (LLMs). Specifically, we leverage the in-context learning capabilities of LLMs and instruct them to generate ASR-like errors based on a few available medical dialogue examples with audio recordings. Experimental results show that LLMs can effectively model ASR noise, and incorporating this noisy data into the training process significantly improves the robustness and accuracy of medical dialogue summarization systems. This approach addresses the challenges of noisy ASR outputs in critical applications, offering a robust solution to enhance the reliability of clinical dialogue summarization.

[Arxiv](https://arxiv.org/abs/2408.14418)