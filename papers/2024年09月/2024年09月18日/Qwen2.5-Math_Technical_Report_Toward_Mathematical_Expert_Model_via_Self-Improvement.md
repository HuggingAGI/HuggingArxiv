# Qwen2.5-Math 技术报告：借助自我提升，打造数学专家模型

发布时间：2024年09月18日

`LLM应用`

> Qwen2.5-Math Technical Report: Toward Mathematical Expert Model via Self-Improvement

# 摘要

> 本报告介绍了一系列专为数学设计的大型语言模型：Qwen2.5-Math 和 Qwen2.5-Math-Instruct-1.5B/7B/72B。Qwen2.5 系列的核心创新在于贯穿整个流程的自我改进理念，从预训练到推理：（1）预训练阶段，利用 Qwen2-Math-Instruct 生成大量高质量数学数据。（2）后训练阶段，通过 Qwen2-Math-Instruct 的大量采样开发奖励模型（RM），并应用于监督微调（SFT）中数据的迭代进化。通过更强的 SFT 模型，迭代训练和更新 RM，指导下一轮 SFT 数据迭代。最终 SFT 模型上，使用最终 RM 进行强化学习，得到 Qwen2.5-Math-Instruct。（3）推理阶段，RM 指导采样，优化模型性能。Qwen2.5-Math-Instruct 支持中英文，具备先进的数学推理能力，包括思维链（CoT）和工具集成推理（TIR）。我们在 10 个中英文数学数据集上评估模型，如 GSM8K、MATH、GaoKao、AMC23 和 AIME24，涵盖从小学到竞赛的各种难度。

> In this report, we present a series of math-specific large language models: Qwen2.5-Math and Qwen2.5-Math-Instruct-1.5B/7B/72B. The core innovation of the Qwen2.5 series lies in integrating the philosophy of self-improvement throughout the entire pipeline, from pre-training and post-training to inference: (1) During the pre-training phase, Qwen2-Math-Instruct is utilized to generate large-scale, high-quality mathematical data. (2) In the post-training phase, we develop a reward model (RM) by conducting massive sampling from Qwen2-Math-Instruct. This RM is then applied to the iterative evolution of data in supervised fine-tuning (SFT). With a stronger SFT model, it's possible to iteratively train and update the RM, which in turn guides the next round of SFT data iteration. On the final SFT model, we employ the ultimate RM for reinforcement learning, resulting in the Qwen2.5-Math-Instruct. (3) Furthermore, during the inference stage, the RM is used to guide sampling, optimizing the model's performance.
  Qwen2.5-Math-Instruct supports both Chinese and English, and possess advanced mathematical reasoning capabilities, including Chain-of-Thought (CoT) and Tool-Integrated Reasoning (TIR). We evaluate our models on 10 mathematics datasets in both English and Chinese, such as GSM8K, MATH, GaoKao, AMC23, and AIME24, covering a range of difficulties from grade school level to math competition problems.

[Arxiv](https://arxiv.org/abs/2409.12122)