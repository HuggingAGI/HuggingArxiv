# GlitchProber 致力于在大型语言模型中有效检测并缓解 Glitch Tokens 问题。

发布时间：2024年08月09日

`LLM理论` `人工智能`

> GlitchProber: Advancing Effective Detection and Mitigation of Glitch Tokens in Large Language Models

# 摘要

> 大型语言模型（LLM）在自然语言处理领域取得了空前成功，但其内部机制的不透明性引发了对其可信度和可解释性的广泛担忧。最新研究发现，模型词汇空间中存在一类被称为“故障令牌”的异常标记，这些标记一旦被输入，可能导致模型输出错误、无关甚至有害的结果，严重威胁LLM的可靠性与实用性。本研究旨在深入理解故障令牌，并提出相应的检测与缓解技术。我们首先揭示了故障令牌在LLM中引发的特征，这些特征通过中间层注意力模式和动态信息分布的显著偏差得以证实。基于此，我们开发了GlitchProber工具，该工具通过小规模采样、主成分分析加速特征提取及简单分类器进行高效词汇筛选，进一步纠正模型中间层的异常值，以减轻故障令牌的破坏性影响。在五个主流开源LLM上的评估显示，GlitchProber在效率、精确度和召回率方面均优于现有方法，平均F1分数达到0.86，平均修复率高达50.06%。GlitchProber不仅为应对故障令牌挑战开辟了新路径，更激发了未来研究向更健壮、可解释的LLM迈进。

> Large language models (LLMs) have achieved unprecedented success in the field of natural language processing. However, the black-box nature of their internal mechanisms has brought many concerns about their trustworthiness and interpretability. Recent research has discovered a class of abnormal tokens in the model's vocabulary space and named them "glitch tokens". Those tokens, once included in the input, may induce the model to produce incorrect, irrelevant, or even harmful results, drastically undermining the reliability and practicality of LLMs.
  In this work, we aim to enhance the understanding of glitch tokens and propose techniques for their detection and mitigation. We first reveal the characteristic features induced by glitch tokens on LLMs, which are evidenced by significant deviations in the distributions of attention patterns and dynamic information from intermediate model layers. Based on the insights, we develop GlitchProber, a tool for efficient glitch token detection and mitigation. GlitchProber utilizes small-scale sampling, principal component analysis for accelerated feature extraction, and a simple classifier for efficient vocabulary screening. Taking one step further, GlitchProber rectifies abnormal model intermediate layer values to mitigate the destructive effects of glitch tokens. Evaluated on five mainstream open-source LLMs, GlitchProber demonstrates higher efficiency, precision, and recall compared to existing approaches, with an average F1 score of 0.86 and an average repair rate of 50.06%. GlitchProber unveils a novel path to address the challenges posed by glitch tokens and inspires future research toward more robust and interpretable LLMs.

[Arxiv](https://arxiv.org/abs/2408.04905)