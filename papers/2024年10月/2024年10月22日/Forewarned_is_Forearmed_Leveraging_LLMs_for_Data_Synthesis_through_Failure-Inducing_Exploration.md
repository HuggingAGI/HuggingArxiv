# 预先警告就是预先武装：通过引发失败的探索利用大型语言模型进行数据合成

发布时间：2024年10月22日

`LLM应用` `语言模型` `数据合成`

> Forewarned is Forearmed: Leveraging LLMs for Data Synthesis through Failure-Inducing Exploration

# 摘要

> 大型语言模型（LLMs）从对多样化、高质量的特定任务数据的训练中显著受益，在一系列下游应用中带来了令人印象深刻的性能。当前的方法通常依赖于人工注释的数据或预定义的任务模板来引导强大的 LLMs 合成与任务相关的数据，以进行有效的模型训练。然而，这种对人工设计组件的依赖可能会限制生成数据的范围，可能会忽略可能挑战模型的关键边缘情况或新场景。在本文中，我们提出了一种新颖的方法，ReverseGen，旨在自动生成能暴露 LLMs 弱点的有效训练样本。具体来说，我们引入了一个专门的提议者，经过训练以产生导致目标模型生成不满意响应的查询。然后，这些导致失败的查询被用于构建训练数据，有助于解决模型的缺点并提高整体性能。我们的方法是灵活的，可以应用于各种规模的模型（3B、7B 和 8B）。我们在三个关键应用（安全性、诚实性和数学）上评估了 ReverseGen，表明我们生成的数据既高效又多样。用 ReverseGen 生成的数据进行微调的模型始终优于那些在人工注释或一般模型生成的数据上训练的模型，为特定任务的 LLM 增强的数据合成提供了新的视角。

> Large language models (LLMs) have significantly benefited from training on diverse, high-quality task-specific data, leading to impressive performance across a range of downstream applications. Current methods often rely on human-annotated data or predefined task templates to direct powerful LLMs in synthesizing task-relevant data for effective model training. However, this dependence on manually designed components may constrain the scope of generated data, potentially overlooking critical edge cases or novel scenarios that could challenge the model. In this paper, we present a novel approach, ReverseGen, designed to automatically generate effective training samples that expose the weaknesses of LLMs. Specifically, we introduce a dedicated proposer trained to produce queries that lead target models to generate unsatisfactory responses. These failure-inducing queries are then used to construct training data, helping to address the models' shortcomings and improve overall performance. Our approach is flexible and can be applied to models of various scales (3B, 7B, and 8B). We evaluate ReverseGen on three key applications (safety, honesty, and math), demonstrating that our generated data is both highly effective and diverse. Models fine-tuned with ReverseGen-generated data consistently outperform those trained on human-annotated or general model-generated data, offering a new perspective on data synthesis for task-specific LLM enhancement.

[Arxiv](https://arxiv.org/abs/2410.16736)