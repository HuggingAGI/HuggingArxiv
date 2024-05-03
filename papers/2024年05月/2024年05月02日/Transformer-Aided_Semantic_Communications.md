# 借助Transformer的语义通信技术

发布时间：2024年05月02日

`LLM应用` `图像处理`

> Transformer-Aided Semantic Communications

# 摘要

> 大型语言模型（LLMs）中的变换器结构，作为深度神经网络（DNNs）的一个特殊类别，以其识别和强调输入数据中最重要方面的能力而著称。这一特性在多种通信挑战中尤为有用，尤其是在语义通信领域，恰当地编码相关数据对于带宽受限的系统至关重要。本研究中，我们专门采用视觉变换器对输入图像进行压缩和紧凑表示，以在传输过程中保持语义信息。利用变换器内在的注意力机制，我们生成了一个注意力掩码，该掩码有效优先传输图像的关键部分，确保重建阶段集中于掩码标记的关键对象。我们的技术显著提升了语义通信质量，并优化了带宽使用效率，通过根据数据的语义信息含量对数据的不同部分进行编码。通过TinyImageNet数据集的测试，我们专注于重建质量和准确性的评估，结果证明我们的框架即便在仅传输部分编码数据的情况下，也能成功保持语义信息，达到预期的压缩比率。

> The transformer structure employed in large language models (LLMs), as a specialized category of deep neural networks (DNNs) featuring attention mechanisms, stands out for their ability to identify and highlight the most relevant aspects of input data. Such a capability is particularly beneficial in addressing a variety of communication challenges, notably in the realm of semantic communication where proper encoding of the relevant data is critical especially in systems with limited bandwidth. In this work, we employ vision transformers specifically for the purpose of compression and compact representation of the input image, with the goal of preserving semantic information throughout the transmission process. Through the use of the attention mechanism inherent in transformers, we create an attention mask. This mask effectively prioritizes critical segments of images for transmission, ensuring that the reconstruction phase focuses on key objects highlighted by the mask. Our methodology significantly improves the quality of semantic communication and optimizes bandwidth usage by encoding different parts of the data in accordance with their semantic information content, thus enhancing overall efficiency. We evaluate the effectiveness of our proposed framework using the TinyImageNet dataset, focusing on both reconstruction quality and accuracy. Our evaluation results demonstrate that our framework successfully preserves semantic information, even when only a fraction of the encoded data is transmitted, according to the intended compression rates.

[Arxiv](https://arxiv.org/abs/2405.01521)