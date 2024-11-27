# 不同标准下的偏差各异：以基于事实的方式评估LLMs中的偏差

发布时间：2024年11月26日

`LLM应用` `语言模型` `偏见评估`

> Different Bias Under Different Criteria: Assessing Bias in LLMs with a Fact-Based Approach

# 摘要

> 大型语言模型（LLMs）常常反映出真实世界存在的偏见，这促使人们努力去减轻这些影响，让模型不再有偏见。要达成此目标，就得为无偏见状态明确清晰的标准，但凡偏离这些标准的，都算有偏见。有些研究把无偏见状态定义为对不同人群一视同仁，期望LLMs能有均衡的输出。不过，对于平等的不同看法以及多元化的重要性，导致建立通用标准困难重重。另外，还有些方法提议采用基于事实的标准来进行更一致、更客观的评估，只是这些方法尚未完全用于LLM的偏见评估。所以，需要一种有客观标准的指标，它能提供与基于平等的方法不同的视角。基于此需求，我们引入了一种新的指标，用基于事实的标准和真实世界的统计数据来评估偏见。在本文中，我们做了一项人类调查，结果显示当LLM的输出与真实世界的人口分布高度吻合时，人类往往对其评价更积极。用我们提出的指标去评估各种LLM，发现模型的偏见会因所用标准不同而有所差异，这凸显了多视角评估的必要性。

> Large language models (LLMs) often reflect real-world biases, leading to efforts to mitigate these effects and make the models unbiased. Achieving this goal requires defining clear criteria for an unbiased state, with any deviation from these criteria considered biased. Some studies define an unbiased state as equal treatment across diverse demographic groups, aiming for balanced outputs from LLMs. However, differing perspectives on equality and the importance of pluralism make it challenging to establish a universal standard. Alternatively, other approaches propose using fact-based criteria for more consistent and objective evaluations, though these methods have not yet been fully applied to LLM bias assessments. Thus, there is a need for a metric with objective criteria that offers a distinct perspective from equality-based approaches. Motivated by this need, we introduce a novel metric to assess bias using fact-based criteria and real-world statistics. In this paper, we conducted a human survey demonstrating that humans tend to perceive LLM outputs more positively when they align closely with real-world demographic distributions. Evaluating various LLMs with our proposed metric reveals that model bias varies depending on the criteria used, highlighting the need for multi-perspective assessment.

[Arxiv](https://arxiv.org/abs/2411.17338)