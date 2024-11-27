# 针对在单个中等 GPU 系统上高效推理大型语言模型的任务调度

发布时间：2024年11月23日

`LLM应用` `计算机` `推理引擎`

> Task Scheduling for Efficient Inference of Large Language Models on Single Moderate GPU Systems

# 摘要

> 大型语言模型（LLMs）因其规模庞大，对计算资源和内存的需求极高，致使在中等 GPU 系统上推理效率欠佳。诸如量化或剪枝之类的技术虽能缩小模型规模，却常常降低准确性，难以在实际应用中适用。在此项工作中，我们推出了\modelname{}，这是一款高性能的推理引擎，旨在加速 LLM 推理且不损模型精度。\modelname{} 融合了三项创新之法来提升推理效率：其一，模型分区，能让任务在 CPU 计算、GPU 计算以及 CPU - GPU 通信之间异步处理；其二，自适应分区算法，用于优化 CPU、GPU 以及 PCIe 通信能力的运用；其三，令牌分配策略，用于应对 LLM 推理过程中的各类提示和生成任务。在三个配备不同 CPU 和 GPU 的测试环境中，针对 Mixtral、LLaMA - 2、Qwen 和 PhiMoE 等多种 LLM 展开了全面实验。实验结果显示，相较于 llama.cpp 和 Fiddler 等前沿解决方案，\modelname{} 在解码环节实现了 1.11 倍至 1.80 倍的提速，在预填充方面达到了 1.69 倍至 6.33 倍的加速，整体加速幅度在 1.25 倍至 2.04 倍之间。

> Large language models~(LLMs) are known for their high demand on computing resources and memory due to their substantial model size, which leads to inefficient inference on moderate GPU systems. Techniques like quantization or pruning can shrink model sizes but often impair accuracy, making them unsuitable for practical applications. In this work, we introduce \modelname{}, a high-performance inference engine designed to speed up LLM inference without compromising model accuracy. \modelname{} incorporates three innovative methods to increase inference efficiency: 1) model partitioning to allow asynchronous processing of tasks across CPU computation, GPU computation, and CPU-GPU communication, 2) an adaptive partition algorithm to optimize the use of CPU, GPU, and PCIe communication capabilities, and 3) a token assignment strategy to handle diverse prompt and generation tasks during LLM inference. Comprehensive experiments were conducted with various LLMs such as Mixtral, LLaMA-2, Qwen, and PhiMoE across three test environments featuring different CPUs and GPUs. The experimental findings demonstrate that \modelname{} achieves speeds between $1.11\times$ to $1.80\times$ faster in decoding and $1.69\times$ to $6.33\times$ faster in pre-filling, leading to an overall speedup ranging from $1.25\times$ to $2.04\times$ compared to state-of-the-art solutions, llama.cpp and Fiddler.

[Arxiv](https://arxiv.org/abs/2411.15715)