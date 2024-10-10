# 大语言模型中的信号水印

发布时间：2024年10月09日

`LLM应用` `文本生成`

> Signal Watermark on Large Language Models

# 摘要

> 随着 LLM 的复杂性增加，它们带来的安全问题也日益严重，如假新闻和学术滥用。现有的文本检测器依赖于困惑度和突发性，且计算资源消耗大。本文提出了一种基于预定义信号模式的水印方法，在 LLM 生成文本时嵌入水印。这种方法不仅使水印对人类不可见，还保持了文本的质量和语法完整性。通过结合 LLM 和 FFT，我们实现了令牌概率计算和水印检测。在 LLM 文本生成中应用信号处理原理，我们成功地嵌入了不影响文本质量的水印。实验表明，即使在温度设置变化的情况下，我们的方法也能保持高检测准确性，AUROC 分数达到 0.97，远超 GPTZero 的 0.64。水印在多种攻击场景下的表现进一步证明了其鲁棒性，有效解决了模型生成文本认证的难题。

> As Large Language Models (LLMs) become increasingly sophisticated, they raise significant security concerns, including the creation of fake news and academic misuse. Most detectors for identifying model-generated text are limited by their reliance on variance in perplexity and burstiness, and they require substantial computational resources. In this paper, we proposed a watermarking method embedding a specific watermark into the text during its generation by LLMs, based on a pre-defined signal pattern. This technique not only ensures the watermark's invisibility to humans but also maintains the quality and grammatical integrity of model-generated text. We utilize LLMs and Fast Fourier Transform (FFT) for token probability computation and detection of the signal watermark. The unique application of signal processing principles within the realm of text generation by LLMs allows for subtle yet effective embedding of watermarks, which do not compromise the quality or coherence of the generated text. Our method has been empirically validated across multiple LLMs, consistently maintaining high detection accuracy, even with variations in temperature settings during text generation. In the experiment of distinguishing between human-written and watermarked text, our method achieved an AUROC score of 0.97, significantly outperforming existing methods like GPTZero, which scored 0.64. The watermark's resilience to various attacking scenarios further confirms its robustness, addressing significant challenges in model-generated text authentication.

[Arxiv](https://arxiv.org/abs/2410.06545)