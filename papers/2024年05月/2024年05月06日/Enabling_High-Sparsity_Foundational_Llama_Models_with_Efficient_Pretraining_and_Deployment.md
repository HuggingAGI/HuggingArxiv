# 通过高效的预训练和部署策略，成功打造了高稀疏性基础的羊驼模型。

发布时间：2024年05月06日

`分类：LLM应用` `计算优化`

> Enabling High-Sparsity Foundational Llama Models with Efficient Pretraining and Deployment

# 摘要

> 大型语言模型（LLMs）引领了自然语言处理（NLP）的新纪元，但其庞大的体量也带来了计算上的瓶颈。我们提出了一种创新的方法，能够构建既精确又稀疏的基础版高效LLMs，这些模型即便在70%的稀疏度下，也能在微调任务中完全恢复准确度。这一成就是通过结合SparseGPT一次性修剪技术和对SlimPajama数据集部分内容以及The Stack数据集中的Python数据子集进行稀疏预训练，在我们LLaMA-2 7B模型上实现的。我们在Cerebras CS-3芯片上的实验显示，由于稀疏性，训练速度显著提升，与理论预测的扩展性高度一致。此外，我们还通过Neural Magic的DeepSparse引擎在CPU上实现了最高达3倍的推理加速，以及通过Neural Magic的nm-vllm引擎在GPU上实现了1.7倍的加速。这些提升仅依靠稀疏化技术实现，为未来通过量化技术进一步提升性能留出了空间。具体而言，我们在CPU上对稀疏-量化的LLaMA模型实现了最高8.6倍的总加速。我们通过在包括聊天、指令执行、代码生成、算术推理和摘要等多样化且具有挑战性的任务上展示这些成果，证明了其广泛的适用性。本研究为打造更小巧、更迅捷且不失精准度的LLMs开辟了新径。

> Large language models (LLMs) have revolutionized Natural Language Processing (NLP), but their size creates computational bottlenecks. We introduce a novel approach to create accurate, sparse foundational versions of performant LLMs that achieve full accuracy recovery for fine-tuning tasks at up to 70% sparsity. We achieve this for the LLaMA-2 7B model by combining the SparseGPT one-shot pruning method and sparse pretraining of those models on a subset of the SlimPajama dataset mixed with a Python subset of The Stack dataset. We exhibit training acceleration due to sparsity on Cerebras CS-3 chips that closely matches theoretical scaling. In addition, we establish inference acceleration of up to 3x on CPUs by utilizing Neural Magic's DeepSparse engine and 1.7x on GPUs through Neural Magic's nm-vllm engine. The above gains are realized via sparsity alone, thus enabling further gains through additional use of quantization. Specifically, we show a total speedup on CPUs for sparse-quantized LLaMA models of up to 8.6x. We demonstrate these results across diverse, challenging tasks, including chat, instruction following, code generation, arithmetic reasoning, and summarization to prove their generality. This work paves the way for rapidly creating smaller and faster LLMs without sacrificing accuracy.

[Arxiv](https://arxiv.org/abs/2405.03594)