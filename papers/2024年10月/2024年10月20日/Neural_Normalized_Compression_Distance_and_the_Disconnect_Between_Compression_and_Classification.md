# 神经归一化压缩距离揭示了压缩与分类之间的鸿沟

发布时间：2024年10月20日

`LLM理论` `信息论` `机器学习`

> Neural Normalized Compression Distance and the Disconnect Between Compression and Classification

# 摘要

> 预测分类与压缩在信息论中紧密相连，这一点广为人知。许多深度学习方法被视为一种压缩学习，更好的压缩意味着更优的性能。我们通过归一化压缩距离 (NCD) 来探究这一假设，NCD 利用压缩来衡量序列相似性，从而实现最近邻分类。我们将大型语言模型 (LLM) 转化为无损压缩器，开发了神经 NCD，并与 gzip 等经典算法进行对比。结果显示，分类准确性并非仅由压缩率决定，还存在其他未被当前理论预测到的现象。这表明，我们对神经网络“压缩”的本质及有效分类所需条件的理解尚不充分。

> It is generally well understood that predictive classification and compression are intrinsically related concepts in information theory. Indeed, many deep learning methods are explained as learning a kind of compression, and that better compression leads to better performance. We interrogate this hypothesis via the Normalized Compression Distance (NCD), which explicitly relies on compression as the means of measuring similarity between sequences and thus enables nearest-neighbor classification. By turning popular large language models (LLMs) into lossless compressors, we develop a Neural NCD and compare LLMs to classic general-purpose algorithms like gzip. In doing so, we find that classification accuracy is not predictable by compression rate alone, among other empirical aberrations not predicted by current understanding. Our results imply that our intuition on what it means for a neural network to ``compress'' and what is needed for effective classification are not yet well understood.

[Arxiv](https://arxiv.org/abs/2410.15280)