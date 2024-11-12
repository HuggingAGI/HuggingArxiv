# 基于 CTC 辅助的基于大语言模型的上下文语音识别

发布时间：2024年11月10日

`LLM应用` `语音识别` `语言模型`

> CTC-Assisted LLM-Based Contextual ASR

# 摘要

> 上下文相关的自动语音识别（ASR）或热词定制具有很大的实用价值。尽管当前的端到端（E2E）自动语音识别（ASR）系统性能令人印象深刻，但它们在准确识别罕见词方面经常面临挑战。典型的 E2E 上下文相关 ASR 模型通常具有复杂的架构和解码机制，性能有限，容易受到干扰词的干扰。随着基于大型语言模型（LLM）的 ASR 模型成为新的主流，我们提出了一种具有高效过滤算法的 CTC 辅助基于 LLM 的上下文相关 ASR 模型。通过使用粗略的 CTC 解码结果来过滤潜在的相关热词，并将它们纳入 LLM 提示输入，我们的模型在针对识别罕见长尾词的 Librispeech 测试清洁集和测试其他集上达到了 1.27%/3.67%和 2.72%/8.02%的 WER/B-WER，与基于基线 LLM 的 ASR 模型相比有显著改进，并大大超过了其他相关工作。更值得注意的是，在大型语言模型和所提出的过滤算法的帮助下，我们的上下文相关 ASR 模型在有 2000 个偏向词的情况下仍然表现良好。

> Contextual ASR or hotword customization holds substantial practical value. Despite the impressive performance of current end-to-end (E2E) automatic speech recognition (ASR) systems, they often face challenges in accurately recognizing rare words. Typical E2E contextual ASR models commonly feature complex architectures and decoding mechanisms, limited in performance and susceptible to interference from distractor words. With large language model (LLM)-based ASR models emerging as the new mainstream, we propose a CTC-Assisted LLM-Based Contextual ASR model with an efficient filtering algorithm. By using coarse CTC decoding results to filter potential relevant hotwords and incorporating them into LLM prompt input, our model attains WER/B-WER of 1.27%/3.67% and 2.72%/8.02% on the Librispeech test-clean and test-other sets targeting on recognizing rare long-tail words, demonstrating significant improvements compared to the baseline LLM-based ASR model, and substantially surpassing other related work. More remarkably, with the help of the large language model and proposed filtering algorithm, our contextual ASR model still performs well with 2000 biasing words.

[Arxiv](https://arxiv.org/abs/2411.06437)