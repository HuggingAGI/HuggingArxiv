# InfinityMATH：一款可扩展的程序化数学推理指令调优数据集

发布时间：2024年08月09日

`LLM应用` `人工智能`

> InfinityMATH: A Scalable Instruction Tuning Dataset in Programmatic Mathematical Reasoning

# 摘要

> 近期，思维链 (CoT) 和思维程序 (PoT) 技术的进步大幅提升了语言模型的数学推理能力，并促进了与 LLM 的指令调优数据集的融合。但现有的大规模数据集创建方法依赖大量种子数据和高计算成本，限制了其扩展性。为此，我们推出了 InfinityMATH，一个专为程序化数学推理设计的可扩展指令调优数据集。该数据集通过解耦数字与数学问题，生成与数字无关的程序，实现了高效且灵活的扩展，同时减少了对特定数值的依赖。通过 Llama2 和 CodeLlama 等开源模型进行的微调实验表明，InfinityMATH 带来了显著的性能提升，平均改进幅度高达 184.7% 至 514.3%，并在 GSM8K+ 和 MATH+ 等增强测试集上展现了出色的鲁棒性。InfinityMATH 使模型在处理更广泛的数学问题时更加通用和高效。数据集已公开，可访问 https://huggingface.co/datasets/flagopen/InfinityMATH 获取。

> Recent advancements in Chain-of-Thoughts (CoT) and Program-of-Thoughts (PoT) methods have greatly enhanced language models' mathematical reasoning capabilities, facilitating their integration into instruction tuning datasets with LLMs. However, existing methods for large-scale dataset creation require substantial seed data and high computational costs for data synthesis, posing significant challenges for scalability. We introduce InfinityMATH, a scalable instruction tuning dataset for programmatic mathematical reasoning. The construction pipeline emphasizes decoupling numbers from mathematical problems to synthesize number-independent programs, enabling efficient and flexible scaling while minimizing dependency on specific numerical values. Fine-tuning experiments with open-source language and code models, such as Llama2 and CodeLlama, demonstrate the practical benefits of InfinityMATH. These fine-tuned models, showed significant relative improvements on both in-domain and out-of-domain benchmarks, ranging from 184.7% to 514.3% on average. Additionally, these models exhibited high robustness on the GSM8K+ and MATH+ benchmarks, which are enhanced version of test sets with simply the number variations. InfinityMATH ensures that models are more versatile and effective across a broader range of mathematical problems. The data is available at https://huggingface.co/datasets/flagopen/InfinityMATH.

[Arxiv](https://arxiv.org/abs/2408.07089)