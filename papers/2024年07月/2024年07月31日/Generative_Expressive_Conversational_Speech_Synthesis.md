# 生成式对话语音合成，赋予表达力

发布时间：2024年07月31日

`LLM应用` `语音合成` `人工智能`

> Generative Expressive Conversational Speech Synthesis

# 摘要

> 会话语音合成 (CSS) 旨在在用户与代理的对话环境中，以恰当的说话风格传达目标话语。现有 CSS 方法虽采用多模态上下文建模技术以实现共情理解与表达，但常需构建复杂网络架构并精细调整内部模块。此外，受限于小规模脚本式录音数据集，这些方法往往难以模拟真实自然的对话风格。为此，我们提出 GPT-Talker 这一创新生成式表达性 CSS 系统。我们巧妙地将多轮对话历史的多模态信息转化为离散令牌序列，并将其无缝融合，构建出全面的用户-代理对话上下文。借助 GPT 的强大能力，我们预测包含语义与风格信息的代理响应令牌序列，并通过对话增强的 VITS 合成出富有表现力的会话语音，向用户反馈。同时，我们创建了大规模自然 CSS 数据集 NCSSD，涵盖即兴录制与电视对话，包含中英文，总时长 236 小时。实验证明，无论是主观还是客观评估，我们的模型在自然度与表达性方面均显著超越现有顶尖 CSS 系统。相关代码、数据集及预训练模型已公开于 GitHub：https://github.com/AI-S2-Lab/GPT-Talker。

> Conversational Speech Synthesis (CSS) aims to express a target utterance with the proper speaking style in a user-agent conversation setting. Existing CSS methods employ effective multi-modal context modeling techniques to achieve empathy understanding and expression. However, they often need to design complex network architectures and meticulously optimize the modules within them. In addition, due to the limitations of small-scale datasets containing scripted recording styles, they often fail to simulate real natural conversational styles. To address the above issues, we propose a novel generative expressive CSS system, termed GPT-Talker.We transform the multimodal information of the multi-turn dialogue history into discrete token sequences and seamlessly integrate them to form a comprehensive user-agent dialogue context. Leveraging the power of GPT, we predict the token sequence, that includes both semantic and style knowledge, of response for the agent. After that, the expressive conversational speech is synthesized by the conversation-enriched VITS to deliver feedback to the user.Furthermore, we propose a large-scale Natural CSS Dataset called NCSSD, that includes both naturally recorded conversational speech in improvised styles and dialogues extracted from TV shows. It encompasses both Chinese and English languages, with a total duration of 236 hours.We conducted comprehensive experiments on the reliability of the NCSSD and the effectiveness of our GPT-Talker. Both subjective and objective evaluations demonstrate that our model outperforms other state-of-the-art CSS systems significantly in terms of naturalness and expressiveness. The Code, Dataset, and Pre-trained Model are available at: https://github.com/AI-S2-Lab/GPT-Talker.

[Arxiv](https://arxiv.org/abs/2407.21491)