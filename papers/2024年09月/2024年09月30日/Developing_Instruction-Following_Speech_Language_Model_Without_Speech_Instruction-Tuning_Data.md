# 打造无需语音指令调优的指令跟随语音语言模型

发布时间：2024年09月30日

`LLM应用` `语音识别` `人工智能`

> Developing Instruction-Following Speech Language Model Without Speech Instruction-Tuning Data

# 摘要

> 最新的端到端语音语言模型 (SLM) 通过整合预训练的语音模型，进一步提升了大型语言模型 (LLM) 的能力。然而，这些 SLM 通常需要大量语音指令微调，以弥合语音与文本之间的鸿沟，这不仅耗费大量注释资源，还可能导致原始语言能力的丧失。为此，我们提出了一种简单高效的自动方法，用于生成语音-文本对数据，这种方法在保留 LLM 原有语言能力的同时，巧妙地增强了 SLM 的副语言理解能力。我们的模型无需依赖语音指令微调数据，便能在语音相关任务中表现出色，尤其在 Dynamic-SUPERB 和 AIR-Bench-Chat 基准测试中成绩斐然。此外，我们的模型还能精准执行 LLM 派生的复杂指令，如特定输出格式和链式思维推理。这一创新不仅提升了 SLM 的灵活性和效能，还大幅减少了对庞大注释数据集的依赖，为构建更高效、更智能的语音理解系统奠定了基础。

> Recent end-to-end speech language models (SLMs) have expanded upon the capabilities of large language models (LLMs) by incorporating pre-trained speech models. However, these SLMs often undergo extensive speech instruction-tuning to bridge the gap between speech and text modalities. This requires significant annotation efforts and risks catastrophic forgetting of the original language capabilities. In this work, we present a simple yet effective automatic process for creating speech-text pair data that carefully injects speech paralinguistic understanding abilities into SLMs while preserving the inherent language capabilities of the text-based LLM. Our model demonstrates general capabilities for speech-related tasks without the need for speech instruction-tuning data, achieving impressive performance on Dynamic-SUPERB and AIR-Bench-Chat benchmarks. Furthermore, our model exhibits the ability to follow complex instructions derived from LLMs, such as specific output formatting and chain-of-thought reasoning. Our approach not only enhances the versatility and effectiveness of SLMs but also reduces reliance on extensive annotated datasets, paving the way for more efficient and capable speech understanding systems.

[Arxiv](https://arxiv.org/abs/2409.20007)