# 逻辑思维：为大型语言模型注入逻辑，实现全面推理

发布时间：2024年09月26日

`LLM应用` `人工智能` `逻辑推理`

> Logic-of-Thought: Injecting Logic into Contexts for Full Reasoning in Large Language Models

# 摘要

> 尽管大型语言模型 (LLM) 在多种任务中表现出色，但在复杂逻辑推理任务中仍显不足。虽然 Chain-of-Thought 等提示方法能在一定程度上提升推理能力，但其生成的结论有时与推理链不符。为此，我们提出 Logic-of-Thought (LoT) 提示方法，通过命题逻辑生成扩展逻辑信息，并将其作为输入提示的增强，从而提升逻辑推理能力。LoT 可与现有提示方法无缝结合，实验证明，它在五个逻辑推理任务中显著提升了多种提示方法的性能，如在 ReClor 数据集上提升 Chain-of-Thought 性能 +4.35%，在 LogiQA 上提升 Chain-of-Thought with Self-Consistency 性能 +5%，在 ProofWriter 数据集上提升 Tree-of-Thoughts 性能 +8%。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across various tasks but their performance in complex logical reasoning tasks remains unsatisfactory. Although some prompting methods, such as Chain-of-Thought, can improve the reasoning ability of LLMs to some extent, they suffer from an unfaithful issue where derived conclusions may not align with the generated reasoning chain. To address this issue, some studies employ the approach of propositional logic to further enhance logical reasoning abilities of LLMs. However, the potential omissions in the extraction of logical expressions in these methods can cause information loss in the logical reasoning process, thereby generating incorrect results. To this end, we propose Logic-of-Thought (LoT) prompting which employs propositional logic to generate expanded logical information from input context, and utilizes the generated logical information as an additional augmentation to the input prompts, thereby enhancing the capability of logical reasoning. The LoT is orthogonal to existing prompting methods and can be seamlessly integrated with them. Extensive experiments demonstrate that LoT boosts the performance of various prompting methods with a striking margin across five logical reasoning tasks. In particular, the LoT enhances Chain-of-Thought's performance on the ReClor dataset by +4.35%; moreover, it improves Chain-of-Thought with Self-Consistency's performance on LogiQA by +5%; additionally, it boosts performance of Tree-of-Thoughts on ProofWriter dataset by +8%.

[Arxiv](https://arxiv.org/abs/2409.17539)