# 无专家参与的 LLM-符号规划：在未知领域中探索前行

发布时间：2024年09月24日

`LLM应用` `人工智能` `自动化`

> Planning in the Dark: LLM-Symbolic Planning Pipeline without Experts

# 摘要

> LLM 在处理自然语言规划任务时虽有潜力，但直接应用常导致推理不一致和幻觉。尽管混合 LLM-符号规划管道提供了更稳健的解决方案，但其高度依赖专家干预，限制了可扩展性并可能引入偏见。为此，我们提出了一种新方法，构建动作模式库以生成多样候选方案，并引入自动语义验证和排序模块，无需专家参与。实验证明，我们的方法在规划性能上优于直接 LLM 规划。这不仅实现了完全自动化的端到端规划，还降低了与 AI 规划互动的门槛，使更多人能够参与其中。

> Large Language Models (LLMs) have shown promise in solving natural language-described planning tasks, but their direct use often leads to inconsistent reasoning and hallucination. While hybrid LLM-symbolic planning pipelines have emerged as a more robust alternative, they typically require extensive expert intervention to refine and validate generated action schemas. It not only limits scalability but also introduces a potential for biased interpretation, as a single expert's interpretation of ambiguous natural language descriptions might not align with the user's actual intent. To address this, we propose a novel approach that constructs an action schema library to generate multiple candidates, accounting for the diverse possible interpretations of natural language descriptions. We further introduce a semantic validation and ranking module that automatically filter and rank the generated schemas and plans without expert-in-the-loop. The experiments showed our pipeline maintains superiority in planning over the direct LLM planning approach. These findings demonstrate the feasibility of a fully automated end-to-end LLM-symbolic planner that requires no expert intervention, opening up the possibility for a broader audience to engage with AI planning with less prerequisite of domain expertise.

[Arxiv](https://arxiv.org/abs/2409.15915)