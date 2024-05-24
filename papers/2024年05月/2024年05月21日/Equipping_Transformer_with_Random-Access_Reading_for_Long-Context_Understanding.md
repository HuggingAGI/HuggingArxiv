# 赋予Transformer随机访问阅读能力，深化长上下文理解

发布时间：2024年05月21日

`Agent

理由：这篇论文探讨了如何改进大型语言模型（LLMs）处理长文档的能力，特别是通过引入一种名为“随机访问”的新策略，该策略允许模型跳过不相关的标记，类似于人类阅读习惯。这种策略涉及到模型的训练和微调，以实现更高效的长文档处理。这表明论文关注的是如何使模型更像一个智能代理，能够自主地、有目的地处理信息，而不是仅仅关注理论层面的模型构建或应用层面的具体应用。因此，它更适合归类为Agent，即关注模型作为智能代理的行为和能力。` `文档处理`

> Equipping Transformer with Random-Access Reading for Long-Context Understanding

# 摘要

> 基于Transformer的大型语言模型（LLMs）在处理长上下文时面临挑战，主要因为自注意力机制的二次复杂性和预训练时仅使用短输入导致的长度扩展问题。现有技术如文本分块、核方法和结构化注意力旨在降低计算复杂性，而位置编码、持续预训练和数据工程则用于解决长度扩展问题。这些方法通常要求**顺序访问**文档，从首至尾逐一阅读。我们认为，对于目标导向的长文档阅读，无需这种顺序访问，一个训练有素的模型应能跳过不相关的数百个标记。借鉴人类阅读习惯和现有研究，我们提出了一种名为**随机访问**的新策略，允许Transformer高效处理长文档，无需逐一检查每个标记。预训练、微调和推理的实验结果均证实了这一策略的有效性。

> Long-context modeling presents a significant challenge for transformer-based large language models (LLMs) due to the quadratic complexity of the self-attention mechanism and issues with length extrapolation caused by pretraining exclusively on short inputs. Existing methods address computational complexity through techniques such as text chunking, the kernel approach, and structured attention, and tackle length extrapolation problems through positional encoding, continued pretraining, and data engineering. These approaches typically require $\textbf{sequential access}$ to the document, necessitating reading from the first to the last token. We contend that for goal-oriented reading of long documents, such sequential access is not necessary, and a proficiently trained model can learn to omit hundreds of less pertinent tokens. Inspired by human reading behaviors and existing empirical observations, we propose $\textbf{random access}$, a novel reading strategy that enables transformers to efficiently process long documents without examining every token. Experimental results from pretraining, fine-tuning, and inference phases validate the efficacy of our method.

[Arxiv](https://arxiv.org/abs/2405.13216)