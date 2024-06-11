# SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力

发布时间：2024年06月08日

`LLM应用

这篇论文主要讨论了针对大型语言模型（LLMs）的越狱攻击及其防御机制。论文提出了一种名为SelfDefend的防御框架，该框架通过创建一个影子LLM实例来防御各种越狱攻击，包括基于优化的攻击、基于模板的攻击、高级间接攻击和多语言越狱。此外，论文还探讨了如何通过数据蒸馏技术优化开源防御模型，以提高其性能和降低延迟。这些内容主要关注于LLMs的实际应用场景中的安全问题和防御策略，因此属于LLM应用分类。` `人工智能`

> SelfDefend: LLMs Can Defend Themselves against Jailbreaking in a Practical Manner

# 摘要

> 越狱攻击是一种新兴的对抗手段，它绕过了大型语言模型（LLMs）的安全机制，分为四大类：基于优化的攻击（如贪婪坐标梯度GCG）、基于模板的攻击（如“立即做任何事”）、高级间接攻击（如DrAttack）和多语言越狱。构建一个实用的越狱防御系统颇具挑战，因为它不仅要抵御所有这些攻击，还不能给用户操作带来明显延迟，并且要兼容各种开源和闭源的LLMs。受传统安全领域影子栈防御内存溢出攻击的启发，本文提出了一个名为SelfDefend的通用LLM越狱防御框架。该框架通过创建一个影子LLM防御实例，与主LLM实例并行运作，共同实施基于检查点的访问控制，从而保护主LLM。SelfDefend的有效性基于我们的发现：现有的LLMs能够识别并防御有害的用户查询。我们通过使用GPT-3.5/4模型在多种越狱攻击中验证了这一点。实验表明，SelfDefend能显著降低GPT-3.5和GPT-4的攻击成功率，而对正常查询的影响微乎其微。为了增强防御系统的鲁棒性并降低成本，我们采用了数据蒸馏技术来优化开源防御模型，这些模型在性能上与基于GPT-4的SelfDefend相当，且延迟更低。此外，这些优化后的模型对GCG和提示注入等特定攻击表现出强大的抵抗力。

> Jailbreaking is an emerging adversarial attack that bypasses the safety alignment deployed in off-the-shelf large language models (LLMs) and has evolved into four major categories: optimization-based attacks such as Greedy Coordinate Gradient (GCG), jailbreak template-based attacks such as "Do-Anything-Now", advanced indirect attacks like DrAttack, and multilingual jailbreaks. However, delivering a practical jailbreak defense is challenging because it needs to not only handle all the above jailbreak attacks but also incur negligible delay to user prompts, as well as be compatible with both open-source and closed-source LLMs.
  Inspired by how the traditional security concept of shadow stacks defends against memory overflow attacks, this paper introduces a generic LLM jailbreak defense framework called SelfDefend, which establishes a shadow LLM defense instance to concurrently protect the target LLM instance in the normal stack and collaborate with it for checkpoint-based access control. The effectiveness of SelfDefend builds upon our observation that existing LLMs (both target and defense LLMs) have the capability to identify harmful prompts or intentions in user queries, which we empirically validate using the commonly used GPT-3.5/4 models across all major jailbreak attacks. Our measurements show that SelfDefend enables GPT-3.5 to suppress the attack success rate (ASR) by 8.97-95.74% (average: 60%) and GPT-4 by even 36.36-100% (average: 83%), while incurring negligible effects on normal queries. To further improve the defense's robustness and minimize costs, we employ a data distillation approach to tune dedicated open-source defense models. These models outperform four SOTA defenses and match the performance of GPT-4-based SelfDefend, with significantly lower extra delays. We also empirically show that the tuned models are robust to targeted GCG and prompt injection attacks.

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x1.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x2.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x3.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x4.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x5.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x6.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x7.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x8.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x9.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x10.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x11.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x12.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x13.png)

![SelfDefend：大型语言模型（LLMs）具备实际防御越狱攻击的能力](../../../paper_images/2406.05498/x14.png)

[Arxiv](https://arxiv.org/abs/2406.05498)