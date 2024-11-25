# CodeRosetta：推动并行编程中无监督代码翻译的边界

发布时间：2024年10月27日

`LLM应用` `语言翻译`

> CodeRosetta: Pushing the Boundaries of Unsupervised Code Translation for Parallel Programming

# 摘要

> 近期大型语言模型（LLMs）的进步，重新点燃了人们对自动编程语言翻译的热情。尤其是编码器 - 解码器转换器模型，在不同编程语言的互译中展现出潜力。然而，由于复杂的并行语义等难题，一种语言及其高性能计算（HPC）扩展之间的翻译探索尚不充分。本文中，我们推出了 CodeRosetta，这是专为编程语言及其 HPC 扩展间的翻译而设计的编码器 - 解码器转换器模型。CodeRosetta 在 C++ 到 CUDA 以及 Fortran 到 C++ 的翻译任务中接受了评估。它采用具有定制化预训练和训练目标的学习框架，能有效捕捉代码语义和并行结构的细微差异，实现双向翻译。结果显示，CodeRosetta 在 C++ 到 CUDA 的翻译中，比最先进的基线分别高出 2.9 BLEU 和 1.72 CodeBLEU 点，编译准确率提升 6.05%。和一般的闭源 LLMs 相比，我们的方法在 C++ 到 CUDA 的翻译中分别高出 22.08 BLEU 和 14.39 CodeBLEU，编译准确率提高 2.75%。最后，CodeRosetta 在 Fortran 到并行 C++ 的翻译上表现卓越，据我们所知，这是首个用于此复杂任务的编码器 - 解码器模型，与闭源和开源 LLMs 相比，CodeBLEU 至少提高 4.63 点。

> Recent advancements in Large Language Models (LLMs) have renewed interest in automatic programming language translation. Encoder-decoder transformer models, in particular, have shown promise in translating between different programming languages. However, translating between a language and its high-performance computing (HPC) extensions remains underexplored due to challenges such as complex parallel semantics. In this paper, we introduce CodeRosetta, an encoder-decoder transformer model designed specifically for translating between programming languages and their HPC extensions. CodeRosetta is evaluated on C++ to CUDA and Fortran to C++ translation tasks. It uses a customized learning framework with tailored pretraining and training objectives to effectively capture both code semantics and parallel structural nuances, enabling bidirectional translation. Our results show that CodeRosetta outperforms state-of-the-art baselines in C++ to CUDA translation by 2.9 BLEU and 1.72 CodeBLEU points while improving compilation accuracy by 6.05%. Compared to general closed-source LLMs, our method improves C++ to CUDA translation by 22.08 BLEU and 14.39 CodeBLEU, with 2.75% higher compilation accuracy. Finally, CodeRosetta exhibits proficiency in Fortran to parallel C++ translation, marking it, to our knowledge, as the first encoder-decoder model for this complex task, improving CodeBLEU by at least 4.63 points compared to closed-source and open-code LLMs.

[Arxiv](https://arxiv.org/abs/2410.20527)