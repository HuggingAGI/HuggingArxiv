# 思维链机制探秘：迭代头研究

发布时间：2024年06月04日

`LLM理论

理由：这篇论文探讨了链式思维推理（CoT）在大型语言模型中的内在机制和触发条件，特别是在变换器模型中的生成过程。研究关注的是CoT的注意力机制——“迭代头”，以及其在注意力层面的形成与运作。这些内容属于对大型语言模型内部工作原理的理论探讨，因此归类为LLM理论。` `机器学习`

> Iteration Head: A Mechanistic Study of Chain-of-Thought

# 摘要

> 链式思维推理（CoT）已证明能有效提升大型语言模型的实证表现和理论近似能力。尽管如此，我们对CoT能力的内在机制及其触发条件的理解尚浅。本研究在可控且易于解读的环境下，揭示了CoT推理在变换器模型中的生成过程。研究发现了一种专为迭代推理设计的注意力机制——“迭代头”，并详细追踪了其在注意力层面的形成与运作，同时评估了由此产生的CoT技能在不同任务间的迁移能力。

> Chain-of-Thought (CoT) reasoning is known to improve Large Language Models both empirically and in terms of theoretical approximation power. However, our understanding of the inner workings and conditions of apparition of CoT capabilities remains limited. This paper helps fill this gap by demonstrating how CoT reasoning emerges in transformers in a controlled and interpretable setting. In particular, we observe the appearance of a specialized attention mechanism dedicated to iterative reasoning, which we coined "iteration heads". We track both the emergence and the precise working of these iteration heads down to the attention level, and measure the transferability of the CoT skills to which they give rise between tasks.

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x1.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x2.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x3.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x4.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x5.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x6.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x7.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x8.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x9.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x10.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x11.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x12.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x13.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x14.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x15.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x16.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x17.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x18.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x19.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x20.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x21.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x22.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x23.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x24.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x25.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x26.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x27.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x28.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x29.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x30.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x31.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x32.png)

![思维链机制探秘：迭代头研究](../../../paper_images/2406.02128/x33.png)

[Arxiv](https://arxiv.org/abs/2406.02128)