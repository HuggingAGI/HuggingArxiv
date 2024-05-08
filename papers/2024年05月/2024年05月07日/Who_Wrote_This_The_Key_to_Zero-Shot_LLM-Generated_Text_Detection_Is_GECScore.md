# 这篇文章的作者是谁？GECScore 是识别零-shot LLM 生成文本的关键工具。

发布时间：2024年05月07日

`LLM应用

这篇论文介绍了一种新颖的零-shot检测方法，用于区分大型语言模型（LLM）生成的文本和人类编写的文本。该方法利用了LLM生成文本中语法错误较少的特点，通过计算语法错误修正分数（GECScore）来实现文本来源的精准区分。这种方法不需要依赖大量的训练数据，且在实验中表现出了优于现有技术的性能，包括对释义和对抗攻击的抵抗力。因此，它属于LLM应用的范畴，因为它提供了一种实际应用中检测LLM生成文本的工具或技术。` `文本检测`

> Who Wrote This? The Key to Zero-Shot LLM-Generated Text Detection Is GECScore

# 摘要

> 大型语言模型（LLM）生成的文本检测器，其效能高度依赖于丰富的训练数据。然而，我们提出的黑盒零-shot检测方法，无需此类数据，巧妙地利用了人类文本中常见的语法错误多于LLM生成文本这一特点。通过计算语法错误修正分数（GECScore），我们能精准区分文本来源。实验证明，我们的方法不仅超越了现有的零-shot和监督技术，平均AUROC高达98.7%，更展现出对释义和对抗攻击的卓越抵抗力。

> The efficacy of an large language model (LLM) generated text detector depends substantially on the availability of sizable training data. White-box zero-shot detectors, which require no such data, are nonetheless limited by the accessibility of the source model of the LLM-generated text. In this paper, we propose an simple but effective black-box zero-shot detection approach, predicated on the observation that human-written texts typically contain more grammatical errors than LLM-generated texts. This approach entails computing the Grammar Error Correction Score (GECScore) for the given text to distinguish between human-written and LLM-generated text. Extensive experimental results show that our method outperforms current state-of-the-art (SOTA) zero-shot and supervised methods, achieving an average AUROC of 98.7% and showing strong robustness against paraphrase and adversarial perturbation attacks.

[Arxiv](https://arxiv.org/abs/2405.04286)