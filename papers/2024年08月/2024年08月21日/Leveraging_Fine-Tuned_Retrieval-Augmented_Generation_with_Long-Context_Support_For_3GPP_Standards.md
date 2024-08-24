# 结合微调与检索增强技术，提供长上下文支持，专为3GPP标准定制。

发布时间：2024年08月21日

`RAG` `通信网络`

> Leveraging Fine-Tuned Retrieval-Augmented Generation with Long-Context Support: For 3GPP Standards

# 摘要

> 最新研究发现，大型语言模型在处理电信技术标准时面临挑战。为此，我们基于Phi-2小型语言模型开发了一种微调的检索增强生成系统，旨在优化通信网络性能。该系统通过前瞻性语义分块技术，智能识别文档格式并自适应确定解析断点。针对技术标准中相似上下文众多的问题，我们引入了重新排序算法，确保最相关信息优先处理。考虑到Phi-2上下文窗口较小的限制，我们采用了SelfExtend技术，在推理时扩展窗口，提升性能并增强系统对多样化查询的适应性。微调过程中，我们运用低秩适应技术，提高训练效率，使系统能在小数据集上有效微调。实验结果显示，我们的方法在电信领域的问答任务中显著优于现有技术，甚至超越了规模庞大的GPT-4模型。这项研究为利用小型语言模型提升通信网络效率与性能开辟了新途径，为构建网络智能语言模型奠定了基础。

> Recent studies show that large language models (LLMs) struggle with technical standards in telecommunications. We propose a fine-tuned retrieval-augmented generation (RAG) system based on the Phi-2 small language model (SLM) to serve as an oracle for communication networks. Our developed system leverages forward-looking semantic chunking to adaptively determine parsing breakpoints based on embedding similarity, enabling effective processing of diverse document formats. To handle the challenge of multiple similar contexts in technical standards, we employ a re-ranking algorithm to prioritize the most relevant retrieved chunks. Recognizing the limitations of Phi-2's small context window, we implement a recent technique, namely SelfExtend, to expand the context window during inference, which not only boosts the performance but also can accommodate a wider range of user queries and design requirements from customers to specialized technicians. For fine-tuning, we utilize the low-rank adaptation (LoRA) technique to enhance computational efficiency during training and enable effective fine-tuning on small datasets. Our comprehensive experiments demonstrate substantial improvements over existing question-answering approaches in the telecom domain, achieving performance that exceeds larger language models such as GPT-4 (which is about 880 times larger in size). This work presents a novel approach to leveraging SLMs for communication networks, offering a balance of efficiency and performance. This work can serve as a foundation towards agentic language models for networks.

[Arxiv](https://arxiv.org/abs/2408.11775)