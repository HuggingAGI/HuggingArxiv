# 大型语言模型中的认知完整性

发布时间：2024年11月10日

`LLM应用` `人工智能` `语言模型`

> Epistemic Integrity in Large Language Models

# 摘要

> 大型语言模型越来越多地被当作信息来源，但它们以高度自信生成错误或误导性陈述的倾向给用户和社会带来了风险。在本文中，我们面对认知失调的关键问题——模型的语言自信度未能反映其真正的内部确定性。我们引入了一个新的人工标注数据集和一种测量大型语言模型（LLM）语言自信度的新方法，相对于以前的基准，错误率降低了 50%以上。在多个数据集上得到验证，我们的方法揭示了模型语言自信地呈现信息的方式与其实际准确性之间存在明显的不一致。进一步的人工评估证实了这种失调的严重性。这一证据突显了大型语言模型过度自信可能大规模误导用户的紧迫风险。我们的框架在诊断这种失调方面向前迈出了关键的一步，为纠正它以及在各个领域实现更值得信赖的人工智能提供了一条途径。

> Large language models are increasingly relied upon as sources of information, but their propensity for generating false or misleading statements with high confidence poses risks for users and society. In this paper, we confront the critical problem of epistemic miscalibration $unicode{x2013}$ where a model's linguistic assertiveness fails to reflect its true internal certainty. We introduce a new human-labeled dataset and a novel method for measuring the linguistic assertiveness of Large Language Models (LLMs) which cuts error rates by over 50% relative to previous benchmarks. Validated across multiple datasets, our method reveals a stark misalignment between how confidently models linguistically present information and their actual accuracy. Further human evaluations confirm the severity of this miscalibration. This evidence underscores the urgent risk of the overstated certainty LLMs hold which may mislead users on a massive scale. Our framework provides a crucial step forward in diagnosing this miscalibration, offering a path towards correcting it and more trustworthy AI across domains.

[Arxiv](https://arxiv.org/abs/2411.06528)