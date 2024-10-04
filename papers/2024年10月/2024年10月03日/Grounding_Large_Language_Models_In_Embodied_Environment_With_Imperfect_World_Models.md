# 将大型语言模型嵌入具身环境，面对不完美的世界模型

发布时间：2024年10月03日

`Agent` `机器人` `人工智能`

> Grounding Large Language Models In Embodied Environment With Imperfect World Models

# 摘要

> 尽管 LLMs 在众多应用中表现出色，但在处理物理推理或机器人任务时，由于缺乏现实世界的直接经验，常常力不从心。为此，我们推出了 GLIMO，通过模拟器等代理世界模型收集和合成训练数据，弥补这一短板。GLIMO 内置 LLM 代理数据生成器，自动产出高质量、多样化的指令数据集。生成器配备迭代自精炼模块，确保时间一致性经验采样，并集成多样化问答指令种子和检索增强生成模块，助力模型反思过往经验。实验结果显示，GLIMO 显著提升了 LLaMA-3 等开源 LLMs 的性能，在三大基准测试中分别提升 2.04 倍、1.54 倍和 1.82 倍，甚至能与 GPT-4 一较高下。

> Despite a widespread success in various applications, large language models (LLMs) often stumble when tackling basic physical reasoning or executing robotics tasks, due to a lack of direct experience with the physical nuances of the real world. To address these issues, we propose a Grounding Large language model with Imperfect world MOdel (GLIMO), which utilizes proxy world models such as simulators to collect and synthesize trining data. GLIMO incorporates an LLM agent-based data generator to automatically create high-quality and diverse instruction datasets. The generator includes an iterative self-refining module for temporally consistent experience sampling, a diverse set of question-answering instruction seeds, and a retrieval-augmented generation module for reflecting on prior experiences. Comprehensive experiments show that our approach improve the performance of strong open-source LLMs like LLaMA-3 with a performance boost of 2.04 $\times$, 1.54 $\times$, and 1.82 $\times$ across three different benchmarks, respectively. The performance is able to compete with or surpass their larger counterparts such as GPT-4.

[Arxiv](https://arxiv.org/abs/2410.02742)