# 大型语言模型生成推荐的可学习分词器

发布时间：2024年05月12日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在生成式推荐领域的应用，并提出了一种新的可学习标记器LETTER，以解决将推荐数据有效转化为LLMs语言空间的问题。论文关注的是LLMs在特定应用场景（即生成式推荐）中的实际应用和改进，因此属于LLM应用分类。` `推荐系统`

> Learnable Tokenizer for LLM-based Generative Recommendation

# 摘要

> 大型语言模型（LLMs）因其强大的世界知识和推理能力，在生成式推荐领域备受瞩目。然而，如何将推荐数据有效转化为LLMs的语言空间，是一个亟待解决的难题。现有方法在语义编码、协作信号整合及代码分配偏差处理上存在局限。为此，我们创新性地提出了LETTER，一种可学习的标记器，它通过融合分层语义、协作信号和代码分配多样性，满足了标识符的关键需求。LETTER采用残差量化VAE进行语义正则化，对比对齐损失进行协作正则化，并通过多样性损失减少代码分配偏差。我们在两个生成式推荐模型中应用了LETTER，并引入了排名引导的生成损失，以提升其排名能力。实验结果显示，LETTER在项目标记化方面表现卓越，为生成式推荐领域的发展注入了新的活力。

> Harnessing Large Language Models (LLMs) for generative recommendation has garnered significant attention due to LLMs' powerful capacities such as rich world knowledge and reasoning. However, a critical challenge lies in transforming recommendation data into the language space of LLMs through effective item tokenization. Existing approaches, such as ID identifiers, textual identifiers, and codebook-based identifiers, exhibit limitations in encoding semantic information, incorporating collaborative signals, or handling code assignment bias. To address these shortcomings, we propose LETTER (a LEarnable Tokenizer for generaTivE Recommendation), designed to meet the key criteria of identifiers by integrating hierarchical semantics, collaborative signals, and code assignment diversity. LETTER integrates Residual Quantized VAE for semantic regularization, a contrastive alignment loss for collaborative regularization, and a diversity loss to mitigate code assignment bias. We instantiate LETTER within two generative recommender models and introduce a ranking-guided generation loss to enhance their ranking ability. Extensive experiments across three datasets demonstrate the superiority of LETTER in item tokenization, thereby advancing the state-of-the-art in the field of generative recommendation.

[Arxiv](https://arxiv.org/abs/2405.07314)