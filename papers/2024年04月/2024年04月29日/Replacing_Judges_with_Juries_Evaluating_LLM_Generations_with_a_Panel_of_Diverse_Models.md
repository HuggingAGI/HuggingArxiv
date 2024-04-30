# 以多元模型小组评判，取代传统法官角色：深入评估大型语言模型的创作成果

发布时间：2024年04月29日

`LLM应用` `人工智能`

> Replacing Judges with Juries: Evaluating LLM Generations with a Panel of Diverse Models

# 摘要

> 随着大型语言模型（LLMs）技术的飞速发展，我们对其质量的精准评估能力却未能跟上步伐。寻找合适的数据来充分探究模型特性变得日益艰难，而单独对模型的自由生成内容进行正确性评估同样充满挑战。为应对这一难题，当前许多评估方法开始借助LLMs自身的能力，来对其他LLMs的输出成果进行质量评定。这种评估方式通常依赖于单一的大型模型，如GPT4。尽管这种方法日益流行，但它不仅成本高昂，还可能带来模型内部偏见。在本项研究中，我们发现超大型模型往往并非必要。我们提出一种新的方法：利用一个由多个LLM评估员组成的评审团（PoLL）来执行模型评估。在三种不同的评审情境和六个不同的数据集上进行测试，我们发现采用由众多小型模型构成的PoLL评审团，不仅在性能上超越了单一大型模型评审，而且在成本上节省了超过七倍，同时因其由不同的模型家族组成，还减少了模型内部偏见。

> As Large Language Models (LLMs) have become more advanced, they have outpaced our abilities to accurately evaluate their quality. Not only is finding data to adequately probe particular model properties difficult, but evaluating the correctness of a model's freeform generation alone is a challenge. To address this, many evaluations now rely on using LLMs themselves as judges to score the quality of outputs from other LLMs. Evaluations most commonly use a single large model like GPT4. While this method has grown in popularity, it is costly, has been shown to introduce intramodel bias, and in this work, we find that very large models are often unnecessary. We propose instead to evaluate models using a Panel of LLm evaluators (PoLL). Across three distinct judge settings and spanning six different datasets, we find that using a PoLL composed of a larger number of smaller models outperforms a single large judge, exhibits less intra-model bias due to its composition of disjoint model families, and does so while being over seven times less expensive.

[Arxiv](https://arxiv.org/abs/2404.18796)