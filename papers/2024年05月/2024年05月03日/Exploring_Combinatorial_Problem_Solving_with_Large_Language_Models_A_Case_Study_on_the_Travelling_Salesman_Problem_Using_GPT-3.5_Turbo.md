# 本研究深入探讨了大型语言模型在解决组合问题上的能力，特别是以 GPT-3.5 Turbo 为工具，对旅行商问题进行了一项案例研究。

发布时间：2024年05月03日

`LLM应用` `组合优化`

> Exploring Combinatorial Problem Solving with Large Language Models: A Case Study on the Travelling Salesman Problem Using GPT-3.5 Turbo

# 摘要

> 大型语言模型（LLMs）是深度学习领域的佼佼者，专为文本输入生成文本而设计。尽管研究者们正致力于将这些模型应用于更复杂的任务，如代码编写和逻辑推理，但探索LLMs如何解决组合问题的研究却寥寥无几。本研究旨在探究LLMs在解决经典问题——旅行商问题（TSP）上的潜力。我们使用GPT-3.5 Turbo，通过零样本上下文学习、少样本上下文学习以及思维链（CoT）等多种方法进行了实验。随后，我们对GPT-3.5 Turbo进行了针对性的微调，以处理特定规模的问题，并通过一系列不同规模的实例进行了测试。微调后的模型在处理与训练实例规模相同或更大的问题时，均展现出了出色的性能。为了进一步提升微调模型的性能而不增加额外的训练成本，我们采用了自集成策略，以提升解决方案的精度。

> Large Language Models (LLMs) are deep learning models designed to generate text based on textual input. Although researchers have been developing these models for more complex tasks such as code generation and general reasoning, few efforts have explored how LLMs can be applied to combinatorial problems. In this research, we investigate the potential of LLMs to solve the Travelling Salesman Problem (TSP). Utilizing GPT-3.5 Turbo, we conducted experiments employing various approaches, including zero-shot in-context learning, few-shot in-context learning, and chain-of-thoughts (CoT). Consequently, we fine-tuned GPT-3.5 Turbo to solve a specific problem size and tested it using a set of various instance sizes. The fine-tuned models demonstrated promising performance on problems identical in size to the training instances and generalized well to larger problems. Furthermore, to improve the performance of the fine-tuned model without incurring additional training costs, we adopted a self-ensemble approach to improve the quality of the solutions.

[Arxiv](https://arxiv.org/abs/2405.01997)