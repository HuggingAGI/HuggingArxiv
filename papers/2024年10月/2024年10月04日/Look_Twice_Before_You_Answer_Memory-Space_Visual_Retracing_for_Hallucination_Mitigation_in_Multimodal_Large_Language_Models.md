# 回答前，先三思：通过记忆空间视觉回溯，缓解多模态大型语言模型中的幻觉问题。

发布时间：2024年10月04日

`LLM应用` `人工智能` `计算机视觉`

> Look Twice Before You Answer: Memory-Space Visual Retracing for Hallucination Mitigation in Multimodal Large Language Models

# 摘要

> 尽管多模态大型语言模型 (MLLMs) 能力强大，但它们容易产生幻觉，尤其是编造视觉输入中不存在的内容。为了应对这一挑战，我们借鉴了人类常见的认知过程：当关键现场细节的记忆模糊时，再次查看以获取准确答案是自然而然的选择。因此，我们提出了 Memory-space Visual Retracing (MemVR)，这是一种无需外部知识检索或额外微调的幻觉缓解方法。具体来说，当模型对相关视觉记忆不确定时，我们将视觉提示作为补充证据，通过前馈网络 (FFN) 重新注入模型。实验结果显示，MemVR 在各种 MLLMs 中显著减少了幻觉现象，并在不增加时间成本的情况下在基准测试中表现优异，显示出其广泛应用的潜力。

> Despite their impressive capabilities, Multimodal Large Language Models (MLLMs) are susceptible to hallucinations, especially assertively fabricating content not present in the visual inputs. To address the aforementioned challenge, we follow a common cognitive process - when one's initial memory of critical on-sight details fades, it is intuitive to look at them a second time to seek a factual and accurate answer. Therefore, we introduce Memory-space Visual Retracing (MemVR), a novel hallucination mitigation paradigm that without the need for external knowledge retrieval or additional fine-tuning. In particular, we treat visual prompts as supplementary evidence to be reinjected into MLLMs via Feed Forward Network (FFN) as key-value memory, when the model is uncertain or even amnesic about question-relevant visual memories. Comprehensive experimental evaluations demonstrate that MemVR significantly mitigates hallucination issues across various MLLMs and excels in general benchmarks without incurring added time overhead, thus emphasizing its potential for widespread applicability.

[Arxiv](https://arxiv.org/abs/2410.03577)