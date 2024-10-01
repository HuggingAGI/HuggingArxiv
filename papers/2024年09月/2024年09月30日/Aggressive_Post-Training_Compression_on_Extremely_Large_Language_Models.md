# 对超大型语言模型进行激进的训练后压缩

发布时间：2024年09月30日

`LLM理论` `信息技术`

> Aggressive Post-Training Compression on Extremely Large Language Models

# 摘要

> 随着 LLM 的规模和复杂性不断增加，它们在个人电脑和移动设备上的部署面临挑战。为此，我们提出了一种创新的网络剪枝技术，利用高稀疏性和低量化位数，在几小时内压缩 LLM 并保持高准确性。实验证明，该方法高效且具有实际应用潜力。通过让 LLM 在本地设备上运行，我们的工作将开启自然语言处理应用的新纪元，带来广泛的影响。

> The increasing size and complexity of Large Language Models (LLMs) pose challenges for their deployment on personal computers and mobile devices. Aggressive post-training model compression is necessary to reduce the models' size, but it often results in significant accuracy loss. To address this challenge, we propose a novel network pruning technology that utilizes over 0.7 sparsity and less than 8 bits of quantization. Our approach enables the compression of prevailing LLMs within a couple of hours while maintaining a relatively small accuracy loss. In experimental evaluations, our method demonstrates effectiveness and potential for practical deployment. By making LLMs available on domestic devices, our work can facilitate a new era of natural language processing applications with wide-ranging impacts.

[Arxiv](https://arxiv.org/abs/2409.20094)