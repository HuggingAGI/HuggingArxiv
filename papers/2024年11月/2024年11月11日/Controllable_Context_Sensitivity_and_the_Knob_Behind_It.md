# 可控的上下文敏感度及其背后的调节钮

发布时间：2024年11月11日

`LLM理论` `语言模型`

> Controllable Context Sensitivity and the Knob Behind It

# 摘要

> 在进行预测时，语言模型得权衡对上下文和先验知识的依赖程度。选择模型对上下文的敏感度是一项关键功能，能让模型在检索增强生成和问答等任务中表现出众。本文中，我们探寻能控制这种敏感度的旋钮，以明确语言模型是依据上下文还是先验知识作答。为引导这一探寻，我们设计了一个有关可控上下文敏感度的任务。在此任务里，先给模型提供一个上下文（巴黎在英国）和一个问题（巴黎在哪？）；接着指示模型运用先验知识或上下文知识，并评估其对两种意图（法国或英国）能否给出正确答案。当针对此任务进行微调时，Llama-3.1、Mistral-v0.3 以及 Gemma-2 的指令调整版本能高精度（85%-95%）解决。分析这些高性能模型时，我们借助新的线性时间算法，确定了哪些层可能对上下文敏感度至关重要。然后，在每个模型中，我们在单个层里识别出一个 1-D 子空间，它编码了模型是遵循上下文还是先验知识。有趣的是，尽管在微调模型中识别出这个子空间，但发现完全相同的子空间不仅在该模型中有效，在该模型家族的非微调指令和基础模型中同样是个有效旋钮。最后，我们表明模型的性能与它在这个子空间中区分同意上下文和忽略上下文答案的清晰程度有很强的相关性。这些结果显示，单个子空间有助于模型在上下文和先验知识间抉择，暗示了控制此行为的一个简单基本机制。

> When making predictions, a language model must trade off how much it relies on its context vs. its prior knowledge. Choosing how sensitive the model is to its context is a fundamental functionality, as it enables the model to excel at tasks like retrieval-augmented generation and question-answering. In this paper, we search for a knob which controls this sensitivity, determining whether language models answer from the context or their prior knowledge. To guide this search, we design a task for controllable context sensitivity. In this task, we first feed the model a context (Paris is in England) and a question (Where is Paris?); we then instruct the model to either use its prior or contextual knowledge and evaluate whether it generates the correct answer for both intents (either France or England). When fine-tuned on this task, instruction-tuned versions of Llama-3.1, Mistral-v0.3, and Gemma-2 can solve it with high accuracy (85-95%). Analyzing these high-performing models, we narrow down which layers may be important to context sensitivity using a novel linear time algorithm. Then, in each model, we identify a 1-D subspace in a single layer that encodes whether the model follows context or prior knowledge. Interestingly, while we identify this subspace in a fine-tuned model, we find that the exact same subspace serves as an effective knob in not only that model but also non-fine-tuned instruct and base models of that model family. Finally, we show a strong correlation between a model's performance and how distinctly it separates context-agreeing from context-ignoring answers in this subspace. These results suggest a single subspace facilitates how the model chooses between context and prior knowledge, hinting at a simple fundamental mechanism that controls this behavior.

[Arxiv](https://arxiv.org/abs/2411.07404)