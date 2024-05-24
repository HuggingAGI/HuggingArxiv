# 实时互动对话的建模：时间戳标注转录文本

发布时间：2024年05月21日

`Agent

这篇论文介绍了一种利用预训练语言模型实现实时交互对话的方法，这种方法通过模拟带有时间戳的对话记录和采用因果拒绝采样解码来实现。论文通过即时消息和口语对话的案例展示了该方法的实时交互能力，强调了其在维持高速生成速度下的实用性。这种技术可以被视为一种智能代理（Agent），因为它能够模拟人类的实时对话行为，提供即时的响应和交互。因此，这篇论文最适合归类为Agent。` `实时交互` `聊天机器人`

> Modeling Real-Time Interactive Conversations as Timed Diarized Transcripts

# 摘要

> 基于语言模型的聊天机器人虽然广受欢迎，但大多受限于同步回合制对话。本论文介绍了一种简便而通用的方法，利用预训练的纯文本语言模型，通过模拟带有时间戳的对话记录并采用因果拒绝采样解码，实现实时交互对话的模拟。我们通过即时消息和口语对话两个案例，展示了该方法在维持每秒约30和20个令牌生成速度下的实时交互能力。这些增强功能仅需少量数据即可融入语言模型，并在常规硬件上运行。

> Chatbots built upon language models have exploded in popularity, but they have largely been limited to synchronous, turn-by-turn dialogues. In this paper we present a simple yet general method to simulate real-time interactive conversations using pretrained text-only language models, by modeling timed diarized transcripts and decoding them with causal rejection sampling. We demonstrate the promise of this method with two case studies: instant messenger dialogues and spoken conversations, which require generation at about 30 tok/s and 20 tok/s respectively to maintain real-time interactivity. These capabilities can be added into language models using relatively little data and run on commodity hardware.

[Arxiv](https://arxiv.org/abs/2405.13203)