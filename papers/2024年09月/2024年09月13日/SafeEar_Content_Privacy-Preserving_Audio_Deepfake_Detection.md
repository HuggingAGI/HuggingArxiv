# SafeEar：保护隐私的音频深度伪造检测

发布时间：2024年09月13日

`LLM应用` `音频处理`

> SafeEar: Content Privacy-Preserving Audio Deepfake Detection

# 摘要

> TTS 和 VC 模型在生成逼真音频方面表现卓越，但其背后的音频深度伪造技术却对社会和个人构成严重威胁。现有对策多依赖完整原始音频来验证真实性，但这些音频常含私密内容，限制了深度伪造检测的应用，尤其是在涉及敏感信息的场景中。为此，我们提出 SafeEar 框架，通过神经音频编解码器分离语义与声学信息，仅利用声学特征（如韵律和音色）进行深度伪造检测，确保语义内容不被泄露。为应对多样化的深度伪造音频，我们通过现实编解码器增强检测器。实验表明，SafeEar 在四大基准数据集上的等错误率低至 2.02%，同时保护五种语言的语音内容不被机器和人类解析，单词错误率均超 93.93%。此外，我们构建的反深度伪造与反内容恢复评估基准，为未来音频隐私保护与深度伪造检测研究奠定了基础。

> Text-to-Speech (TTS) and Voice Conversion (VC) models have exhibited remarkable performance in generating realistic and natural audio. However, their dark side, audio deepfake poses a significant threat to both society and individuals. Existing countermeasures largely focus on determining the genuineness of speech based on complete original audio recordings, which however often contain private content. This oversight may refrain deepfake detection from many applications, particularly in scenarios involving sensitive information like business secrets. In this paper, we propose SafeEar, a novel framework that aims to detect deepfake audios without relying on accessing the speech content within. Our key idea is to devise a neural audio codec into a novel decoupling model that well separates the semantic and acoustic information from audio samples, and only use the acoustic information (e.g., prosody and timbre) for deepfake detection. In this way, no semantic content will be exposed to the detector. To overcome the challenge of identifying diverse deepfake audio without semantic clues, we enhance our deepfake detector with real-world codec augmentation. Extensive experiments conducted on four benchmark datasets demonstrate SafeEar's effectiveness in detecting various deepfake techniques with an equal error rate (EER) down to 2.02%. Simultaneously, it shields five-language speech content from being deciphered by both machine and human auditory analysis, demonstrated by word error rates (WERs) all above 93.93% and our user study. Furthermore, our benchmark constructed for anti-deepfake and anti-content recovery evaluation helps provide a basis for future research in the realms of audio privacy preservation and deepfake detection.

[Arxiv](https://arxiv.org/abs/2409.09272)