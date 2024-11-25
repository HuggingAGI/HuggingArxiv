# 让大型语言模型做好说话的准备：语音生成的一种后期融合方式

发布时间：2024年10月27日

`LLM应用`

> Get Large Language Models Ready to Speak: A Late-fusion Approach for Speech Generation

# 摘要

> 大型语言模型（LLMs）在各类基于文本的任务中表现抢眼，给自然语言处理（NLP）带来了革命性变化。但以文本为主的LLMs在语音生成任务上的拓展还有待深入挖掘。在本研究中，我们推出了由微调的Llama模型驱动的文本转语音（TTS）系统，名为TTS-Llama，其语音合成性能达到了前沿水平。基于TTS-Llama，我们又提出了MoLE-Llama，这是通过纯后期融合参数高效微调（PEFT）和专家混合架构开发的文本与语音多模态LLM。大量的实证结果显示，MoLE-Llama在纯文本问答（QA）和TTS任务中均表现出色，缓解了任一模式中的灾难性遗忘问题。最后，我们在语音输出的文本问答任务中对MoLE-Llama做了进一步探索，展现了其作为具备语音生成能力的多模态对话系统的巨大潜力。

> Large language models (LLMs) have revolutionized natural language processing (NLP) with impressive performance across various text-based tasks. However, the extension of text-dominant LLMs to with speech generation tasks remains under-explored. In this work, we introduce a text-to-speech (TTS) system powered by a fine-tuned Llama model, named TTS-Llama, that achieves state-of-the-art speech synthesis performance. Building on TTS-Llama, we further propose MoLE-Llama, a text-and-speech multimodal LLM developed through purely late-fusion parameter-efficient fine-tuning (PEFT) and a mixture-of-expert architecture. Extensive empirical results demonstrate MoLE-Llama's competitive performance on both text-only question-answering (QA) and TTS tasks, mitigating catastrophic forgetting issue in either modality. Finally, we further explore MoLE-Llama in text-in-speech-out QA tasks, demonstrating its great potential as a multimodal dialog system capable of speech generation.

[Arxiv](https://arxiv.org/abs/2410.20336)