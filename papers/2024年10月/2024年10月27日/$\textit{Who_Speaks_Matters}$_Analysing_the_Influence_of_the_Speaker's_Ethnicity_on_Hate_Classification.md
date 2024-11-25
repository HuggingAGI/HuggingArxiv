# $	extit{谁发言很重要}$：剖析发言者的种族对仇恨分类的影响

发布时间：2024年10月27日

`LLM应用` `内容审核` `仇恨言论检测`

> $\textit{Who Speaks Matters}$: Analysing the Influence of the Speaker's Ethnicity on Hate Classification

# 摘要

> 大型语言模型（LLMs）为可扩展的内容审核（比如仇恨言论检测）带来了诱人的希望。然而，它们也存在脆弱性，且对边缘化群体和方言有偏见。因此，在将其应用于仇恨言论检测这类高风险任务时，必须严格审视。在本研究中，我们探究了利用 LLMs 进行仇恨言论分类的稳健性，特别是当说话者种族的显性和隐性标记被注入输入时。对于显性标记，我们会注入提及说话者身份的短语；对于隐性标记，则注入方言特征。通过分析在这些标记存在时模型输出翻转的频次，我们揭示了 4 个热门 LLMs 和 5 个种族的不同脆弱程度。我们发现，输入中隐性方言标记的存在比显性标记更易导致模型输出翻转。而且，不同种族的翻转百分比也有所不同。最后，我们发现规模更大的模型更稳健。我们的发现表明，在将 LLMs 用于仇恨言论检测等高风险任务时，需要谨慎对待。

> Large Language Models (LLMs) offer a lucrative promise for scalable content moderation, including hate speech detection. However, they are also known to be brittle and biased against marginalised communities and dialects. This requires their applications to high-stakes tasks like hate speech detection to be critically scrutinized. In this work, we investigate the robustness of hate speech classification using LLMs, particularly when explicit and implicit markers of the speaker's ethnicity are injected into the input. For the explicit markers, we inject a phrase that mentions the speaker's identity. For the implicit markers, we inject dialectal features. By analysing how frequently model outputs flip in the presence of these markers, we reveal varying degrees of brittleness across 4 popular LLMs and 5 ethnicities. We find that the presence of implicit dialect markers in inputs causes model outputs to flip more than the presence of explicit markers. Further, the percentage of flips varies across ethnicities. Finally, we find that larger models are more robust. Our findings indicate the need for exercising caution in deploying LLMs for high-stakes tasks like hate speech detection.

[Arxiv](https://arxiv.org/abs/2410.20490)