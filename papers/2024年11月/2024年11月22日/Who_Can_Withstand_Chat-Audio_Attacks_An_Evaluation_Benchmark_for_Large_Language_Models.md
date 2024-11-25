# 谁能够抵御聊天音频攻击？大型语言模型的评估基准

发布时间：2024年11月22日

`LLM应用` `语音交互` `音频攻击`

> Who Can Withstand Chat-Audio Attacks? An Evaluation Benchmark for Large Language Models

# 摘要

> 对抗性音频攻击给大型语言模型（LLMs）在语音人机交互中的广泛应用带来了重大威胁。现有的研究多聚焦于特定模型的对抗方法，然而实际应用需要更通用、普适的音频对抗攻击手段。本文引入了 Chat-Audio Attacks（CAA）基准，涵盖四种不同类型的音频攻击，旨在探究 LLMs 在对话场景中面对这些攻击的脆弱性。为评估 LLMs 的稳健性，我们提出了三项评估策略：标准评估，运用传统指标量化模型在攻击下的表现；GPT-4o 基础评估，模拟真实世界的对话复杂情况；人类评估，提供关于用户感知和信任的见解。我们使用 CAA 基准上的三种不同评估方法对六个具备语音交互能力的先进 LLMs 进行了评估，包括 Gemini-1.5-Pro、GPT-4o 等。我们的全面分析揭示了四种音频攻击对这些模型性能的影响，表明 GPT-4o 展现出了最高的抵御能力。

> Adversarial audio attacks pose a significant threat to the growing use of large language models (LLMs) in voice-based human-machine interactions. While existing research has primarily focused on model-specific adversarial methods, real-world applications demand a more generalizable and universal approach to audio adversarial attacks. In this paper, we introduce the Chat-Audio Attacks (CAA) benchmark including four distinct types of audio attacks, which aims to explore the the vulnerabilities of LLMs to these audio attacks in conversational scenarios. To evaluate the robustness of LLMs, we propose three evaluation strategies: Standard Evaluation, utilizing traditional metrics to quantify model performance under attacks; GPT-4o-Based Evaluation, which simulates real-world conversational complexities; and Human Evaluation, offering insights into user perception and trust. We evaluate six state-of-the-art LLMs with voice interaction capabilities, including Gemini-1.5-Pro, GPT-4o, and others, using three distinct evaluation methods on the CAA benchmark. Our comprehensive analysis reveals the impact of four types of audio attacks on the performance of these models, demonstrating that GPT-4o exhibits the highest level of resilience.

[Arxiv](https://arxiv.org/abs/2411.14842)