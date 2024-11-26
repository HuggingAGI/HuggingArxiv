# VaLiD：借由视觉层融合对比解码来缓解大型视觉语言模型的幻觉

发布时间：2024年11月24日

`LLM应用` `多模态`

> VaLiD: Mitigating the Hallucination of Large Vision Language Models by Visual Layer Fusion Contrastive Decoding

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务推理方面表现卓越。然而，它们常生成看似合理却未精准反映视觉内容的回应，此现象称作幻觉。近来的方法引入了免训练的手段，于推理阶段调整解码策略以减轻幻觉，通常把幻觉归咎于语言模型自身。但我们的分析显示，视觉编码过程中的扭曲极大影响了模型的推理精度。具体来说，早期的视觉层或许能保留关键特征，可随着信息向输出层传递会逐渐扭曲。基于这些发现，我们从视觉编码视角提出了一种新颖的减轻幻觉的方法：	extbf{V}isu	extbf{a}l 	extbf{L}ayer Fus	extbf{i}on Contrastive 	extbf{D}ecoding（VaLiD）。该方法借助不确定性来引导视觉隐藏层的选取，矫正视觉编码过程中的扭曲，进而提升生成文本的可靠性。实验结果表明，VaLiD 在各类基准测试中有效减少了幻觉，相比多种基线方法实现了最先进的性能。

> Large Vision-Language Models (LVLMs) have demonstrated outstanding performance in multimodal task reasoning. However, they often generate responses that appear plausible yet do not accurately reflect the visual content, a phenomenon known as hallucination. Recent approaches have introduced training-free methods that mitigate hallucinations by adjusting the decoding strategy during inference stage, typically attributing hallucination to the language model itself. Our analysis, however, reveals that distortions in the visual encoding process significantly affect the model's reasoning accuracy. Specifically, earlier visual layers may retain key features but gradually distort as the information propagates toward the output layer. Building on these findings, we propose a novel hallucination-mitigation method from the visual encoding perspective: \textbf{V}isu\textbf{a}l \textbf{L}ayer Fus\textbf{i}on Contrastive \textbf{D}ecoding (VaLiD). This method utilizes uncertainty to guide the selection of visual hidden layers, correcting distortions in the visual encoding process and thereby improving the reliability of generated text. Experimental results show that VaLiD effectively reduces hallucinations across various benchmarks, achieving state-of-the-art performance compared to multiple baseline methods.

[Arxiv](https://arxiv.org/abs/2411.15839)