# AXCEL：利用 LLM 实现自动可解释一致性评估

发布时间：2024年09月25日

`LLM应用` `文本生成`

> AXCEL: Automated eXplainable Consistency Evaluation using LLMs

# 摘要

> 大型语言模型 (LLM) 在各行各业广泛应用，但评估生成文本的一致性仍是一大难题。传统指标如 ROUGE 和 BLEU 与人类判断相关性不强。更复杂的自然语言推理 (NLI) 指标虽有改进，但实现复杂，跨领域泛化性差，且缺乏解释性。近期出现的基于提示的评估方法虽易实现，但仍缺乏解释性，且依赖任务特定提示，通用性受限。为此，我们推出了自动化可解释一致性评估 (AXCEL)，一种基于提示的指标，通过详细推理和指出不一致文本片段来解释评分。AXCEL 通用性强，无需改变提示即可应用于多任务。在摘要、自由文本生成和数据到文本转换任务中，AXCEL 分别比现有最佳方法提升 8.7%、6.2% 和 29.4%。我们还研究了基础 LLM 对评估性能的影响，并使用最新 LLM 重新校准现有最佳方法以公平比较。此外，AXCEL 在开源 LLM 上也表现出色。

> Large Language Models (LLMs) are widely used in both industry and academia for various tasks, yet evaluating the consistency of generated text responses continues to be a challenge. Traditional metrics like ROUGE and BLEU show a weak correlation with human judgment. More sophisticated metrics using Natural Language Inference (NLI) have shown improved correlations but are complex to implement, require domain-specific training due to poor cross-domain generalization, and lack explainability. More recently, prompt-based metrics using LLMs as evaluators have emerged; while they are easier to implement, they still lack explainability and depend on task-specific prompts, which limits their generalizability. This work introduces Automated eXplainable Consistency Evaluation using LLMs (AXCEL), a prompt-based consistency metric which offers explanations for the consistency scores by providing detailed reasoning and pinpointing inconsistent text spans. AXCEL is also a generalizable metric which can be adopted to multiple tasks without changing the prompt. AXCEL outperforms both non-prompt and prompt-based state-of-the-art (SOTA) metrics in detecting inconsistencies across summarization by 8.7%, free text generation by 6.2%, and data-to-text conversion tasks by 29.4%. We also evaluate the influence of underlying LLMs on prompt based metric performance and recalibrate the SOTA prompt-based metrics with the latest LLMs for fair comparison. Further, we show that AXCEL demonstrates strong performance using open source LLMs.

[Arxiv](https://arxiv.org/abs/2409.16984)