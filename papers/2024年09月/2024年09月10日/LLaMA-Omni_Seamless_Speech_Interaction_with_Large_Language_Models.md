# LLaMA-Omni：实现与大型语言模型的流畅语音互动

发布时间：2024年09月10日

`LLM应用` `语音交互` `人工智能`

> LLaMA-Omni: Seamless Speech Interaction with Large Language Models

# 摘要

> GPT-4o 等模型通过语音与 LLM 实时交互，大幅提升了用户体验。然而，基于开源 LLM 的语音交互模型仍待探索。为此，我们推出了 LLaMA-Omni，一种专为低延迟高品质语音交互设计的创新架构。它集成了预训练语音编码器、语音适配器、LLM 和流式语音解码器，无需语音转录，能以极低延迟直接生成文本和语音响应。基于 Llama-3.1-8B-Instruct 模型，我们构建了包含 200K 语音指令及响应的 InstructS2S-200K 数据集。实验显示，LLaMA-Omni 在内容和风格上优于以往模型，响应延迟仅 226 毫秒。在 4 个 GPU 上训练仅需 3 天，为未来高效开发语音-语言模型奠定了基础。

> Models like GPT-4o enable real-time interaction with large language models (LLMs) through speech, significantly enhancing user experience compared to traditional text-based interaction. However, there is still a lack of exploration on how to build speech interaction models based on open-source LLMs. To address this, we propose LLaMA-Omni, a novel model architecture designed for low-latency and high-quality speech interaction with LLMs. LLaMA-Omni integrates a pretrained speech encoder, a speech adaptor, an LLM, and a streaming speech decoder. It eliminates the need for speech transcription, and can simultaneously generate text and speech responses directly from speech instructions with extremely low latency. We build our model based on the latest Llama-3.1-8B-Instruct model. To align the model with speech interaction scenarios, we construct a dataset named InstructS2S-200K, which includes 200K speech instructions and corresponding speech responses. Experimental results show that compared to previous speech-language models, LLaMA-Omni provides better responses in both content and style, with a response latency as low as 226ms. Additionally, training LLaMA-Omni takes less than 3 days on just 4 GPUs, paving the way for the efficient development of speech-language models in the future.

[Arxiv](https://arxiv.org/abs/2409.06666)