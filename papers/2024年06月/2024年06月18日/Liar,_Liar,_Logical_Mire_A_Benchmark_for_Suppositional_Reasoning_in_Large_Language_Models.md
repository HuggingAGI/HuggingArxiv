# 谎言迷局：大型语言模型中假设推理的新基准

发布时间：2024年06月18日

`Agent

这篇论文关注的是大型语言模型（如Llama 3和Mixtral-8x7B）在解决逻辑谜题（如骑士与骗子问题）中的表现。这些问题需要模型具备推理和理解陈述真实性的能力。论文通过TruthQuest基准评估了这些模型的性能，并分析了它们在理解和推断逻辑含义方面的挑战。这种类型的研究通常归类为Agent，因为它涉及评估和改进模型作为智能代理在特定任务上的表现。` `逻辑谜题` `人工智能`

> Liar, Liar, Logical Mire: A Benchmark for Suppositional Reasoning in Large Language Models

# 摘要

> 骑士与骗子问题是一种经典的逻辑谜题，角色或说真话或撒谎，玩家需根据其陈述推断身份。这类谜题考验玩家通过假设情景评估陈述真实性的能力。本文推出的TruthQuest基准，基于此类谜题，涵盖了多样的复杂问题。评估发现，大型语言模型如Llama 3和Mixtral-8x7B在解决这些问题上表现不佳。分析显示，较弱的模型常在理解真假概念上犯错，而更强的模型则在推断虚假陈述的逻辑含义时遇到挑战。

> Knights and knaves problems represent a classic genre of logical puzzles where characters either tell the truth or lie. The objective is to logically deduce each character's identity based on their statements. The challenge arises from the truth-telling or lying behavior, which influences the logical implications of each statement. Solving these puzzles requires not only direct deductions from individual statements, but the ability to assess the truthfulness of statements by reasoning through various hypothetical scenarios. As such, knights and knaves puzzles serve as compelling examples of suppositional reasoning. In this paper, we introduce $\textit{TruthQuest}$, a benchmark for suppositional reasoning based on the principles of knights and knaves puzzles. Our benchmark presents problems of varying complexity, considering both the number of characters and the types of logical statements involved. Evaluations on $\textit{TruthQuest}$ show that large language models like Llama 3 and Mixtral-8x7B exhibit significant difficulties solving these tasks. A detailed error analysis of the models' output reveals that lower-performing models exhibit a diverse range of reasoning errors, frequently failing to grasp the concept of truth and lies. In comparison, more proficient models primarily struggle with accurately inferring the logical implications of potentially false statements.

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/wizard.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/elf_a.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/elf_b.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/elf_c.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x1.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x2.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x3.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x4.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x5.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x6.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x7.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x8.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x9.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x10.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x11.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x12.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x13.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x14.png)

![谎言迷局：大型语言模型中假设推理的新基准](../../../paper_images/2406.12546/x15.png)

[Arxiv](https://arxiv.org/abs/2406.12546)