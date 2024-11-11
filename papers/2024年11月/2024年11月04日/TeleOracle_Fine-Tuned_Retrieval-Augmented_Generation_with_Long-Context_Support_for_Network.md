# TeleOracle：具有长上下文支持的微调检索增强生成用于网络

发布时间：2024年11月04日

`RAG` `问答系统`

> TeleOracle: Fine-Tuned Retrieval-Augmented Generation with Long-Context Support for Network

# 摘要

> 电信行业的快速发展需要能够管理复杂网络并适应新兴技术的智能系统。虽然大型语言模型（LLM）在应对这些挑战方面显示出了希望，但由于边缘设备的限制和不一致的文档，它们在电信环境中的部署面临着重大的限制。为了弥补这一差距，我们提出了 TeleOracle，这是一个基于 Phi-2 小型语言模型（SLM）构建的电信专用检索增强生成（RAG）系统。为了改进上下文检索，TeleOracle 采用了一个两阶段的检索器，该检索器结合了语义分块以及混合关键字和语义搜索。此外，我们在推理过程中扩大了上下文窗口，以提高模型对开放式查询的性能。我们还采用了低秩自适应进行有效的微调。对模型性能的全面分析表明，我们的 RAG 框架在将 Phi-2 与电信领域的下游问答（QnA）任务对齐方面是有效的，与基础的 Phi-2 模型相比，准确率提高了 30％，达到了 81.20％的总体准确率。值得注意的是，我们表明我们的模型不仅与更大的 LLM 表现相当，而且还获得了更高的忠诚度得分，表明对检索到的上下文的遵循度更高。

> The telecommunications industry's rapid evolution demands intelligent systems capable of managing complex networks and adapting to emerging technologies. While large language models (LLMs) show promise in addressing these challenges, their deployment in telecom environments faces significant constraints due to edge device limitations and inconsistent documentation. To bridge this gap, we present TeleOracle, a telecom-specialized retrieval-augmented generation (RAG) system built on the Phi-2 small language model (SLM). To improve context retrieval, TeleOracle employs a two-stage retriever that incorporates semantic chunking and hybrid keyword and semantic search. Additionally, we expand the context window during inference to enhance the model's performance on open-ended queries. We also employ low-rank adaption for efficient fine-tuning. A thorough analysis of the model's performance indicates that our RAG framework is effective in aligning Phi-2 to the telecom domain in a downstream question and answer (QnA) task, achieving a 30% improvement in accuracy over the base Phi-2 model, reaching an overall accuracy of 81.20%. Notably, we show that our model not only performs on par with the much larger LLMs but also achieves a higher faithfulness score, indicating higher adherence to the retrieved context.

[Arxiv](https://arxiv.org/abs/2411.02617)