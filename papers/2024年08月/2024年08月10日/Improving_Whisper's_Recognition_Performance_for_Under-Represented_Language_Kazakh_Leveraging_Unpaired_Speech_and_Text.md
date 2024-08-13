# 借助未配对的语音与文本数据，我们致力于提升 Whisper 对哈萨克语这一代表性不足语言的识别能力。

发布时间：2024年08月10日

`LLM应用` `语音识别` `低资源语言`

> Improving Whisper's Recognition Performance for Under-Represented Language Kazakh Leveraging Unpaired Speech and Text

# 摘要

> Whisper 等大规模自动语音识别模型虽有显著进步，但在低资源语言如哈萨克语上的表现仍不尽人意。本研究探索了如何利用低成本数据提升 Whisper 在代表性不足语言上的性能。我们结合 GPT 语言模型与 Whisper，通过 EOT 判断修改和幻觉惩罚优化识别效果。同时，利用解码平均标记对数概率筛选无标签语音数据，并借助伪标签数据微调模型，最终在多次实验中实现超过 10% 的 WER 绝对降低，此方法有望推广至其他代表性不足的语言。

> Whisper and other large-scale automatic speech recognition models have made significant progress in performance. However, their performance on many low-resource languages, such as Kazakh, is not satisfactory. It is worth researching how to utilize low-cost data to improve the performance of Whisper on under-represented languages. In this study, we utilized easily accessible unpaired speech and text data and combined the language model GPT with Whisper on Kazakh. We implemented end of transcript (EOT) judgment modification and hallucination penalty to improve the performance of speech recognition. Further, we employed the decoding average token log probability as a criterion to select samples from unlabeled speech data and used pseudo-labeled data to fine-tune the model to further improve its performance. Ultimately, we achieved more than 10\% absolute WER reduction in multiple experiments, and the whole process has the potential to be generalized to other under-represented languages.

[Arxiv](https://arxiv.org/abs/2408.05554)