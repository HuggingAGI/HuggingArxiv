# 大型语言模型，推理之师

发布时间：2023年06月13日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（如GPT-3 175B）作为推理导师，通过思维链（CoT）提示方法来增强小型模型的复杂推理能力。这种方法通过微调小型模型，使其能够处理复杂的推理任务，从而在模型规模和成本上实现显著的缩减。论文中提出的Fine-tune-CoT方法，以及利用教师模型生成多重推理路径来丰富微调数据的做法，都是针对具体应用场景的技术创新。因此，这篇论文更适合归类于LLM应用，因为它关注的是如何将大型语言模型的能力应用于小型模型的优化和提升，而不是理论研究或Agent的设计与实现。` `人工智能`

> Large Language Models Are Reasoning Teachers

# 摘要

> 近期研究揭示，通过思维链（CoT）提示，语言模型能够逐步攻克复杂推理难题。但此类方法依赖于GPT-3 175B等巨型模型，大规模部署成本不菲。本文创新地利用这些巨型模型作为推理导师，赋能小型模型进行复杂推理，大幅缩减模型规模。我们提出的Fine-tune-CoT方法，利用巨型教师模型生成推理样本，微调小型模型。在众多公共模型与复杂任务中，Fine-tune-CoT显著增强了小型模型的推理力，超越了基于提示的基准，甚至在多任务中胜过教师模型。我们还进一步拓展方法，利用教师模型为每一样本生成多重独特推理路径，丰富微调数据，跨数据集显著提升性能，即便对微型模型亦然。通过消融与样本研究，我们深入探讨了学生模型推理能力的崛起。项目代码与数据已公开于https://github.com/itsnamgyu/reasoning-teacher。

> Recent works have shown that chain-of-thought (CoT) prompting can elicit language models to solve complex reasoning tasks, step-by-step. However, prompt-based CoT methods are dependent on very large models such as GPT-3 175B which are prohibitive to deploy at scale. In this paper, we use these large models as reasoning teachers to enable complex reasoning in smaller models and reduce model size requirements by several orders of magnitude. We propose Fine-tune-CoT, a method that generates reasoning samples from very large teacher models to fine-tune smaller models. We evaluate our method on a wide range of public models and complex tasks. We find that Fine-tune-CoT enables substantial reasoning capability in small models, far outperforming prompt-based baselines and even the teacher model in many tasks. Additionally, we extend our method by leveraging the teacher model's ability to generate multiple distinct rationales for each original sample. Enriching the fine-tuning data with such diverse reasoning results in a substantial performance boost across datasets, even for very small models. We conduct ablations and sample studies to understand the emergence of reasoning capabilities of student models. Our code implementation and data are available at https://github.com/itsnamgyu/reasoning-teacher.

[Arxiv](https://arxiv.org/abs/2212.10071)