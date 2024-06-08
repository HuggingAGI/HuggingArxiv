# 语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。

发布时间：2024年06月04日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在算术任务上的表现，特别是在多位数乘法的首位和末位数字预测上的差异。它分析了LLMs在特定任务上的性能，并提出了改进方法，这涉及到对LLMs内部工作机制的理解和优化。因此，这篇论文更偏向于对LLMs理论层面的研究和探讨，而不是具体的应用、代理行为或检索增强生成（RAG）技术。` `人工智能`

> Language Models Do Hard Arithmetic Tasks Easily and Hardly Do Easy Arithmetic Tasks

# 摘要

> 大型语言模型（LLMs）在算术任务上的表现一直是热议的话题。我们观察到，尽管需要复杂的复合运算，LLMs仍能准确自信地预测多位数乘法的首位数字，且无需复杂的思维链推理。然而，对于多位数乘法的末位数字预测，LLMs的表现却不尽人意，这一任务实际上等同于简单的1位数乘法，理应容易掌握。我们的研究表明，当LLMs基于所有正确的更高位数字进行调整时，末位数字的预测准确性显著提升，使用Llama 2-13B模型在5位数乘法任务中的正确率提高了230%，而Mistral-7B模型的提升幅度也达到了150%。

> The ability (and inability) of large language models (LLMs) to perform arithmetic tasks has been the subject of much theoretical and practical debate. We show that LLMs are frequently able to correctly and confidently predict the first digit of n-digit by m-digit multiplication tasks without using chain of thought reasoning, despite these tasks require compounding operations to solve. Simultaneously, LLMs in practice often fail to correctly or confidently predict the last digit of an n-digit by m-digit multiplication, a task equivalent to 1-digit by 1-digit multiplication which can be easily learned or memorized. We show that the latter task can be solved more robustly when the LLM is conditioned on all of the correct higher-order digits, which on average increases the confidence of the correct last digit on 5-digit by 5-digit multiplication tasks using Llama 2-13B by over 230% (0.13 to 0.43) and Mistral-7B by 150% (0.22 to 0.55).

![语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。](../../../paper_images/2406.02356/Llama-2-7b-hf_592392_token_dist_position_1.png)

![语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。](../../../paper_images/2406.02356/Llama-2-13b-hf_592392_token_dist_position_1.png)

![语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。](../../../paper_images/2406.02356/Llama-2-7b-hf_592392_token_dist_position_6.png)

![语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。](../../../paper_images/2406.02356/Llama-2-13b-hf_592392_token_dist_position_6.png)

![语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。](../../../paper_images/2406.02356/Llama-2-7b-hf_59239223206_token_dist_position_6.png)

![语言模型轻松应对复杂算术挑战，却在简单算术任务上显得力不从心。](../../../paper_images/2406.02356/Llama-2-13b-hf_59239223206_token_dist_position_6.png)

[Arxiv](https://arxiv.org/abs/2406.02356)