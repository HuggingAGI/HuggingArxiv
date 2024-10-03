# PersonaMath：借助角色驱动的数据增强提升数学推理能力

发布时间：2024年10月02日

`LLM应用` `人工智能`

> PersonaMath: Enhancing Math Reasoning through Persona-Driven Data Augmentation

# 摘要

> 尽管闭源 LLM 在数学问题上表现出色，但开源模型仍难以应对。为此，我们提出了一种数据增强方法，并创建了 PersonaMathQA 数据集，基于 MATH 和 GSM8K 训练 PersonaMath 模型。我们的方法分两步：首先通过角色多样化增强数据集，然后通过反思提升问题质量。PersonaMath-7B 模型在 MATH 和 GSM8K 上的表现超越了所有基线，展示了我们数据集的高效性和多样性。我们已开源数据集、模型和代码，供公众使用。

> While closed-source Large Language Models (LLMs) demonstrate strong mathematical problem-solving abilities, open-source models continue to struggle with such tasks. To bridge this gap, we propose a data augmentation approach and introduce PersonaMathQA, a dataset derived from MATH and GSM8K, on which we train the PersonaMath models. Our approach consists of two stages: the first stage is learning from Persona Diversification, and the second stage is learning from Reflection. In the first stage, we regenerate detailed chain-of-thought (CoT) solutions as instructions using a closed-source LLM and introduce a novel persona-driven data augmentation technique to enhance the dataset's quantity and diversity. In the second stage, we incorporate reflection to fully leverage more challenging and valuable questions. Evaluation of our PersonaMath models on MATH and GSM8K reveals that the PersonaMath-7B model (based on LLaMA-2-7B) achieves an accuracy of 24.2% on MATH and 68.7% on GSM8K, surpassing all baseline methods and achieving state-of-the-art performance. Notably, our dataset contains only 70.3K data points-merely 17.8% of MetaMathQA and 27% of MathInstruct-yet our model outperforms these baselines, demonstrating the high quality and diversity of our dataset, which enables more efficient model training. We open-source the PersonaMathQA dataset, PersonaMath models, and our code for public usage.

[Arxiv](https://arxiv.org/abs/2410.01504)