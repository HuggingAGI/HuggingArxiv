# 文本去学习让人误以为知识已被遗忘

发布时间：2024年06月19日

`LLM理论

这篇论文探讨了机器遗忘技术在语言模型中的应用及其潜在的反效果，即文本遗忘泄露攻击（TULA）。它分析了在黑盒和白盒环境下，通过对比模型遗忘前后的状态，攻击者如何推断出被遗忘数据的相关信息。这一研究不仅揭示了机器遗忘可能加剧知识泄露的风险，而且为理解语言模型中的安全机制提供了理论基础。因此，这篇论文属于LLM理论分类，因为它深入探讨了语言模型中遗忘机制的理论问题和安全挑战。` `数据安全` `人工智能`

> Textual Unlearning Gives a False Sense of Unlearning

# 摘要

> 语言模型易受“记忆”训练数据的影响，包括大量私密或受版权保护的内容。为保护被遗忘权，机器遗忘技术应运而生，旨在帮助模型高效地“遗忘”敏感信息，降低知识泄露风险。然而，这一机制是否可能事与愿违？本文提出了一种名为文本遗忘泄露攻击（TULA）的新型攻击手段，攻击者仅通过对比遗忘前后的模型状态，便能推断出被遗忘数据的相关信息。我们还展示了TULA在黑盒和白盒环境下的变体。实验结果显示，机器遗忘不仅未能降低风险，反而加剧了知识泄露的可能性。在黑盒测试中，TULA使攻击者识别被遗忘数据的能力提升了超过20%；而在白盒环境下，甚至能以60%以上的准确率还原被遗忘数据。我们的研究首次揭示了机器遗忘在语言模型中可能带来的反效果，为开发更安全的遗忘机制提供了启示。

> Language models (LMs) are susceptible to "memorizing" training data, including a large amount of private or copyright-protected content. To safeguard the right to be forgotten (RTBF), machine unlearning has emerged as a promising method for LMs to efficiently "forget" sensitive training content and mitigate knowledge leakage risks. However, despite its good intentions, could the unlearning mechanism be counterproductive? In this paper, we propose the Textual Unlearning Leakage Attack (TULA), where an adversary can infer information about the unlearned data only by accessing the models before and after unlearning. Furthermore, we present variants of TULA in both black-box and white-box scenarios. Through various experimental results, we critically demonstrate that machine unlearning amplifies the risk of knowledge leakage from LMs. Specifically, TULA can increase an adversary's ability to infer membership information about the unlearned data by more than 20% in black-box scenario. Moreover, TULA can even reconstruct the unlearned data directly with more than 60% accuracy with white-box access. Our work is the first to reveal that machine unlearning in LMs can inversely create greater knowledge risks and inspire the development of more secure unlearning mechanisms.

![文本去学习让人误以为知识已被遗忘](../../../paper_images/2406.13348/x1.png)

![文本去学习让人误以为知识已被遗忘](../../../paper_images/2406.13348/x2.png)

![文本去学习让人误以为知识已被遗忘](../../../paper_images/2406.13348/x3.png)

[Arxiv](https://arxiv.org/abs/2406.13348)