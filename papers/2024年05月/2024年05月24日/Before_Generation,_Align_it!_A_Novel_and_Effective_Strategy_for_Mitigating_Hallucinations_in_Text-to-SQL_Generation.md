# 生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。

发布时间：2024年05月24日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）在文本到SQL任务中的应用，特别是在减少幻觉和提高模型性能方面的策略和框架（TA-SQL）。论文通过识别和分类幻觉类型，并提出任务对齐策略来改进模型性能，这些都是针对特定应用场景的优化措施。因此，这篇论文更适合归类于“LLM应用”类别，而不是“Agent”、“RAG”或“LLM理论”。` `数据库`

> Before Generation, Align it! A Novel and Effective Strategy for Mitigating Hallucinations in Text-to-SQL Generation

# 摘要

> ICL驱动的大型语言模型在文本到SQL任务中表现出色，但LLMs的泛化缺陷常导致幻觉，限制了其潜力。我们首先识别并分类了文本到SQL各阶段常见的幻觉类型，并提出了任务对齐策略 (TA)，旨在减少幻觉。TA让LLMs借鉴类似任务经验，而非从头开始，有效减轻了幻觉。基于此，我们开发了TA-SQL框架，实验证明其有效且稳健，显著提升了GPT-4在BIRD dev上的性能，并在多个复杂基准测试中取得了显著进步。

> Large Language Models (LLMs) driven by In-Context Learning (ICL) have significantly improved the performance of text-to-SQL. Previous methods generally employ a two-stage reasoning framework, namely 1) schema linking and 2) logical synthesis, making the framework not only effective but also interpretable. Despite these advancements, the inherent bad nature of the generalization of LLMs often results in hallucinations, which limits the full potential of LLMs. In this work, we first identify and categorize the common types of hallucinations at each stage in text-to-SQL. We then introduce a novel strategy, Task Alignment (TA), designed to mitigate hallucinations at each stage. TA encourages LLMs to take advantage of experiences from similar tasks rather than starting the tasks from scratch. This can help LLMs reduce the burden of generalization, thereby mitigating hallucinations effectively. We further propose TA-SQL, a text-to-SQL framework based on this strategy. The experimental results and comprehensive analysis demonstrate the effectiveness and robustness of our framework. Specifically, it enhances the performance of the GPT-4 baseline by 21.23% relatively on BIRD dev and it yields significant improvements across six models and four mainstream, complex text-to-SQL benchmarks.

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x1.png)

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x2.png)

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x3.png)

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x4.png)

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x5.png)

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x6.png)

![生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。](../../../paper_images/2405.15307/x7.png)

[Arxiv](https://arxiv.org/abs/2405.15307)