# 借助上下文话语分析和大型语言模型来提升基于语音的情绪识别能力

发布时间：2024年10月27日

`LLM应用` `语音识别` `情感分析`

> Improving Speech-based Emotion Recognition with Contextual Utterance Analysis and LLMs

# 摘要

> 语音情感识别（SER）致力于从口语中辨别情感状态。2024 年 IEEE SLT-GenSEC 关于后自动语音识别（ASR）情感识别任务的挑战赛，要求参与者仅凭借文本数据来探究大型语言模型（LLMs）的情感识别能力。我们提出了一种创新的方法，先是对所有可用的转录加以优化，以保障数据的可靠性。接着，把每个完整的对话切分成较小的对话，并将这些对话当作上下文来预测对话里目标话语的情感。最后，我们对不同的上下文长度和提示技术展开研究，以提升预测的准确性。我们的最佳提交成果在未加权准确率方面超出基线 20％，在挑战赛中斩获最佳表现。我们所有实验的代码、预测结果和日志文件都可供公众获取。

> Speech Emotion Recognition (SER) focuses on identifying emotional states from spoken language. The 2024 IEEE SLT-GenSEC Challenge on Post Automatic Speech Recognition (ASR) Emotion Recognition tasks participants to explore the capabilities of large language models (LLMs) for emotion recognition using only text data. We propose a novel approach that first refines all available transcriptions to ensure data reliability. We then segment each complete conversation into smaller dialogues and use these dialogues as context to predict the emotion of the target utterance within the dialogue. Finally, we investigated different context lengths and prompting techniques to improve prediction accuracy. Our best submission exceeded the baseline by 20% in unweighted accuracy, achieving the best performance in the challenge. All our experiments' codes, prediction results, and log files are publicly available.

[Arxiv](https://arxiv.org/abs/2410.20334)