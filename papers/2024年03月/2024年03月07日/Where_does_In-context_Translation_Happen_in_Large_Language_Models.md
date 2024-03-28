# 在大型语言模型内部，上下文翻译究竟如何运作呢？

发布时间：2024年03月07日

`LLM理论`

> Where does In-context Translation Happen in Large Language Models

# 摘要

> 自我监督的大规模语言模型已证实能够运用上下文学习完成机器翻译任务，但对于模型如何依据提示指令和示例执行该任务的具体环节尚不清晰。本研究旨在探索并刻画大型语言模型从依赖上下文学习过渡至独立执行翻译任务的关键转折区域。通过对\textsc{GPTNeo2.7B}、\textsc{Bloom3B}、\textsc{Llama7b}及\textsc{Llama7b-chat}进行一系列逐层上下文遮蔽实验，我们揭示了模型在某一“任务识别”阶段会将翻译任务内化至输入特征表达，并自此阶段起不再需要持续关注上下文信息。此外，我们还注意到，当完全屏蔽某一层时性能显著降低的现象与识别翻译任务关键层有着紧密联系。借助这一内在冗余特性，在采用5个实例进行提示时，可节省高达45%的计算资源，并发现在第14/32层实现了任务识别功能。进一步的逐层微调实验证明，对机器翻译微调最为有效的层数恰恰就是那些对任务识别起到决定性作用的层次。

> Self-supervised large language models have demonstrated the ability to perform Machine Translation (MT) via in-context learning, but little is known about where the model performs the task with respect to prompt instructions and demonstration examples. In this work, we attempt to characterize the region where large language models transition from in-context learners to translation models. Through a series of layer-wise context-masking experiments on \textsc{GPTNeo2.7B}, \textsc{Bloom3B}, \textsc{Llama7b} and \textsc{Llama7b-chat}, we demonstrate evidence of a "task recognition" point where the translation task is encoded into the input representations and attention to context is no longer necessary. We further observe correspondence between the low performance when masking out entire layers, and the task recognition layers. Taking advantage of this redundancy results in 45\% computational savings when prompting with 5 examples, and task recognition achieved at layer 14 / 32. Our layer-wise fine-tuning experiments indicate that the most effective layers for MT fine-tuning are the layers critical to task recognition.

[Arxiv](https://arxiv.org/abs/2403.04510)