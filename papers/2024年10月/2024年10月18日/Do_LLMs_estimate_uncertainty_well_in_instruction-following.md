# 大型语言模型在遵循指令时，能否准确评估不确定性？

发布时间：2024年10月18日

`LLM理论` `人工智能` `人机交互`

> Do LLMs estimate uncertainty well in instruction-following?

# 摘要

> 大型语言模型 (LLM) 若能精准遵循用户指令，将成为各领域的宝贵个人 AI 助手。然而，最新研究表明，LLM 在指令遵循方面存在显著局限，引发了对高风险应用中其可靠性的担忧。准确评估 LLM 在遵循指令时的不确定性，是降低部署风险的关键。我们首次系统评估了 LLM 在指令遵循情境下的不确定性估计能力，发现现有基准测试中，多个因素与不确定性纠缠，使得方法和模型间的比较复杂。为此，我们设计了包含两个数据版本的受控评估，全面比较了不同条件下的不确定性估计方法。结果显示，现有方法在处理细微指令错误时表现不佳，尽管内部模型状态有所改进，但在复杂场景中仍显不足。我们的研究为理解 LLM 在指令遵循任务中的局限性和不确定性估计潜力提供了重要见解，推动了更可信 AI 助手的发展。

> Large language models (LLMs) could be valuable personal AI agents across various domains, provided they can precisely follow user instructions. However, recent studies have shown significant limitations in LLMs' instruction-following capabilities, raising concerns about their reliability in high-stakes applications. Accurately estimating LLMs' uncertainty in adhering to instructions is critical to mitigating deployment risks. We present, to our knowledge, the first systematic evaluation of the uncertainty estimation abilities of LLMs in the context of instruction-following. Our study identifies key challenges with existing instruction-following benchmarks, where multiple factors are entangled with uncertainty stems from instruction-following, complicating the isolation and comparison across methods and models. To address these issues, we introduce a controlled evaluation setup with two benchmark versions of data, enabling a comprehensive comparison of uncertainty estimation methods under various conditions. Our findings show that existing uncertainty methods struggle, particularly when models make subtle errors in instruction following. While internal model states provide some improvement, they remain inadequate in more complex scenarios. The insights from our controlled evaluation setups provide a crucial understanding of LLMs' limitations and potential for uncertainty estimation in instruction-following tasks, paving the way for more trustworthy AI agents.

[Arxiv](https://arxiv.org/abs/2410.14582)