# Bitune：双向指令调优法

发布时间：2024年05月23日

`LLM理论

理由：这篇论文介绍了一种名为Bitune的新方法，该方法通过结合因果和双向注意力机制来优化大型语言模型的指令调优过程。这种方法涉及对模型参数的微调，以提高模型在特定任务上的性能。论文的重点在于提出和验证一种新的模型优化技术，这属于对大型语言模型（LLM）的理论研究，探讨了模型的内部机制和改进方法，因此应归类于LLM理论。` `机器学习`

> Bitune: Bidirectional Instruction-Tuning

# 摘要

> 我们提出了一种名为Bitune的新方法，它通过结合因果和双向注意力机制，优化了大型语言模型的指令调优过程，显著提升了下游任务的表现。通过引入两组参数并采用高效的参数微调技术，Bitune能够更精确地捕捉指令的含义。这种方法不仅在常识推理、算术和语言理解等任务上实现了零-shot性能的显著提升，而且通过详尽的消融研究，证明了其对不同参数高效微调技术的适应性。

> We introduce Bitune, a method that improves instruction-tuning of pretrained decoder-only large language models, leading to consistent gains on downstream tasks. Bitune applies both causal and bidirectional attention to the prompt, to obtain a better representation of the query or instruction. We realize this by introducing two sets of parameters, for which we apply parameter-efficient finetuning techniques. These causal and bidirectional features are then combined into a weighted average with trainable coefficients, which is subsequently used to generate new tokens. We demonstrate significant improvements in zero-shot performance on commonsense reasoning, arithmetic, and language understanding tasks, while extensive ablation studies validate the role of each component and demonstrate the method's agnosticism to different PEFT techniques.

[Arxiv](https://arxiv.org/abs/2405.14862)