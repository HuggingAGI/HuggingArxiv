# 语音基础模型与大型语言模型如何对接？关键何在，何为次要？

发布时间：2024年09月25日

`LLM应用` `语音识别` `语音翻译`

> How to Connect Speech Foundation Models and Large Language Models? What Matters and What Does Not

# 摘要

> 大型语言模型 (LLM) 的卓越表现激发了将其应用于多种任务和输入模式的研究。在语音转文本 (S2T) 任务中，新兴方案通过适配器将语音基础模型 (SFM) 的编码器输出映射到 LLM 嵌入空间。然而，尚无研究探讨下游任务性能对各组件（SFM、适配器、LLM）的依赖程度，也未研究适配器设计是否受 SFM 和 LLM 选择影响。为此，我们测试了 5 种适配器、2 种 LLM（Mistral 和 Llama）及 2 种 SFM（Whisper 和 SeamlessM4T）在自动语音识别和语音翻译任务中的表现。结果显示，SFM 对下游性能至关重要，适配器选择影响适中，且受 SFM 和 LLM 影响。

> The remarkable performance achieved by Large Language Models (LLM) has driven research efforts to leverage them for a wide range of tasks and input modalities. In speech-to-text (S2T) tasks, the emerging solution consists of projecting the output of the encoder of a Speech Foundational Model (SFM) into the LLM embedding space through an adapter module. However, no work has yet investigated how much the downstream-task performance depends on each component (SFM, adapter, LLM) nor whether the best design of the adapter depends on the chosen SFM and LLM. To fill this gap, we evaluate the combination of 5 adapter modules, 2 LLMs (Mistral and Llama), and 2 SFMs (Whisper and SeamlessM4T) on two widespread S2T tasks, namely Automatic Speech Recognition and Speech Translation. Our results demonstrate that the SFM plays a pivotal role in downstream performance, while the adapter choice has moderate impact and depends on the SFM and LLM.

[Arxiv](https://arxiv.org/abs/2409.17044)