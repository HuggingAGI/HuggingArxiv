# 潜在改写：层上的扰动可提升语言模型中的知识注入效果

发布时间：2024年11月01日

`LLM应用` `知识注入`

> Latent Paraphrasing: Perturbation on Layers Improves Knowledge Injection in Language Models

# 摘要

> 随着大型语言模型（LLMs）在知识持续演进的专业领域中愈发广泛地部署，及时且精准的知识注入需求变得极为关键。采用改写数据进行微调是强化知识注入的常用手段，然而它面临两大显著难题：因重复使用外部模型产生的高昂计算成本以及有限的样本多样性。为此，我们推出了 LaPael，这是一种潜在层面的改写方法，将与输入相关的噪声应用于早期的 LLM 层。此方法能在模型内部直接达成多样且语义一致的增强效果。而且，它免除了每次知识更新时生成改写的反复成本。我们在问答基准上的大量实验表明，LaPael 相较于标准微调以及现有的基于噪声的方法，能更好地提升知识注入效果。另外，将 LaPael 与数据层面的改写相结合，还能进一步增强性能。

> As Large Language Models (LLMs) are increasingly deployed in specialized domains with continuously evolving knowledge, the need for timely and precise knowledge injection has become essential. Fine-tuning with paraphrased data is a common approach to enhance knowledge injection, yet it faces two significant challenges: high computational costs due to repetitive external model usage and limited sample diversity. To this end, we introduce LaPael, a latent-level paraphrasing method that applies input-dependent noise to early LLM layers. This approach enables diverse and semantically consistent augmentations directly within the model. Furthermore, it eliminates the recurring costs of paraphrase generation for each knowledge update. Our extensive experiments on question-answering benchmarks demonstrate that LaPael improves knowledge injection over standard fine-tuning and existing noise-based approaches. Additionally, combining LaPael with data-level paraphrasing further enhances performance.

[Arxiv](https://arxiv.org/abs/2411.00686)