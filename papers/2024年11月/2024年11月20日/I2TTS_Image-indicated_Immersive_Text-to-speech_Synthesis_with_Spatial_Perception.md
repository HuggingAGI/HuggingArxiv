# I2TTS：具备空间感知的图像指示沉浸式文语转换合成

发布时间：2024年11月20日

`LLM应用` `虚拟现实`

> I2TTS: Image-indicated Immersive Text-to-speech Synthesis with Spatial Perception

# 摘要

> 控制语音合成的风格与特征对于让输出适配特定的情境和用户需求极为关键。以往的文本转语音（TTS）工作主要着眼于生成听起来自然的语音的技术层面，比如语调、节奏和清晰度。然而，他们忽略了这样一个事实，即对合成语音的空间感知愈发受到重视，这在游戏和虚拟现实中或许能带来沉浸式体验。为解决此问题，本文中我们提出了一种新颖的多模态TTS方法，即图像指示的沉浸式文本转语音合成（I2TTS）。具体而言，我们引入了一个场景提示编码器，将视觉场景提示直接融入合成管道以控制语音生成过程。另外，我们还提出了一种混响分类和优化技术，用于调整合成的梅尔频谱图以增强沉浸式体验，保证所涉及的混响条件与场景精准匹配。实验结果显示，我们的模型在不牺牲语音自然度的情况下实现了高品质的场景和空间匹配，在上下文感知语音合成领域取得了重大进展。项目演示页面：https://spatialTTS.github.io/ 索引术语 - 语音合成，场景提示，空间感知

> Controlling the style and characteristics of speech synthesis is crucial for adapting the output to specific contexts and user requirements. Previous Text-to-speech (TTS) works have focused primarily on the technical aspects of producing natural-sounding speech, such as intonation, rhythm, and clarity. However, they overlook the fact that there is a growing emphasis on spatial perception of synthesized speech, which may provide immersive experience in gaming and virtual reality. To solve this issue, in this paper, we present a novel multi-modal TTS approach, namely Image-indicated Immersive Text-to-speech Synthesis (I2TTS). Specifically, we introduce a scene prompt encoder that integrates visual scene prompts directly into the synthesis pipeline to control the speech generation process. Additionally, we propose a reverberation classification and refinement technique that adjusts the synthesized mel-spectrogram to enhance the immersive experience, ensuring that the involved reverberation condition matches the scene accurately. Experimental results demonstrate that our model achieves high-quality scene and spatial matching without compromising speech naturalness, marking a significant advancement in the field of context-aware speech synthesis. Project demo page: https://spatialTTS.github.io/ Index Terms-Speech synthesis, scene prompt, spatial perception

[Arxiv](https://arxiv.org/abs/2411.13314)