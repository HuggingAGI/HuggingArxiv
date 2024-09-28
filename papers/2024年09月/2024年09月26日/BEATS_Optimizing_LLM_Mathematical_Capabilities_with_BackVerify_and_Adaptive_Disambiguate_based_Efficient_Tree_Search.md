# BEATS：利用 BackVerify 和 Adaptive Disambiguate 的高效树搜索，提升 LLM 的数学能力

发布时间：2024年09月26日

`LLM应用` `人工智能`

> BEATS: Optimizing LLM Mathematical Capabilities with BackVerify and Adaptive Disambiguate based Efficient Tree Search

# 摘要

> 尽管大型语言模型 (LLM) 在众多任务中表现出色，但在解决数学问题时仍显不足，这主要归因于数学的严谨逻辑性。以往的研究尝试通过监督微调、提示工程和搜索方法来提升其数学能力，但效果有限且耗费大量计算资源。为此，我们创新性地提出了 BEATS 方法，通过设计新型提示，引导模型逐步推理并生成答案，同时引入后验证技术确保答案的准确性。此外，剪枝树搜索的运用进一步优化了搜索效率。实验结果显示，BEATS 将 Qwen2-7b-Instruct 的分数从 36.94 提升至 61.52，显著超越了 GPT4 在 MATH 基准上的表现。

> Large Language Models (LLMs) have exhibited exceptional performance across a broad range of tasks and domains. However, they still encounter difficulties in solving mathematical problems due to the rigorous and logical nature of mathematics. Previous studies have employed techniques such as supervised fine-tuning (SFT), prompt engineering, and search-based methods to improve the mathematical problem-solving abilities of LLMs. Despite these efforts, their performance remains suboptimal and demands substantial computational resources. To address this issue, we propose a novel approach, BEATS, to enhance mathematical problem-solving abilities. Our method leverages newly designed prompts that guide the model to iteratively rewrite, advance by one step, and generate answers based on previous steps. Additionally, we introduce a new back-verification technique that uses LLMs to validate the correctness of the generated answers. Furthermore, we employ a pruning tree search to optimize search time while achieving strong performance. Notably, our method improves Qwen2-7b-Instruct's score from 36.94 to 61.52, outperforming GPT4's 42.5 on the MATH benchmark.

[Arxiv](https://arxiv.org/abs/2409.17972)