# Freeze-Omni：一款具备冻结 LLM 的智能且低延迟的语音到语音对话模型

发布时间：2024年11月01日

`LLM应用` `语音交互` `多模态交互`

> Freeze-Omni: A Smart and Low Latency Speech-to-speech Dialogue Model with Frozen LLM

# 摘要

> 大型语言模型发展迅猛，带来众多新型智能应用，尤其是 GPT-4o 出色的多模态人机交互，给用户带来了极佳体验。在此背景下，研究人员近期提出了诸多能够实现语音到语音对话的多模态 LLMs。本文中，我们提出了一种名为 Freeze-Omni 的语音-文本多模态 LLM 架构。我们的主要贡献在于，在训练全程保持 LLM 冻结的情况下，能将语音输入和输出模态与 LLM 相连接。我们为语音输入和输出的建模制定了 3 阶段训练策略，让 Freeze-Omni 凭借文本-语音配对数据（如 ASR 和 TTS 数据）以及仅 8 个 GPU 上的 6 万条多轮文本问答数据，获得语音到语音的对话能力。而且，我们能够切实保证 Freeze-Omni 在语音模态中的智能水平与骨干 LLM 的文本模态相当，同时口语响应的端到端延迟处于较低水平。另外，我们还设计了通过多任务训练实现双向对话能力的方法，使 Freeze-Omni 在用户间具备更自然的对话能力风格。Freeze-Omni 主要为研究人员在 LLM 冻结的条件下开展多模态 LLM 研究提供了可能，避免了因数据和训练资源少而导致 LLM 出现灾难性遗忘所带来的种种影响。

> The rapid development of large language models has brought many new smart applications, especially the excellent multimodal human-computer interaction in GPT-4o has brought impressive experience to users. In this background, researchers have proposed many multimodal LLMs that can achieve speech-to-speech dialogue recently. In this paper, we propose a speech-text multimodal LLM architecture called Freeze-Omni. Our main contribution is the speech input and output modalities can connected to the LLM while keeping the LLM frozen throughout the training process. We designed 3-stage training strategies both for the modeling of speech input and output, enabling Freeze-Omni to obtain speech-to-speech dialogue ability using text-speech paired data (such as ASR and TTS data) and only 60,000 multi-round text Q&A data on 8 GPUs. Moreover, we can effectively ensure that the intelligence of the Freeze-Omni in the speech modality is at the same level compared with that in the text modality of its backbone LLM, while the end-to-end latency of the spoken response achieves a low level. In addition, we also designed a method to achieve duplex dialogue ability through multi-task training, making Freeze-Omni have a more natural style of dialogue ability between the users. Freeze-Omni mainly provides a possibility for researchers to conduct multimodal LLM under the condition of a frozen LLM, avoiding various impacts caused by the catastrophic forgetting of LLM caused by fewer data and training resources.

[Arxiv](https://arxiv.org/abs/2411.00774)