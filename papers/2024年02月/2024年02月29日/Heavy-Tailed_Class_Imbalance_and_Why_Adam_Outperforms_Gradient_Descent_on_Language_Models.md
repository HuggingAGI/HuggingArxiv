# [在语言模型训练中，Adam 优化器相较于梯度下降法展现出更优性能，这一现象与重尾类别不平衡问题密切相关。本研究探讨了这一特性背后的原因，并揭示了 Adam 如何更好地应对重尾类别不平衡对语言模型训练的影响。]

发布时间：2024年02月29日

`LLM理论`

> Heavy-Tailed Class Imbalance and Why Adam Outperforms Gradient Descent on Language Models

> 研究表明，Adam 在优化大型语言转换器时明显胜过梯度下降，尤其是在处理不均衡的词汇频率分布时优势更加突出，然而其中原因尚未明晰。实际上，语言建模任务中存在的严重类别不平衡问题对优化过程产生了挑战，梯度下降时，低频词的损失下降速度往往滞后于高频词。鉴于大部分样本来源于低频词，所以采用梯度下降时，整体平均损失的下降速率较慢。而 Adam 以及基于符号的方法则成功规避了这一难题，对所有类别都实现了预测性能的提升。为了确证类别不平衡是造成这一现象的关键因素，我们不仅在语言转换器领域，还涵盖了视觉CNNs和线性模型等多种模型结构与数据类型，验证了这一现象的普遍存在。此外，通过在交叉熵损失的线性分类问题上深入探究，我们揭示了重尾类别不平衡会引发病态条件，而 Adam 所采用的归一化手段能够有效抵消这一不利影响。

> Adam has been shown to outperform gradient descent in optimizing large language transformers empirically, and by a larger margin than on other tasks, but it is unclear why this happens. We show that the heavy-tailed class imbalance found in language modeling tasks leads to difficulties in the optimization dynamics. When training with gradient descent, the loss associated with infrequent words decreases slower than the loss associated with frequent ones. As most samples come from relatively infrequent words, the average loss decreases slowly with gradient descent. On the other hand, Adam and sign-based methods do not suffer from this problem and improve predictions on all classes. To establish that this behavior is indeed caused by class imbalance, we show empirically that it persist through different architectures and data types, on language transformers, vision CNNs, and linear models. We further study this phenomenon on a linear classification with cross-entropy loss, showing that heavy-tailed class imbalance leads to ill-conditioning, and that the normalization used by Adam can counteract it.

[Arxiv](https://arxiv.org/abs/2402.19449)