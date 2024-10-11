# 借助检索增强的大型语言模型，优化高级综合设计。

发布时间：2024年10月09日

`RAG` `硬件设计` `人工智能`

> Optimizing High-Level Synthesis Designs with Retrieval-Augmented Large Language Models

# 摘要

> 高级综合 (HLS) 让硬件设计师能用 C/C++/OpenCL 等高级语言设计硬件，极大提升设计效率。但现有 HLS 流程依赖程序员的硬件知识和手动优化，优化过程繁琐且专业性强。自动化 HLS 代码优化迫在眉睫。最近，大型语言模型 (LLM) 在代码理解上表现出色，能直接处理特定领域问题，无需繁重微调。为此，我们提出一种基于检索增强的 LLM 方法，通过少样本学习，让 LLM 通过自然语言提示掌握领域知识。我们设计的 RALAD 框架，利用先进嵌入技术和 top-k 搜索算法，从大数据库中动态获取相关知识，为复杂编程问题提供精准解答。在两个专业领域测试中，RALAD 在编译任务中成功率达 80%，延迟改进优于一般 LLM 3.7 至 19 倍。

> High-level synthesis (HLS) allows hardware designers to create hardware designs with high-level programming languages like C/C++/OpenCL, which greatly improves hardware design productivity. However, existing HLS flows require programmers' hardware design expertise and rely on programmers' manual code transformations and directive annotations to guide compiler optimizations. Optimizing HLS designs requires non-trivial HLS expertise and tedious iterative process in HLS code optimization. Automating HLS code optimizations has become a burning need. Recently, large language models (LLMs) trained on massive code and programming tasks have demonstrated remarkable proficiency in comprehending code, showing the ability to handle domain-specific programming queries directly without labor-intensive fine-tuning. In this work, we propose a novel retrieval-augmented LLM-based approach to effectively optimize high-level synthesis (HLS) programs. Our proposed method leverages few-shot learning, enabling large language models to adopt domain-specific knowledge through natural language prompts. We propose a unique framework, Retrieve Augmented Large Language Model Aided Design (RALAD), designed to enhance LLMs' performance in HLS code optimization tasks. RALAD employs advanced embedding techniques and top-\emph{k} search algorithms to dynamically source relevant knowledge from extensive databases, thereby providing contextually appropriate responses to complex programming queries. Our implementation of RALAD on two specialized domains, utilizing comparatively smaller language models, achieves an impressive 80\% success rate in compilation tasks and outperforms general LLMs by 3.7 -- 19$\times$ in latency improvement.

[Arxiv](https://arxiv.org/abs/2410.07356)