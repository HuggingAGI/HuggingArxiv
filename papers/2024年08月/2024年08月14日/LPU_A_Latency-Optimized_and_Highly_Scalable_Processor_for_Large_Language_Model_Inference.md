# LPU：专为大型语言模型推理设计，实现低延迟与高可扩展性的处理器

发布时间：2024年08月14日

`LLM应用` `半导体` `信息技术`

> LPU: A Latency-Optimized and Highly Scalable Processor for Large Language Model Inference

# 摘要

> OpenAI的ChatGPT的迅猛发展加速了大型语言模型（LLM）的全球化进程，这些模型集成了数十亿预训练参数，涵盖了句法和语义的精髓。HyperAccel推出的延迟处理单元（LPU），专为LLM推理加速设计，具备高度优化和可扩展的处理器架构。LPU通过精简数据流，巧妙平衡了内存带宽与计算逻辑，从而提升了性能与效率。此外，LPU搭载的可扩展同步链路（ESL）有效减少了多LPU间的数据同步延迟。HyperDex软件框架与LPU相辅相成，为LLM应用提供了直观运行环境。在1.3B和66B模型上，LPU分别实现了1.25 ms/token和20.9 ms/token的惊人速度，较GPU分别快2.09倍和1.37倍。采用三星4nm工艺的LPU，面积仅为0.824 mm2，功耗低至284.31 mW。基于LPU的服务器在能效方面，分别比NVIDIA H100和L4服务器高出1.33倍和1.32倍。

> The explosive arrival of OpenAI's ChatGPT has fueled the globalization of large language model (LLM), which consists of billions of pretrained parameters that embodies the aspects of syntax and semantics. HyperAccel introduces latency processing unit (LPU), a latency-optimized and highly scalable processor architecture for the acceleration of LLM inference. LPU perfectly balances the memory bandwidth and compute logic with streamlined dataflow to maximize performance and efficiency. LPU is equipped with expandable synchronization link (ESL) that hides data synchronization latency between multiple LPUs. HyperDex complements LPU as an intuitive software framework to run LLM applications. LPU achieves 1.25 ms/token and 20.9 ms/token for 1.3B and 66B model, respectively, which is 2.09x and 1.37x faster than the GPU. LPU, synthesized using Samsung 4nm process, has total area of 0.824 mm2 and power consumption of 284.31 mW. LPU-based servers achieve 1.33x and 1.32x energy efficiency over NVIDIA H100 and L4 servers, respectively.

[Arxiv](https://arxiv.org/abs/2408.07326)