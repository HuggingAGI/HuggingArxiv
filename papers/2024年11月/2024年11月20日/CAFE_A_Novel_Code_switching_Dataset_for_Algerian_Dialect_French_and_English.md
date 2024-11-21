# CAFE  一个针对阿尔及利亚方言中法语和英语的全新代码切换数据集

发布时间：2024年11月20日

`其他` `语音识别` `数据处理`

> CAFE A Novel Code switching Dataset for Algerian Dialect French and English

# 摘要

> 这篇论文介绍并公开推出了（接收后可获取数据下载链接）CAFE——首个在阿尔及利亚方言、法语和英语之间进行代码切换的数据集。CAFE 语音数据独具特色，原因在于（a）它在真实的人与人对话中捕捉到了诸如代码切换和重叠语音等自然的说话风格现象，（b）应对了北非阿拉伯方言中的独特语言挑战；（c）CAFE 在不同的社会语言情境下捕捉到了来自阿尔及利亚不同地区的方言变化。CAFE 数据约有 37 小时的语音，其中一个子集 CAFE-small 时长 2 小时 36 分钟，并附带了人工标注，涵盖语音分割、转录、代码切换点的明确标注、重叠语音以及诸如噪音、笑声等其他事件。其余约 34.58 小时包含伪标签转录。除了发布数据，论文还指出了使用像 Whisper large-v2,3 和 PromptingWhisper 这样的先进自动语音识别（ASR）模型处理此类内容时面临的挑战。随后，我们用上述 Whisper 模型对 CAFE 数据进行基准测试，展示了精心设计的数据处理流程和先进的解码技术如何将 ASR 性能提升至混合错误率（MER）0.310、字符错误率（CER）0.329 以及单词错误率（WER）0.538 的水平。

> The paper introduces and publicly releases (Data download link available after acceptance) CAFE -- the first Code-switching dataset between Algerian dialect, French, and english languages. The CAFE speech data is unique for (a) its spontaneous speaking style in vivo human-human conversation capturing phenomena like code-switching and overlapping speech, (b) addresses distinct linguistic challenges in North African Arabic dialect; (c) the CAFE captures dialectal variations from various parts of Algeria within different sociolinguistic contexts. CAFE data contains approximately 37 hours of speech, with a subset, CAFE-small, of 2 hours and 36 minutes released with manual human annotation including speech segmentation, transcription, explicit annotation of code-switching points, overlapping speech, and other events such as noises, and laughter among others. The rest approximately 34.58 hours contain pseudo label transcriptions. In addition to the data release, the paper also highlighted the challenges of using state-of-the-art Automatic Speech Recognition (ASR) models such as Whisper large-v2,3 and PromptingWhisper to handle such content. Following, we benchmark CAFE data with the aforementioned Whisper models and show how well-designed data processing pipelines and advanced decoding techniques can improve the ASR performance in terms of Mixed Error Rate (MER) of 0.310, Character Error Rate (CER) of 0.329 and Word Error Rate (WER) of 0.538.

[Arxiv](https://arxiv.org/abs/2411.13424)