# 语言模型的物理学：第 3.3 部分，知识容量缩放定律

发布时间：2024年04月08日

`LLM理论` `知识存储`

> Physics of Language Models: Part 3.3, Knowledge Capacity Scaling Laws

# 摘要

> 摘要：缩放定律描述了语言模型的规模与其能力之间的关系。与之前通过损失或基准评估模型能力的研究不同，我们估计模型存储的知识位数量。我们专注于以元组形式表示的事实知识，例如来自维基百科页面的（美国，首都，华盛顿特区）。通过多个受控数据集，我们确定语言模型可以并且只能每个参数存储 2 位知识，即使量化为 int8，并且此类知识可以灵活提取用于下游应用。因此，一个 7B 模型可以存储 14B 位知识，根据我们的估计，超过了英语维基百科和教科书的总和。

更广泛地说，我们展示了 12 个关于（1）训练持续时间，（2）模型架构，（3）量化，（4）诸如 MoE 之类的稀疏性约束，以及（5）数据信噪比如何影响模型的知识存储容量的结果。值得注意的见解包括：

* 具有旋转嵌入的 GPT-2 架构在知识存储方面与 LLaMA/Mistral 架构相当甚至超越，特别是在较短的训练持续时间内。这是因为 LLaMA/Mistral 使用门控 MLP，其稳定性较差且更难训练。

* 在训练数据前加上域名（例如，此 http URL）会显著增加模型的知识容量。语言模型可以自主识别并优先考虑知识丰富的领域，优化其存储容量。

> 
Abstract:Scaling laws describe the relationship between the size of language models and their capabilities. Unlike prior studies that evaluate a model's capability via loss or benchmarks, we estimate the number of knowledge bits a model stores. We focus on factual knowledge represented as tuples, such as (USA, capital, Washington D.C.) from a Wikipedia page. Through multiple controlled datasets, we establish that language models can and only can store 2 bits of knowledge per parameter, even when quantized to int8, and such knowledge can be flexibly extracted for downstream applications. Consequently, a 7B model can store 14B bits of knowledge, surpassing the English Wikipedia and textbooks combined based on our estimation.
More broadly, we present 12 results on how (1) training duration, (2) model architecture, (3) quantization, (4) sparsity constraints such as MoE, and (5) data signal-to-noise ratio affect a model's knowledge storage capacity. Notable insights include:
* The GPT-2 architecture, with rotary embedding, matches or even surpasses LLaMA/Mistral architectures in knowledge storage, particularly over shorter training durations. This arises because LLaMA/Mistral uses GatedMLP, which is less stable and harder to train.
* Prepending training data with domain names (e.g., this http URL) significantly increases a model's knowledge capacity. Language models can autonomously identify and prioritize domains rich in knowledge, optimizing their storage capacity.
    

[Arxiv](https://arxiv.org/pdf/2404.05405)