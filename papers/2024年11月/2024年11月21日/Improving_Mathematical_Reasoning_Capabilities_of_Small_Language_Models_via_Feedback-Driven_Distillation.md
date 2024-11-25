# 借助反馈驱动的蒸馏来提升小型语言模型的数学推理能力

发布时间：2024年11月21日

`LLM应用`

> Improving Mathematical Reasoning Capabilities of Small Language Models via Feedback-Driven Distillation

# 摘要

> 大型语言模型（LLMs）具备非凡的推理能力，在各类任务中常常斩获顶尖性能。但因其数十亿的参数，对计算和内存的要求极高，难以在资源受限的环境中部署。知识蒸馏是个颇具前景的解决办法，能让 LLMs 把推理能力传递给小型语言模型（SLMs，参数≤ 10 亿），便于在低资源设备上广泛应用。现有的方法多聚焦于为蒸馏数据集生成优质的推理依据，却时常忽视数据数量和质量的关键作用。为应对这些挑战，我们提出了反馈驱动蒸馏（FDD）框架，以增强 SLMs 的数学推理能力。在初始化阶段，通过促使 LLMs 将数学问题与相应的推理原理配对来构建蒸馏数据集。我们依据 SLM 的表现把问题分为简单和困难两类。对于简单问题，LLMs 生成更复杂的变体；对于困难问题，则合成相似复杂度的新问题。此外，我们还提出了多轮蒸馏范式，以迭代丰富蒸馏数据集，逐步提升 SLMs 的数学推理能力。实验结果显示，我们的方法能让 SLMs 实现顶尖的数学推理性能。

> Large Language Models (LLMs) demonstrate exceptional reasoning capabilities, often achieving state-of-the-art performance in various tasks. However, their substantial computational and memory demands, due to billions of parameters, hinder deployment in resource-constrained environments. A promising solution is knowledge distillation, where LLMs transfer reasoning capabilities to Small Language Models (SLMs, $\le$ 1B parameters), enabling wider deployment on low-resource devices. Existing methods primarily focus on generating high-quality reasoning rationales for distillation datasets but often neglect the critical role of data quantity and quality. To address these challenges, we propose a Feedback-Driven Distillation (FDD) framework to enhance SLMs' mathematical reasoning capabilities. In the initialization stage, a distillation dataset is constructed by prompting LLMs to pair mathematical problems with corresponding reasoning rationales. We classify problems into easy and hard categories based on SLM performance. For easy problems, LLMs generate more complex variations, while for hard problems, new questions of similar complexity are synthesized. In addition, we propose a multi-round distillation paradigm to iteratively enrich the distillation datasets, thereby progressively improving the mathematical reasoning abilities of SLMs. Experimental results demonstrate that our method can make SLMs achieve SOTA mathematical reasoning performance.

[Arxiv](https://arxiv.org/abs/2411.14698)