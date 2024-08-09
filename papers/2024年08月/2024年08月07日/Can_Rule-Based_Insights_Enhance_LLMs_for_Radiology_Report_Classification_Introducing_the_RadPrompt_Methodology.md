# RadPrompt 方法论探索：基于规则的洞察如何助力大型语言模型在放射学报告分类中更上一层楼？

发布时间：2024年08月07日

`LLM应用` `人工智能`

> Can Rule-Based Insights Enhance LLMs for Radiology Report Classification? Introducing the RadPrompt Methodology

# 摘要

> 开发从胸部X光片检测病理的成像模型对大型数据集而言成本和时间消耗巨大，因其需监督以达顶尖性能。替代方案是从放射报告中提取标签作为远程监督，这些报告在临床实践中常规生成。然而，现有基于规则的提取方法依赖广泛规则集，对语法变异性的鲁棒性有限。为此，我们推出RadPert系统，整合不确定性感知信息模式与简化规则集，提升性能。同时，开发RadPrompt多轮提示策略，利用RadPert增强大型语言模型的零-shot预测能力，显著提升加权平均F1分数，超越GPT-4 Turbo。RadPrompt更超越其基础模型，彰显LLM与基于规则模型协同的潜力。我们在MIMIC-CXR及剑桥大学医院黄金标准数据集上验证了这些方法。

> Developing imaging models capable of detecting pathologies from chest X-rays can be cost and time-prohibitive for large datasets as it requires supervision to attain state-of-the-art performance. Instead, labels extracted from radiology reports may serve as distant supervision since these are routinely generated as part of clinical practice. Despite their widespread use, current rule-based methods for label extraction rely on extensive rule sets that are limited in their robustness to syntactic variability. To alleviate these limitations, we introduce RadPert, a rule-based system that integrates an uncertainty-aware information schema with a streamlined set of rules, enhancing performance. Additionally, we have developed RadPrompt, a multi-turn prompting strategy that leverages RadPert to bolster the zero-shot predictive capabilities of large language models, achieving a statistically significant improvement in weighted average F1 score over GPT-4 Turbo. Most notably, RadPrompt surpasses both its underlying models, showcasing the synergistic potential of LLMs with rule-based models. We have evaluated our methods on two English Corpora: the MIMIC-CXR gold-standard test set and a gold-standard dataset collected from the Cambridge University Hospitals.

[Arxiv](https://arxiv.org/abs/2408.04121)