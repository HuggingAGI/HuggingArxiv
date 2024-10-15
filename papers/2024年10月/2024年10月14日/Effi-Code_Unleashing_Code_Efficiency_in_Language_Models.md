# Effi-Code：激发语言模型中的代码效率

发布时间：2024年10月14日

`LLM应用` `软件开发` `人工智能`

> Effi-Code: Unleashing Code Efficiency in Language Models

# 摘要

> 随着 LLM 在软件开发中用于代码生成的普及，提升生成代码的效率和正确性变得尤为重要。现有方法多关注代码的正确性，而忽视了效率。为此，我们推出了 Effi-Code，一种能同时提升代码效率和正确性的方法。通过基于开销分析的自优化过程，我们利用开源 LLM 生成高质量的代码样本数据集，并用于微调各种 LLM。我们的方法通过迭代优化，结合运行时性能指标和正确性检查，显著提升了代码的正确性和效率。例如，DeepSeek-Coder-6.7B-Instruct 的 pass@1 从 43.3% 提升至 76.8%，执行时间减少了 30.5%。Effi-Code 不仅可扩展且通用，还具备在软件开发、算法设计和计算问题解决中的广泛应用潜力。源代码已发布在 https://github.com/huangd1999/Effi-Code。

> As the use of large language models (LLMs) for code generation becomes more prevalent in software development, it is critical to enhance both the efficiency and correctness of the generated code. Existing methods and models primarily focus on the correctness of LLM-generated code, ignoring efficiency. In this work, we present Effi-Code, an approach to enhancing code generation in LLMs that can improve both efficiency and correctness. We introduce a Self-Optimization process based on Overhead Profiling that leverages open-source LLMs to generate a high-quality dataset of correct and efficient code samples. This dataset is then used to fine-tune various LLMs. Our method involves the iterative refinement of generated code, guided by runtime performance metrics and correctness checks. Extensive experiments demonstrate that models fine-tuned on the Effi-Code show significant improvements in both code correctness and efficiency across task types. For example, the pass@1 of DeepSeek-Coder-6.7B-Instruct generated code increases from \textbf{43.3\%} to \textbf{76.8\%}, and the average execution time for the same correct tasks decreases by \textbf{30.5\%}. Effi-Code offers a scalable and generalizable approach to improving code generation in AI systems, with potential applications in software development, algorithm design, and computational problem-solving. The source code of Effi-Code was released in \url{https://github.com/huangd1999/Effi-Code}.

[Arxiv](https://arxiv.org/abs/2410.10209)