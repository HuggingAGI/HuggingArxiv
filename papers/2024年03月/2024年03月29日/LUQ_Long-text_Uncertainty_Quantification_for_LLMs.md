# LUQ：为大型语言模型量身打造的长文本不确定性评估方法

发布时间：2024年03月29日

`LLM理论` `信息安全` `人工智能`

> LUQ: Long-text Uncertainty Quantification for LLMs

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理任务中大放异彩。然而，它们有时也会制造虚假信息。不确定性量化（UQ）技术在此显得尤为重要，它帮助我们把握模型对其输出内容的信心程度，从而减少虚假信息的产生。目前关于UQ的研究多集中于短文本，通常只能得到简短的答复。但实际上，我们往往需要更长篇幅的内容。本研究首先揭示了现有UQ方法在处理长篇文本时的不足。接着，我们推出了\textsc{Luq}——一种针对长文本设计的创新采样UQ方法。研究结果表明，\textsc{Luq}在预测模型输出的事实性方面，表现超过了传统基线方法（如Gemini Pro的负相关系数达到-0.85）。利用\textsc{Luq}，我们进一步分析了几种流行LLMs的回应置信度分布，并探讨了这与回应事实性之间的关系。我们发现，LLMs在创作关于稀有事实的长文本时显得不太自信，而像GPT-4这样事实性较强的模型则倾向于回避那些它不确定的问题。为了提升LLM回应的真实性，我们提出了\textsc{Luq-Ensemble}方法，通过整合多个模型的回应，并筛选出不确定性最低的答案。这种集成手段显著提升了最佳独立LLM输出的真实度。

> Large Language Models (LLMs) have demonstrated remarkable capability in a variety of NLP tasks. Despite their effectiveness, these models are prone to generate nonfactual content. Uncertainty Quantification (UQ) is pivotal in enhancing our understanding of a model's confidence in its generated content, thereby aiding in the mitigation of nonfactual outputs. Existing research on UQ predominantly targets short text generation, typically yielding brief, word-limited responses. However, real-world applications frequently necessitate much longer responses. Our study first highlights the limitations of current UQ methods in handling long text generation. We then introduce \textsc{Luq}, a novel sampling-based UQ approach specifically designed for long text. Our findings reveal that \textsc{Luq} outperforms existing baseline methods in correlating with the model's factuality scores (negative coefficient of -0.85 observed for Gemini Pro). With \textsc{Luq} as the tool for UQ, we investigate behavior patterns of several popular LLMs' response confidence spectrum and how that interplays with the response' factuality. We identify that LLMs lack confidence in generating long text for rare facts and a factually strong model (i.e. GPT-4) tends to reject questions it is not sure about. To further improve the factual accuracy of LLM responses, we propose a method called \textsc{Luq-Ensemble} that ensembles responses from multiple models and selects the response with the least uncertainty. The ensembling method greatly improves the response factuality upon the best standalone LLM.

[Arxiv](https://arxiv.org/abs/2403.20279)