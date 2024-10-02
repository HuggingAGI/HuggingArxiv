# 倾听你的声音：一种自适应、高效且与语言无关的语音提取方法

发布时间：2024年10月01日

`LLM应用` `语音识别` `跨语言处理`

> Wanna Hear Your Voice: Adaptive, Effective, and Language-Agnostic Approach in Voice Extraction

# 摘要

> 基于音频线索的目标说话人提取 (TSE) 研究主要集中在英语数据集上，取得了显著成果。然而，跨语言语音的一致性属性却鲜有关注。为此，我们推出了 WHYV (Wanna Hear Your Voice)，旨在无需微调即可实现跨语言的 TSE 模型转移。我们设计了一种门控机制，能根据说话人的声学特征调整特定频率。实验结果显示，WHYV 在干净英语语音上的 SI-SDR 达到 17.3544，在混合噪声环境下也表现出色，达到 13.2032，显著优于其他模型，展现了其强大的跨语言适应能力。

> The research on audio clue-based target speaker extraction (TSE) has mostly focused on modeling the mixture and reference speech, achieving high performance in English due to the availability of large datasets. However, less attention has been given to the consistent properties of human speech across languages. To bridge this gap, we introduce WHYV (Wanna Hear Your Voice), which addresses the challenge of transferring TSE models from one language to another without fine-tuning. In this work, we proposed a gating mechanism that be able to modify specific frequencies based on the speaker's acoustic features. The model achieves an SI-SDR of 17.3544 on clean English speech and 13.2032 on clean speech mixed with Wham! noise, outperforming all other models in its ability to adapt to different languages.

[Arxiv](https://arxiv.org/abs/2410.00527)