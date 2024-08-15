# 对齐增强解码：利用令牌级自适应精炼概率分布进行防御

发布时间：2024年08月14日

`LLM理论` `网络安全` `人工智能`

> Alignment-Enhanced Decoding:Defending via Token-Level Adaptive Refining of Probability Distributions

# 摘要

> 大型语言模型易受越狱攻击，可能生成有害内容。传统防御措施虽通过干扰或审查输入降低风险，却忽视了导致对齐失败的竞争目标。为此，我们提出对齐增强解码（AED），一种新颖防御策略，通过自适应解码直击越狱问题根源。我们首先量化对齐失败，利用自我评估反馈计算后对齐对数，进而自适应融合AED与原始对数，生成既无害又有益的输出。实验涵盖五种模型与四种常见越狱手段，证实了AED的有效性。代码已公开，详见https://github.com/GIGABaozi/AED.git。

> Large language models are susceptible to jailbreak attacks, which can result in the generation of harmful content. While prior defenses mitigate these risks by perturbing or inspecting inputs, they ignore competing objectives, the underlying cause of alignment failures. In this paper, we propose Alignment-Enhanced Decoding (AED), a novel defense that employs adaptive decoding to address the root causes of jailbreak issues. We first define the Competitive Index to quantify alignment failures and utilize feedback from self-evaluation to compute post-alignment logits. Then, AED adaptively combines AED and post-alignment logits with the original logits to obtain harmless and helpful distributions. Consequently, our method enhances safety alignment while maintaining helpfulness. We conduct experiments across five models and four common jailbreaks, with the results validating the effectiveness of our approach. Code is available at https://github.com/GIGABaozi/AED.git.

[Arxiv](https://arxiv.org/abs/2408.07663)