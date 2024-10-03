# 通过顺序贪婪过滤，提升样本效率的保形生成建模

发布时间：2024年10月02日

`LLM理论` `安全关键应用`

> Conformal Generative Modeling with Improved Sample Efficiency through Sequential Greedy Filtering

# 摘要

> 生成模型在安全关键应用中因缺乏严格的统计保证而不可靠。我们提出了SCOPE-Gen，一种顺序一致性预测方法，确保预测集满足严格的统计保证，即高概率包含至少一个有效示例。该方法首先从黑箱生成模型中采样初始示例集，然后通过贪婪过滤器迭代修剪。最终预测集的可接受性分解为马尔可夫链，便于分别控制每个因子。与以往方法相比，SCOPE-Gen在校准期间大幅减少了可接受性评估次数，这在需专家手动评估的安全关键应用中尤为重要。通过自然语言生成和分子图扩展任务的实验，我们展示了该方法在可接受性评估和预测集基数方面的显著优势。

> Generative models lack rigorous statistical guarantees for their outputs and are therefore unreliable in safety-critical applications. In this work, we propose Sequential Conformal Prediction for Generative Models (SCOPE-Gen), a sequential conformal prediction method producing prediction sets that satisfy a rigorous statistical guarantee called conformal admissibility control. This guarantee states that with high probability, the prediction sets contain at least one admissible (or valid) example. To this end, our method first samples an initial set of i.i.d. examples from a black box generative model. Then, this set is iteratively pruned via so-called greedy filters. As a consequence of the iterative generation procedure, admissibility of the final prediction set factorizes as a Markov chain. This factorization is crucial, because it allows to control each factor separately, using conformal prediction. In comparison to prior work, our method demonstrates a large reduction in the number of admissibility evaluations during calibration. This reduction is important in safety-critical applications, where these evaluations must be conducted manually by domain experts and are therefore costly and time consuming. We highlight the advantages of our method in terms of admissibility evaluations and cardinality of the prediction sets through experiments in natural language generation and molecular graph extension tasks.

[Arxiv](https://arxiv.org/abs/2410.01660)