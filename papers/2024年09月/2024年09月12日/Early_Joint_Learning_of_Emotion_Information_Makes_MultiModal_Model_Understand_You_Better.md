# 通过早期联合学习情感信息，多模态模型能更深入地理解你。

发布时间：2024年09月12日

`LLM应用` `情感识别` `语音处理`

> Early Joint Learning of Emotion Information Makes MultiModal Model Understand You Better

# 摘要

> 本文展示了我们在 MER2024 情感识别挑战中的解决方案。为解决音频与文本的模态竞争，我们采用基于大型语言模型的早期融合策略，先联合训练音频和文本，再与单模态特征后期融合。针对数据不足和类别不平衡，我们通过多轮多模态投票进行数据挖掘。此外，为提升音频质量，我们预先进行语音源分离处理。我们的模型在 MER2024-SEMI 和 MER2024-NOISE 中均位列第二，充分证明了方法的有效性。

> In this paper, we present our solutions for emotion recognition in the sub-challenges of Multimodal Emotion Recognition Challenge (MER2024). To mitigate the modal competition issue between audio and text, we adopt an early fusion strategy based on a large language model, where joint training of audio and text is conducted initially. And the joint Audio-Text modal feature will be late-fused with other unimodal features. In order to solve the problems of data insufficiency and class imbalance, We use multiple turns of multi-model voting for data mining. Moreover, to enhance the quality of audio features, we employ speech source separation to preprocess audios. Our model ranks \textbf{2nd} in both MER2024-SEMI and MER2024-NOISE, validating our method's effectiveness.

[Arxiv](https://arxiv.org/abs/2409.18971)