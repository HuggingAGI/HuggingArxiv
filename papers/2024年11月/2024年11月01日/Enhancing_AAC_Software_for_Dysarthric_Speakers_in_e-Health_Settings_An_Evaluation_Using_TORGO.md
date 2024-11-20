# 在电子健康环境中为构音障碍者优化 AAC 软件：基于 TORGO 的评估

发布时间：2024年11月01日

`LLM应用` `语音识别`

> Enhancing AAC Software for Dysarthric Speakers in e-Health Settings: An Evaluation Using TORGO

# 摘要

> 患有脑瘫（CP）和肌萎缩侧索硬化症（ALS）的人往往在发音上遭遇难题，引发构音障碍，形成非典型的言语模式。在医疗保健场景中，沟通不畅会降低护理质量。在构建增强和替代通信（AAC）工具以促进流畅交流时，我们发现像 Whisper 和 Wav2vec2.0 这类先进的自动语音识别（ASR）技术，很大程度上忽视了非典型说话者，主要原因是训练数据的缺失。我们的工作致力于借助 SOTA ASR 并结合特定领域的纠错。英语构音障碍 ASR 性能通常在 TORGO 数据集上评估。提示重叠是该数据集的一个常见问题，即训练和测试说话者之间存在短语重叠。我们的工作提出了一种打破这种提示重叠的算法。减少提示重叠后，使用 SOTA ASR 模型的结果显示，对于轻度和重度构音障碍的说话者，词错误率极高。此外，为改进 ASR，我们的工作探究了 n-gram 语言模型和基于大语言模型（LLM）的多模态生成纠错算法（如 Whispering-LLaMA）用于二次 ASR 的影响。我们的工作凸显出，要改善非典型说话者的 ASR 以实现面对面和电子健康环境中的公平医疗保健服务，还有大量工作亟待完成。

> Individuals with cerebral palsy (CP) and amyotrophic lateral sclerosis (ALS) frequently face challenges with articulation, leading to dysarthria and resulting in atypical speech patterns. In healthcare settings, coomunication breakdowns reduce the quality of care. While building an augmentative and alternative communication (AAC) tool to enable fluid communication we found that state-of-the-art (SOTA) automatic speech recognition (ASR) technology like Whisper and Wav2vec2.0 marginalizes atypical speakers largely due to the lack of training data. Our work looks to leverage SOTA ASR followed by domain specific error-correction. English dysarthric ASR performance is often evaluated on the TORGO dataset. Prompt-overlap is a well-known issue with this dataset where phrases overlap between training and test speakers. Our work proposes an algorithm to break this prompt-overlap. After reducing prompt-overlap, results with SOTA ASR models produce extremely high word error rates for speakers with mild and severe dysarthria. Furthermore, to improve ASR, our work looks at the impact of n-gram language models and large-language model (LLM) based multi-modal generative error-correction algorithms like Whispering-LLaMA for a second pass ASR. Our work highlights how much more needs to be done to improve ASR for atypical speakers to enable equitable healthcare access both in-person and in e-health settings.

[Arxiv](https://arxiv.org/abs/2411.00980)