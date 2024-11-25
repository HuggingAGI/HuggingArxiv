# 大型语言模型是否天生具备道德自我纠正能力？关于自我纠正的机制分析

发布时间：2024年10月27日

`LLM理论` `语言模型` `道德伦理`

> Is Moral Self-correction An Innate Capability of Large Language Models? A Mechanistic Analysis to Self-correction

# 摘要

> 尽管大型语言模型（LLMs）的自我纠正能力备受关注，但其潜在机制仍有待深入探究。在本文中，我们致力于解答有关道德自我纠正的两个关键问题：（1）自我纠正中的诸如思维链（CoT）推理、外部反馈和指导性提示等不同组件，是如何相互作用来达成道德自我纠正的；（2）自我纠正是否为LLMs的固有能力之一？为回答第一个问题，我们探究了不同自我纠正组件如何相互作用来干预隐藏状态中的嵌入道德，进而影响不同的性能表现。针对第二个问题，我们（i）通过在提示中引入弱证据的自然语言干预来评估道德自我纠正的稳健性；（ii）提出了一个名为自我区分的验证框架，该框架要求有效的自我纠正，以使LLMs能够区分理想和不理想的输出。我们的实验结果显示，对于所考虑的任务，不存在普遍最优的自我纠正方法，不过外部反馈和CoT能够带来额外的性能增益。然而，我们的机制分析揭示了指导性提示、CoT和外部反馈之间存在负面交互，意味着内部知识与外部反馈存在冲突。自我区分实验表明，虽然LLMs能够自我纠正其响应，但它们难以可靠地区分期望和不期望的输出。基于我们的经验证据，可以得出结论：道德自我纠正并非LLMs在预训练期间获得的固有能力。

> Though intensive attentions to the self-correction capability of Large Language Models (LLMs), the underlying mechanism of this capability is still under-explored. In this paper, we aim to answer two fundamental questions for moral self-correction: (1) how different components in self-correction, such as Chain-of-Thought (CoT) reasoning, external feedback, and instructional prompts, interact to enable moral self-correction; and (2) is the self-correction one of LLMs' innate capabilities? To answer the first question, we examine how different self-correction components interact to intervene the embedded morality within hidden states, therefore contributing to different performance. For the second question, we (i) evaluate the robustness of moral self-correction by introducing natural language interventions of weak evidence into prompts; (ii) propose a validation framework, self-distinguish, that requires effective self-correction to enable LLMs to distinguish between desirable and undesirable outputs. Our experimental results indicate that there is no universally optimal self-correction method for the tasks considered, although external feedback and CoT can contribute to additional performance gains. However, our mechanistic analysis reveals negative interactions among instructional prompts, CoT, and external feedback, suggesting a conflict between internal knowledge and external feedback. The self-distinguish experiments demonstrate that while LLMs can self-correct their responses, they are unable to reliably distinguish between desired and undesired outputs. With our empirical evidence, we can conclude that moral self-correction is not an innate capability of LLMs acquired during pretraining.

[Arxiv](https://arxiv.org/abs/2410.20513)