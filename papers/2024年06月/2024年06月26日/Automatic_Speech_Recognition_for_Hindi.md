# 印地语自动语音识别探索

发布时间：2024年06月26日

`Agent

理由：这篇论文主要描述了一个自动语音识别（ASR）系统的开发和应用，包括网络应用的开发和语音识别界面的设计。这些内容涉及到构建一个能够处理语音数据并将其转换为文本的系统，这可以被视为一个Agent的行为，因为它涉及到对环境的感知（通过音频输入）和响应（通过文本输出）。此外，论文中提到的实时协作校正ASR转录和优化语音识别过程的技术细节，进一步强调了这是一个Agent系统的特征。虽然ASR技术可能与大型语言模型（LLM）有关，但论文的重点在于系统的应用和实现，而不是LLM的理论研究或特定于LLM的应用开发。因此，将其归类为Agent更为合适。` `语音识别` `网络应用`

> Automatic Speech Recognition for Hindi

# 摘要

> 自动语音识别（ASR）领域结合了语言学与机器学习，致力于开发让计算机将口语转换为文本的技术。ASR模型通过监督学习将语音转换为文本，需处理真实且无限制的文本，而依赖于大规模文本训练的语言模型。高质量转录数据对预测模型训练至关重要。研究包括开发网络应用和设计语音识别界面两大部分。该应用使用JavaScript和Node.js，管理音频文件及其转录，支持实时协作校正ASR转录。语音识别界面从设备记录16kHz音频，进行语音活动检测（VAD），并将音频发送到识别引擎，有效减少非语音时段的处理，节省VoIP应用中的计算和带宽。研究最终测试了神经网络，实现语音信号与HMM状态的精确对齐，采用了一种利用节点共激活统计的新反向传播方法。

> Automatic speech recognition (ASR) is a key area in computational linguistics, focusing on developing technologies that enable computers to convert spoken language into text. This field combines linguistics and machine learning. ASR models, which map speech audio to transcripts through supervised learning, require handling real and unrestricted text. Text-to-speech systems directly work with real text, while ASR systems rely on language models trained on large text corpora. High-quality transcribed data is essential for training predictive models. The research involved two main components: developing a web application and designing a web interface for speech recognition. The web application, created with JavaScript and Node.js, manages large volumes of audio files and their transcriptions, facilitating collaborative human correction of ASR transcripts. It operates in real-time using a client-server architecture. The web interface for speech recognition records 16 kHz mono audio from any device running the web app, performs voice activity detection (VAD), and sends the audio to the recognition engine. VAD detects human speech presence, aiding efficient speech processing and reducing unnecessary processing during non-speech intervals, thus saving computation and network bandwidth in VoIP applications. The final phase of the research tested a neural network for accurately aligning the speech signal to hidden Markov model (HMM) states. This included implementing a novel backpropagation method that utilizes prior statistics of node co-activations.

[Arxiv](https://arxiv.org/abs/2406.18135)