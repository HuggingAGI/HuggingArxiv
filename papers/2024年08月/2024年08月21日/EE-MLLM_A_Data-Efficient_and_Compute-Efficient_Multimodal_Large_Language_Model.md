# EE-MLLM：一款数据与计算双高效的多元大型语言模型

发布时间：2024年08月21日

`LLM应用` `计算机视觉`

> EE-MLLM: A Data-Efficient and Compute-Efficient Multimodal Large Language Model

# 摘要

> 在多模态研究中，众多研究通过利用大量图像-文本对，将大型语言模型（LLM）升级为多模态LLM，并在视觉-语言任务中大放异彩。目前，主流方法主要分为基于自注意力和基于交叉注意力的两大类。基于自注意力的方法因其简洁的MLP架构而数据效率高，但因将视觉和文本令牌串联输入LLM而计算效率较低。而基于交叉注意力的方法虽因额外参数而数据效率稍逊，却因避免长序列输入LLM而计算效率更高。为平衡这两者，我们推出了数据与计算双高效的多模态大型语言模型（EE-MLLM）。EE-MLLM在不增加新模块或参数的前提下，通过将MLLM中的自注意力机制改造为复合注意力机制，实现了双高效。这一新机制的关键在于：1）消除视觉令牌内自注意力的计算负担，提升计算效率；2）在LLM各层重用权重，促进视觉与语言间的模态对齐，增强数据效率。实验证明，EE-MLLM在MMBench、SeedBench等通用数据集及TextVQA、DocVQA等细粒度任务中均表现出色。

> In the realm of multimodal research, numerous studies leverage substantial image-text pairs to conduct modal alignment learning, transforming Large Language Models (LLMs) into Multimodal LLMs and excelling in a variety of visual-language tasks. The prevailing methodologies primarily fall into two categories: self-attention-based and cross-attention-based methods. While self-attention-based methods offer superior data efficiency due to their simple MLP architecture, they often suffer from lower computational efficiency due to concatenating visual and textual tokens as input for LLM. Conversely, cross-attention-based methods, although less data-efficient due to additional learnable parameters, exhibit higher computational efficiency by avoiding long sequence input for LLM. To address these trade-offs, we introduce the Data-Efficient and Compute-Efficient Multimodal Large Language Model (EE-MLLM). Without introducing additional modules or learnable parameters, EE-MLLM achieves both data and compute efficiency. Specifically, we modify the original self-attention mechanism in MLLM to a composite attention mechanism. This mechanism has two key characteristics: 1) Eliminating the computational overhead of self-attention within visual tokens to achieve compute efficiency, and 2) Reusing the weights on each layer of LLM to facilitate effective modality alignment between vision and language for data efficiency. Experimental results demonstrate the effectiveness of EE-MLLM across a range of benchmarks, including general-purpose datasets like MMBench and SeedBench, as well as fine-grained tasks such as TextVQA and DocVQA.

[Arxiv](https://arxiv.org/abs/2408.11795)