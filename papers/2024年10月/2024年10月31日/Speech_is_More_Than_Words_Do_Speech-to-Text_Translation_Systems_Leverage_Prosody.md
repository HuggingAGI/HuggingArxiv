# 语音可不只是文字：语音到文本的翻译系统会借助韵律吗？

发布时间：2024年10月31日

`LLM应用` `语音翻译` `语言模型`

> Speech is More Than Words: Do Speech-to-Text Translation Systems Leverage Prosody?

# 摘要

> 口语表达的韵律，涵盖重音、语调以及节奏等特性，会极大地影响其内在语义，进而也会对其文本翻译产生作用。然而，在语音到文本翻译（S2TT）系统中，韵律鲜少被探究。特别是端到端（E2E）系统已被提出适用于韵律感知翻译，因为它们在进行翻译决策时能够直接获取语音信号，不过对于其在实际中是否成功的了解依旧有限。主要的挑战在于评估翻译中的韵律感知存在难度。为应对此挑战，我们引入了一种评估方法以及一个重点基准（名为ContraProST），旨在捕获各类韵律现象。我们的方法运用大型语言模型和可控的文本转语音（TTS）来生成对比实例。通过将英语语音翻译成德语、西班牙语和日语的实验，我们发现：（a）S2TT 模型具备一定的韵律内部表征，但韵律信号通常不够强劲，难以影响翻译；（b）E2E 系统优于语音识别和文本翻译系统的级联，证实了其在这方面的理论优势；（c）某些级联系统在翻译中也能捕捉韵律信息，但程度较小，这取决于转录本的表面形式的具体情况。

> The prosody of a spoken utterance, including features like stress, intonation and rhythm, can significantly affect the underlying semantics, and as a consequence can also affect its textual translation. Nevertheless, prosody is rarely studied within the context of speech-to-text translation (S2TT) systems. In particular, end-to-end (E2E) systems have been proposed as well-suited for prosody-aware translation because they have direct access to the speech signal when making translation decisions, but the understanding of whether this is successful in practice is still limited. A main challenge is the difficulty of evaluating prosody awareness in translation. To address this challenge, we introduce an evaluation methodology and a focused benchmark (named ContraProST) aimed at capturing a wide range of prosodic phenomena. Our methodology uses large language models and controllable text-to-speech (TTS) to generate contrastive examples. Through experiments in translating English speech into German, Spanish, and Japanese, we find that (a) S2TT models possess some internal representation of prosody, but the prosody signal is often not strong enough to affect the translations, (b) E2E systems outperform cascades of speech recognition and text translation systems, confirming their theoretical advantage in this regard, and (c) certain cascaded systems also capture prosodic information in the translation, but only to a lesser extent that depends on the particulars of the transcript's surface form.

[Arxiv](https://arxiv.org/abs/2410.24019)