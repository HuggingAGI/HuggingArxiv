# 大型语言模型是否“内知”何时遵循指令？

发布时间：2024年10月18日

`LLM理论` `人工智能`

> Do LLMs "know" internally when they follow instructions?

# 摘要

> 指令遵循是构建基于 LLM 的 AI 代理的关键，因为这些模型必须严格遵循用户指令。然而，LLM 常常无法遵循简单清晰的指令。为了改进这一行为并防止不良输出，我们需要更深入地理解 LLM 内部状态与指令遵循结果之间的关系。我们的分析发现，输入嵌入空间中存在一个与成功指令遵循相关的维度。通过沿着这一维度调整表示，我们能够提高指令遵循的成功率，且不影响响应质量。进一步的研究表明，这一维度与提示的措辞密切相关，而非任务或指令的难度。这一发现解释了为何 LLM 有时无法遵循清晰指令，以及为何提示工程通常有效。这项研究揭示了 LLM 指令遵循的内部机制，为构建更可靠的 LLM 代理奠定了基础。

> Instruction-following is crucial for building AI agents with large language models (LLMs), as these models must adhere strictly to user-provided constraints and guidelines. However, LLMs often fail to follow even simple and clear instructions. To improve instruction-following behavior and prevent undesirable outputs, a deeper understanding of how LLMs' internal states relate to these outcomes is required. Our analysis of LLM internal states reveal a dimension in the input embedding space linked to successful instruction-following. We demonstrate that modifying representations along this dimension improves instruction-following success rates compared to random changes, without compromising response quality. Further investigation reveals that this dimension is more closely related to the phrasing of prompts rather than the inherent difficulty of the task or instructions. This discovery also suggests explanations for why LLMs sometimes fail to follow clear instructions and why prompt engineering is often effective, even when the content remains largely unchanged. This work provides insight into the internal workings of LLMs' instruction-following, paving the way for reliable LLM agents.

[Arxiv](https://arxiv.org/abs/2410.14516)