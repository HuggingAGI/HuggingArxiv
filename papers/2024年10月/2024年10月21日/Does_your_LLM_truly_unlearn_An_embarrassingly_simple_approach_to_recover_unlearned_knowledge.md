# 您的大型语言模型（LLM）真的会遗忘吗？一种令人尴尬的简单方法来恢复未遗忘的知识

发布时间：2024年10月21日

`LLM应用` `机器学习`

> Does your LLM truly unlearn? An embarrassingly simple approach to recover unlearned knowledge

# 摘要

> 摘要：大型语言模型（LLMs）在生成文本方面表现出了显著的熟练程度，得益于在大量文本语料库上的广泛训练。然而，LLMs 也可能从其训练数据的多样性和敏感性中获得不良行为，其中可能包括受版权保护和私人内容。机器非学习已被引入作为一种可行的解决方案，以消除此类有问题内容的影响，而无需昂贵且耗时的重新训练。这个过程旨在从 LLMs 中擦除特定知识，同时尽可能多地保留模型的实用性。尽管当前的非学习方法有效，但很少有人关注 LLMs 的现有非学习方法是否真正实现了遗忘，还是仅仅隐藏了知识，而当前的非学习基准未能检测到这一点。本文揭示，对经历过非学习的模型应用量化可以恢复“遗忘”的信息。为了全面评估这一现象，我们使用各种量化技术在多个精度级别上进行了全面的实验。我们发现，对于具有实用性约束的非学习方法，未学习的模型在全精度下平均保留了 21％的预期遗忘知识，在 4 位量化后显著增加到 83％。基于我们的实证发现，我们为观察到的现象提供了理论解释，并提出了一种抗量化的非学习策略来缓解这个复杂的问题......

> 
Abstract:Large language models (LLMs) have shown remarkable proficiency in generating text, benefiting from extensive training on vast textual corpora. However, LLMs may also acquire unwanted behaviors from the diverse and sensitive nature of their training data, which can include copyrighted and private content. Machine unlearning has been introduced as a viable solution to remove the influence of such problematic content without the need for costly and time-consuming retraining. This process aims to erase specific knowledge from LLMs while preserving as much model utility as possible. Despite the effectiveness of current unlearning methods, little attention has been given to whether existing unlearning methods for LLMs truly achieve forgetting or merely hide the knowledge, which current unlearning benchmarks fail to detect. This paper reveals that applying quantization to models that have undergone unlearning can restore the "forgotten" information. To thoroughly evaluate this phenomenon, we conduct comprehensive experiments using various quantization techniques across multiple precision levels. We find that for unlearning methods with utility constraints, the unlearned model retains an average of 21\% of the intended forgotten knowledge in full precision, which significantly increases to 83\% after 4-bit quantization. Based on our empirical findings, we provide a theoretical explanation for the observed phenomenon and propose a quantization-robust unlearning strategy to mitigate this intricate issue...
    

[Arxiv](https://arxiv.org/pdf/2410.16454)