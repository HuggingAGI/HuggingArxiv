# QuanTA：量子启发的矩阵适应技术，实现大型语言模型的高效高秩微调

发布时间：2024年05月31日

`LLM理论

这篇论文介绍了一种新的微调技术——量子信息张量适应（QuanTA），它是一种针对大规模预训练语言模型的微调方法。该技术利用了量子电路启发的技术，实现了高秩微调，并在理论上有普遍性定理和秩表示定理的支持。论文中提到的实验结果表明，QuanTA在多个方面优于传统方法，且具有更好的可扩展性和参数效率。此外，QuanTA能够与现有微调算法集成，提升性能。这些特点使得该论文更符合LLM理论分类，因为它探讨了大型语言模型微调的理论和方法，而不是直接应用于特定的Agent或RAG系统，也不是讨论LLM的具体应用案例。` `预训练语言模型`

> QuanTA: Efficient High-Rank Fine-Tuning of LLMs with Quantum-Informed Tensor Adaptation

# 摘要

> 我们创新性地提出了量子信息张量适应（QuanTA），一种简便且无额外推理负担的大规模预训练语言模型微调技术。借助量子电路启发的技术，QuanTA实现了高秩微调，突破了低秩适应（LoRA）在复杂任务上的局限。理论上的普遍性定理和秩表示定理为我们的方法提供了坚实支撑。实验结果显示，QuanTA在常识推理、算术推理及可扩展性方面均优于传统方法，且在参数更少的情况下表现更佳。此外，QuanTA可与现有微调算法无缝集成，进一步提升性能，为大型语言模型的微调提供了一种高效且可扩展的解决方案，推动了自然语言处理技术的进步。

> We propose Quantum-informed Tensor Adaptation (QuanTA), a novel, easy-to-implement, fine-tuning method with no inference overhead for large-scale pre-trained language models. By leveraging quantum-inspired methods derived from quantum circuit structures, QuanTA enables efficient high-rank fine-tuning, surpassing the limitations of Low-Rank Adaptation (LoRA)--low-rank approximation may fail for complicated downstream tasks. Our approach is theoretically supported by the universality theorem and the rank representation theorem to achieve efficient high-rank adaptations. Experiments demonstrate that QuanTA significantly enhances commonsense reasoning, arithmetic reasoning, and scalability compared to traditional methods. Furthermore, QuanTA shows superior performance with fewer trainable parameters compared to other approaches and can be designed to integrate with existing fine-tuning algorithms for further improvement, providing a scalable and efficient solution for fine-tuning large language models and advancing state-of-the-art in natural language processing.

[Arxiv](https://arxiv.org/abs/2406.00132)