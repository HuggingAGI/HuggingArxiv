# 大型语言模型中基于内存的难题

发布时间：2024年07月01日

`LLM应用` `人工智能` `软件开发`

> Needle in the Haystack for Memory Based Large Language Models

# 摘要

> 本文通过案例研究 LARIMAR，展示了增强记忆的 LLM 架构在提升长上下文事实回忆能力方面的优势。LARIMAR 通过外部关联记忆强化了 LLM 解码器，在多项长上下文回忆任务中表现出色，如密钥传递和海中捞针测试。实验表明，该架构能在测试时灵活适应更长上下文，同时确保解码器识别记忆输出，且不增加 GPU 内存负担。相较于参数相当的替代架构，LARIMAR 无需特定任务训练即可维持卓越性能。

> In this paper, we demonstrate the benefits of using memory augmented Large Language Model (LLM) architecture in improving the recall abilities of facts from a potentially long context. As a case study we test LARIMAR, a recently proposed LLM architecture which augments a LLM decoder with an external associative memory, on several long-context recall tasks, including passkey and needle-in-the-haystack tests. We demonstrate that the external memory can be adapted at test time to handle contexts much longer than those seen during training, while keeping readouts from the memory recognizable to the trained decoder and without increasing GPU memory footprint. Compared to alternative architectures for long-context recall tasks with models of a comparable parameter count, LARIMAR is able to maintain strong performance without any task-specific training.

[Arxiv](https://arxiv.org/abs/2407.01437)