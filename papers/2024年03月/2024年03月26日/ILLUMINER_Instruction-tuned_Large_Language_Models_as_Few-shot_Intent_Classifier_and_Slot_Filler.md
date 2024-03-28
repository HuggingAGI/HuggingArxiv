# ILLUMINER：指令调优的大型语言模型，用作少样本意图识别和槽位填充工具

发布时间：2024年03月26日

`LLM应用` `工业应用`

> ILLUMINER: Instruction-tuned Large Language Models as Few-shot Intent Classifier and Slot Filler

# 摘要

> 当下先进的意图识别和槽位填充技术多依赖于大数据支撑的深度学习模型，这在实际工业应用中受到限制。而大型语言模型，尤其是经过指令优化的模型（Instruct-LLMs），在众多自然语言处理任务中展现出了出色的零样本学习能力。本项研究对Instruct-LLMs在标准意图分类和槽位填充数据集上的表现进行了评估，特别关注其在少量样本学习上的能力。我们提出了ILLUMINER方法，将意图识别和槽位填充任务重新定义为Instruct-LLMs的语言生成问题，并引入了一种相比以往更高效的槽位填充提示技术。通过与多个基准模型的全面对比，我们发现使用FLAN-T5 11B模型的ILLUMINER方法在性能上超越了目前最先进的联合意图识别和槽位填充技术，以及GPT3.5（175B）的上下文学习技术，特别是在槽位填充任务上，性能提升幅度达到11.1至32.2个百分点。此外，我们通过深入的消融实验发现，参数更高效的微调方法仅需不到6%的训练数据，就能达到与传统全参数微调相当的性能水平。

> State-of-the-art intent classification (IC) and slot filling (SF) methods often rely on data-intensive deep learning models, limiting their practicality for industry applications. Large language models on the other hand, particularly instruction-tuned models (Instruct-LLMs), exhibit remarkable zero-shot performance across various natural language tasks. This study evaluates Instruct-LLMs on popular benchmark datasets for IC and SF, emphasizing their capacity to learn from fewer examples. We introduce ILLUMINER, an approach framing IC and SF as language generation tasks for Instruct-LLMs, with a more efficient SF-prompting method compared to prior work. A comprehensive comparison with multiple baselines shows that our approach, using the FLAN-T5 11B model, outperforms the state-of-the-art joint IC+SF method and in-context learning with GPT3.5 (175B), particularly in slot filling by 11.1--32.2 percentage points. Additionally, our in-depth ablation study demonstrates that parameter-efficient fine-tuning requires less than 6% of training data to yield comparable performance with traditional full-weight fine-tuning.

[Arxiv](https://arxiv.org/abs/2403.17536)