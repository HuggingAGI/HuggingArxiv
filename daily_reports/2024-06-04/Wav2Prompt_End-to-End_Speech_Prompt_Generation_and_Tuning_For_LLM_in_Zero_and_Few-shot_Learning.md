# Wav2Prompt：大型语言模型零样本与少样本学习中的端到端语音提示生成与优化
发布时间：2024年06月01日

`提示工程`
> Wav2Prompt: End-to-End Speech Prompt Generation and Tuning For LLM in Zero and Few-shot Learning
>
> Wav2Prompt 技术实现了口语输入与大型文本语言模型（LLM）的无缝对接。它采用与训练自动语音识别（ASR）模型相同的数据进行简单训练，从语音中提取连续表示作为 LLM 的提示。为防止任务过度拟合并保持 LLM 的独特能力，Wav2Prompt 以 LLM 的令牌嵌入为目标，通过连续的集成和触发机制确保语音与文本的精确对齐。这一组合使得 Wav2Prompt-LLM 能够零-shot 处理口语任务，如语音翻译、理解、问答等，其性能与 ASR-LLM 级联相当，甚至超越了先前的技术。在拥有少量特定任务数据的情况下，Wav2Prompt-LLM 还能进行端到端微调，大幅提升性能。例如，在英语-法语 ST 任务中，与 ASR-LLM 级联相比，Wav2Prompt-LLM 组合的 BLEU 分数提高了 8.5 分。
>
> https://arxiv.org/abs/2406.00522

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00522/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00522](https://arxiv.org/abs/2406.00522)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886