# 代理链协作：大型语言模型共同应对长上下文任务挑战

发布时间：2024年06月04日

`Agent

这篇论文介绍了一种名为链式代理（CoA）的新框架，用于处理大型语言模型（LLMs）中的长上下文问题。该框架通过多代理协作实现信息聚合和推理，其中多个代理依次交流，处理文本片段，并由管理代理整合成连贯输出。这种方法通过交替阅读和推理，有效地处理了长上下文，并在多个任务中展示了性能提升。因此，这篇论文应归类为Agent，因为它主要讨论了通过代理系统来改进LLM的应用。` `人工智能`

> Chain of Agents: Large Language Models Collaborating on Long-Context Tasks

# 摘要

> 处理长上下文已成为大型语言模型（LLMs）的一大挑战。现有策略包括减少输入长度和扩展上下文窗口，但各有不足。为此，我们提出了一种名为链式代理（CoA）的新框架，它通过多代理协作，在长上下文任务中实现信息聚合和推理。CoA中的多个代理依次交流，处理文本片段，并由管理代理整合成连贯输出。通过交替阅读和推理，CoA有效处理长上下文，并在多个任务中展现出高达10%的性能提升，超越了现有强基线模型。

> Addressing the challenge of effectively processing long contexts has become a critical issue for Large Language Models (LLMs). Two common strategies have emerged: 1) reducing the input length, such as retrieving relevant chunks by Retrieval-Augmented Generation (RAG), and 2) expanding the context window limit of LLMs. However, both strategies have drawbacks: input reduction has no guarantee of covering the part with needed information, while window extension struggles with focusing on the pertinent information for solving the task. To mitigate these limitations, we propose Chain-of-Agents (CoA), a novel framework that harnesses multi-agent collaboration through natural language to enable information aggregation and context reasoning across various LLMs over long-context tasks. CoA consists of multiple worker agents who sequentially communicate to handle different segmented portions of the text, followed by a manager agent who synthesizes these contributions into a coherent final output. CoA processes the entire input by interleaving reading and reasoning, and it mitigates long context focus issues by assigning each agent a short context. We perform comprehensive evaluation of CoA on a wide range of long-context tasks in question answering, summarization, and code completion, demonstrating significant improvements by up to 10% over strong baselines of RAG, Full-Context, and multi-agent LLMs.

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/CoA.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/haiku.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/sonnet.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/opus.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/x1.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/lostinthemiddle.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/case_study.png)

![代理链协作：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/contextwindow.png)

[Arxiv](https://arxiv.org/abs/2406.02818)