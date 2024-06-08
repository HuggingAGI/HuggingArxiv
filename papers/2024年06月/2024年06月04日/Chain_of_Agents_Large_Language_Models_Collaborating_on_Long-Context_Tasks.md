# 协作代理链：大型语言模型共同应对长上下文任务挑战

发布时间：2024年06月04日

`Agent

这篇论文介绍了一种名为Chain-of-Agents（CoA）的新框架，用于处理大型语言模型（LLMs）在长上下文任务中的挑战。CoA通过利用多个代理之间的协作来整合信息并进行上下文推理，有效解决了长上下文关注问题。这种方法涉及多个工作代理之间的交互，以及一个管理代理来整合信息。论文通过在问答、摘要和代码完成等任务上的评估，展示了CoA相比其他方法的性能提升。因此，这篇论文更符合Agent分类，因为它主要关注的是通过代理系统来优化LLM的应用。` `问答系统`

> Chain of Agents: Large Language Models Collaborating on Long-Context Tasks

# 摘要

> 处理长上下文已成为大型语言模型（LLMs）面临的一大挑战。目前，两种主要策略被采用：一是通过检索增强生成（RAG）等方式减少输入长度；二是扩大LLMs的上下文窗口。但这两种方法各有弊端：前者无法确保包含关键信息，后者则在聚焦任务相关信息上显得力不从心。为此，我们提出了Chain-of-Agents（CoA）框架，它利用自然语言实现多代理间的协作，以在长上下文任务中整合信息并进行上下文推理。CoA包含多个工作代理，它们依次交流以处理文本的不同部分，并由一个管理代理将这些信息整合成连贯的输出。通过交替阅读与推理，CoA有效处理了整个输入，并通过为每个代理分配短上下文来解决长上下文关注问题。在问答、摘要和代码完成等长上下文任务上的广泛评估显示，CoA相比RAG、全上下文和多代理LLMs等强基线，性能提升了高达10%。

> Addressing the challenge of effectively processing long contexts has become a critical issue for Large Language Models (LLMs). Two common strategies have emerged: 1) reducing the input length, such as retrieving relevant chunks by Retrieval-Augmented Generation (RAG), and 2) expanding the context window limit of LLMs. However, both strategies have drawbacks: input reduction has no guarantee of covering the part with needed information, while window extension struggles with focusing on the pertinent information for solving the task. To mitigate these limitations, we propose Chain-of-Agents (CoA), a novel framework that harnesses multi-agent collaboration through natural language to enable information aggregation and context reasoning across various LLMs over long-context tasks. CoA consists of multiple worker agents who sequentially communicate to handle different segmented portions of the text, followed by a manager agent who synthesizes these contributions into a coherent final output. CoA processes the entire input by interleaving reading and reasoning, and it mitigates long context focus issues by assigning each agent a short context. We perform comprehensive evaluation of CoA on a wide range of long-context tasks in question answering, summarization, and code completion, demonstrating significant improvements by up to 10% over strong baselines of RAG, Full-Context, and multi-agent LLMs.

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/CoA.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/haiku.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/sonnet.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/opus.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/x1.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/lostinthemiddle.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/case_study.png)

![协作代理链：大型语言模型共同应对长上下文任务挑战](../../../paper_images/2406.02818/contextwindow.png)

[Arxiv](https://arxiv.org/abs/2406.02818)