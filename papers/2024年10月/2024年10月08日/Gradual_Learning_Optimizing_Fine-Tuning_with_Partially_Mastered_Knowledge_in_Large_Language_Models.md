# 渐进学习：利用大语言模型中已掌握的部分知识，优化微调过程

发布时间：2024年10月08日

`LLM理论` `人工智能`

> Gradual Learning: Optimizing Fine-Tuning with Partially Mastered Knowledge in Large Language Models

# 摘要

> 在预训练阶段，LLM 从海量文本中汲取知识。然而，在微调和推理阶段，模型可能遇到未曾接触的知识，导致幻觉和性能下降。这问题影响深远，因为模型在预训练后必然会遇到新知识。此外，微调常用于使 LLM 适应特定任务，但这也限制了其学习和整合新信息的能力。微调效果取决于知识类型，研究表明，在部分掌握的知识上微调，如在非贪婪解码下可能正确的问答对，能减少幻觉并获取新知。但此法仍可能导致已掌握知识遗忘，限制微调数据集范围，影响整体改进。鉴于模型推理能力和知识间的联系，随着微调中利用现有知识能力的提升，未掌握知识可能变得更易理解。为此，我们进行了实验，提出两阶段微调策略，不仅提升整体测试准确性和知识保留，还保持了先前掌握内容的准确性。在 WikiQA 数据集上微调时，我们的方法使模型获取的知识量增加了 24%。

> During the pretraining phase, large language models (LLMs) acquire vast amounts of knowledge from extensive text corpora. Nevertheless, in later stages such as fine-tuning and inference, the model may encounter knowledge not covered in the initial training, which can lead to hallucinations and degraded performance. This issue has a profound impact on the model's capabilities, as it will inevitably face out-of-scope knowledge after pretraining. Furthermore, fine-tuning is often required to adapt LLMs to domain-specific tasks. However, this phenomenon limits the model's ability to learn and integrate new information during fine-tuning. The effectiveness of fine-tuning largely depends on the type of knowledge involved. Existing research suggests that fine-tuning the model on partially mastered knowledge-for instance, question-answer pairs where the model has a chance of providing correct responses under non-greedy decoding-can enable the model to acquire new knowledge while mitigating hallucination. Notably, this approach can still lead to the forgetting of fully mastered knowledge, constraining the fine-tuning dataset to a narrower range and limiting the model's overall potential for improvement. Given the model's intrinsic reasoning abilities and the interconnectedness of different knowledge areas, it is likely that as the model's capacity to utilize existing knowledge improves during fine-tuning, previously unmastered knowledge may become more understandable. To explore this hypothesis, we conducted experiments and, based on the results, proposed a two-stage fine-tuning strategy. This approach not only improves the model's overall test accuracy and knowledge retention but also preserves its accuracy on previously mastered content. When fine-tuning on the WikiQA dataset, our method increases the amount of knowledge acquired by the model in this stage by 24%.

[Arxiv](https://arxiv.org/abs/2410.05802)