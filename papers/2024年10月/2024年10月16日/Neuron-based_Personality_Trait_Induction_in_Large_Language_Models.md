# 在大语言模型中，通过神经元诱导人格特质

发布时间：2024年10月16日

`LLM应用` `人工智能`

> Neuron-based Personality Trait Induction in Large Language Models

# 摘要

> 大型语言模型 (LLM) 在模拟人格特质方面日益精进，这对角色扮演等应用至关重要。本文提出了一种基于神经元的人格特质诱导方法，包含三大创新：首先，构建了 PersonalityBench 数据集，用于识别和评估 LLM 的人格特质；其次，通过 PersonalityBench 高效识别与性格相关的神经元；最后，开发了一种无需训练和修改参数的精细控制方法。实验证明，我们的方法与微调模型性能相当，为 LLM 的人格特质诱导提供了更高效灵活的解决方案。所有资源可在 https://github.com/RUCAIBox/NPTI 获取。

> Large language models (LLMs) have become increasingly proficient at simulating various personality traits, an important capability for supporting related applications (e.g., role-playing). To further improve this capacity, in this paper, we present a neuron-based approach for personality trait induction in LLMs, with three major technical contributions. First, we construct PersonalityBench, a large-scale dataset for identifying and evaluating personality traits in LLMs. This dataset is grounded in the Big Five personality traits from psychology and is designed to assess the generative capabilities of LLMs towards specific personality traits. Second, by leveraging PersonalityBench, we propose an efficient method for identifying personality-related neurons within LLMs by examining the opposite aspects of a given trait. Third, we develop a simple yet effective induction method that manipulates the values of these identified personality-related neurons. This method enables fine-grained control over the traits exhibited by LLMs without training and modifying model parameters. Extensive experiments validate the efficacy of our neuron identification and trait induction methods. Notably, our approach achieves comparable performance as fine-tuned models, offering a more efficient and flexible solution for personality trait induction in LLMs. We provide access to all the mentioned resources at https://github.com/RUCAIBox/NPTI.

[Arxiv](https://arxiv.org/abs/2410.12327)