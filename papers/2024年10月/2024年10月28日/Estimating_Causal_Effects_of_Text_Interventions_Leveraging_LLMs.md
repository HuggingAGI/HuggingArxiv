# 估算借助大型语言模型进行的文本干预所产生的因果效应

发布时间：2024年10月28日

`LLM应用` `社会科学` `因果推断`

> Estimating Causal Effects of Text Interventions Leveraging LLMs

# 摘要

> 量化社会系统中的文本干预效果，比如降低社交媒体帖子中的愤怒情绪，观察其对参与度的影响，这颇具挑战。直接对现实世界系统进行干预往往难以实现，所以得依靠观察数据。传统的因果推断方法通常是为二元或离散处理设计的，难以应对文本数据复杂、高维的特性。本文提出了一种新方法 CausalDANN 来应对这些挑战，借助大型语言模型（LLMs）推动的文本转换来估算因果效应。和现有方法不同，我们的方法能适应各种文本干预，并利用具有领域适应能力的文本级分类器，即便只观察到对照组，也能针对领域转移得出稳健的效果估计。这种处理各类文本干预的灵活性是文本数据因果估算的重要进步，为更好地理解人类行为以及在社会系统中制定有效政策创造了机会。

> Quantifying the effect of textual interventions in social systems, such as reducing anger in social media posts to see its impact on engagement, poses significant challenges. Direct interventions on real-world systems are often infeasible, necessitating reliance on observational data. Traditional causal inference methods, typically designed for binary or discrete treatments, are inadequate for handling the complex, high-dimensional nature of textual data. This paper addresses these challenges by proposing a novel approach, CausalDANN, to estimate causal effects using text transformations facilitated by large language models (LLMs). Unlike existing methods, our approach accommodates arbitrary textual interventions and leverages text-level classifiers with domain adaptation ability to produce robust effect estimates against domain shifts, even when only the control group is observed. This flexibility in handling various text interventions is a key advancement in causal estimation for textual data, offering opportunities to better understand human behaviors and develop effective policies within social systems.

[Arxiv](https://arxiv.org/abs/2410.21474)