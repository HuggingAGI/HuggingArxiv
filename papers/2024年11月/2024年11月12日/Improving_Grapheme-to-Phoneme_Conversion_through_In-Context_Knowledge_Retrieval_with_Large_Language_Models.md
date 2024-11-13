# 通过大型语言模型的上下文知识检索来改进字素到音素的转换

发布时间：2024年11月12日

`LLM应用` `语音处理` `文本到语音`

> Improving Grapheme-to-Phoneme Conversion through In-Context Knowledge Retrieval with Large Language Models

# 摘要

> 字素到音素（G2P）转换是文本到语音（TTS）系统中的关键步骤，负责将字素映射到相应的语音表示。然而，它面临着歧义问题，即相同的字素根据上下文可以代表多个音素，这给 G2P 转换带来了挑战。受到大型语言模型（LLMs）在处理上下文感知场景方面取得显著成功的启发，提出了具有 LLMs 的上下文知识检索（ICKR）能力的上下文 G2P 转换系统，以提高消歧能力。在 Librig2p 数据集上全面证明了将 ICKR 纳入 G2P 转换系统的有效性。特别是，使用 ICKR 的最佳上下文 G2P 转换系统在加权平均音素错误率（PER）方面比基线绝对降低 2.0％（相对降低 28.9％）。在 ICKR 系统中使用 GPT-4 在 Librig2p 数据集上可以绝对增加 3.5％（相对增加 3.8％）。

> Grapheme-to-phoneme (G2P) conversion is a crucial step in Text-to-Speech (TTS) systems, responsible for mapping grapheme to corresponding phonetic representations. However, it faces ambiguities problems where the same grapheme can represent multiple phonemes depending on contexts, posing a challenge for G2P conversion. Inspired by the remarkable success of Large Language Models (LLMs) in handling context-aware scenarios, contextual G2P conversion systems with LLMs' in-context knowledge retrieval (ICKR) capabilities are proposed to promote disambiguation capability. The efficacy of incorporating ICKR into G2P conversion systems is demonstrated thoroughly on the Librig2p dataset. In particular, the best contextual G2P conversion system using ICKR outperforms the baseline with weighted average phoneme error rate (PER) reductions of 2.0% absolute (28.9% relative). Using GPT-4 in the ICKR system can increase of 3.5% absolute (3.8% relative) on the Librig2p dataset.

[Arxiv](https://arxiv.org/abs/2411.07563)