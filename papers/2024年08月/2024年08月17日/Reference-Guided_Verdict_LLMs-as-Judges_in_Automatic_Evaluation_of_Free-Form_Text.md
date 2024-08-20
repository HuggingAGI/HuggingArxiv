# 参考引导裁决：LLM 在自由文本自动评估中担任法官角色

发布时间：2024年08月17日

`LLM应用` `人工智能`

> Reference-Guided Verdict: LLMs-as-Judges in Automatic Evaluation of Free-Form Text

# 摘要

> 随着大型语言模型的飞速进步，我们迫切需要一种能够精准评估自由形式文本质量的稳健方法。传统评估指标如 BLEU 和 ROUGE 虽有其价值，但往往难以全面捕捉文本的语义深度和上下文契合度。为此，我们创新性地提出了一种参考引导的评估方法，该方法巧妙地利用多个 LLM 作为“裁判”，以提供更为精准和可靠的开放式生成文本评价。通过融合多元 LLM，我们有效减少了模型偏见，大幅提升了评估与人类判断的契合度，尤其是在传统评估方法力所不及的复杂任务中。实验结果显示，我们的方法在多个问答任务中与人类评估高度一致，证明了其作为人类评估替代方案的可扩展性、可重复性和有效性。这不仅增强了评估的可靠性，更为生成式 AI 的自动化评估革新打开了新的大门。

> The rapid advancements in Large Language Models (LLMs) have highlighted the critical need for robust evaluation methods that can accurately assess the quality of generated text, particularly in free-form tasks. Traditional metrics like BLEU and ROUGE, while useful, often fail to capture the semantic richness and contextual relevance of free-form text compared to reference answers. In this study, we introduce a reference-guided verdict method that leverages multiple LLMs-as-judges to provide a more reliable and accurate evaluation of open-ended LLM generations. By integrating diverse LLMs, our approach mitigates individual model biases and significantly improves alignment with human judgments, especially in challenging tasks where traditional metrics and single-model evaluations fall short. Through experiments across multiple question-answering tasks, we show that our method closely aligns with human evaluations, establishing it as a scalable, reproducible, and effective alternative to human evaluation. Our approach not only enhances evaluation reliability but also opens new avenues for refining automated assessment in generative AI.

[Arxiv](https://arxiv.org/abs/2408.09235)