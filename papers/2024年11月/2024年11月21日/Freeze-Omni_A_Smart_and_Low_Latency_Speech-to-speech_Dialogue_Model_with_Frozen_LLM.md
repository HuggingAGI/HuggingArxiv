# Freeze-Omni：一款具备冻结 LLM 的智能且低延迟的语音到语音对话模型

发布时间：2024年11月21日

`LLM应用` `语音交互` `多模态交互`

> Freeze-Omni: A Smart and Low Latency Speech-to-speech Dialogue Model with Frozen LLM

# 摘要

> 大型语言模型发展迅猛，带来众多新型智能应用，尤其是 GPT-4o 出色的多模态人机交互，给用户带来了极佳体验。在此背景下，研究人员近期提出了诸多能够实现语音到语音对话的多模态 LLMs。本文中，我们提出了一种名为 Freeze-Omni 的语音-文本多模态 LLM 架构。我们的主要贡献在于，在训练全程保持 LLM 冻结的情况下，能将语音输入和输出模态与 LLM 相连接。我们为语音输入和输出的建模制定了 3 阶段训练策略，让 Freeze-Omni 凭借文本-语音配对数据（如 ASR 和 TTS 数据）以及仅 8 个 GPU 上的 6 万条多轮文本问答数据，获得语音到语音的对话能力。而且，我们能够切实保证 Freeze-Omni 在语音模态中的智能水平与骨干 LLM 的文本模态相当，同时口语响应的端到端延迟处于较低水平。另外，我们还设计了通过多任务训练实现双向对话能力的方法，使 Freeze-Omni 在用户间具备更自然的对话能力风格。Freeze-Omni 主要为研究人员在 LLM 冻结的条件下开展多模态 LLM 研究提供了可能，避免了因数据和训练资源少而导致 LLM 出现灾难性遗忘所带来的种种影响。

> Rapidly developing large language models (LLMs) have brought tremendous intelligent applications. Especially, the GPT-4o's excellent duplex speech interaction ability has brought impressive experience to users. Researchers have recently proposed several multi-modal LLMs in this direction that can achieve user-agent speech-to-speech conversations. This paper proposes a novel speech-text multimodal LLM architecture called Freeze-Omni. Our main contribution is that the speech input and output modalities can be easily connected to a textual LLM while keeping the LLM's parameters frozen throughout the training process. We design a three-stage training strategy for modeling both the speech input and output, enabling Freeze-Omni to obtain speech-to-speech conversation ability using text-speech paired data (such as ASR and TTS data) and only 60,000 multi-round text Q&A data on 8 GPUs. Moreover, we can effectively ensure that the intelligence of the Freeze-Omni in the speech modality is at the same level compared with that in the text modality of its backbone LLM, while achieving low latency end-to-end spoken response. In addition, we also designed a method to achieve duplex dialogue ability through multi-task training, giving Freeze-Omni a more natural style of dialogue ability between users and agents. In summary, Freeze-Omni holds great potential to conduct speech-to-speech dialogue based on a multimodal LLM under the condition of a frozen LLM, avoiding the catastrophic forgetting problem caused by limited data and training resources.

[Arxiv](https://arxiv.org/abs/2411.00774)