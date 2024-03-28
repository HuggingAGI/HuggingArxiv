# WMDP基准计划旨在衡量并有效减少恶意使用，其方法是采用“消除学习”技术。这个测试标准聚焦于评估及降低利用机器学习模型进行恶意行为的可能性，并探索通过“遗忘学习”机制来达成这一目标的途径。

发布时间：2024年03月05日

`Agent`

> The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning

# 摘要

> 白宫发布的AI行政命令警示了LLMs在生物、网络及化学武器制造中可能助力恶意行为的风险。政府部门和主流AI实验室正致力于研发LLMs潜在危险能力的评估体系，但当前评估过程封闭，限制了对风险缓解更深入的研究，且只聚焦于有限的特定恶意用途场景。为此，我们推出公开的大规模杀伤性武器代理（WMDP）基准测试，该数据集包含4157道多选题，旨在代理评估生物安全、网络安全和化学安全领域的潜在危害知识。此数据集由学术界和技术专家团队精心打造，在公开前严格过滤了敏感信息。WMDP不仅可作为检验LLMs中危险知识的标尺，还为评估和改进去除有害知识的去学习方法提供了基准。为了推动去学习技术发展，我们创新研发出基于模型表征控制的前沿去学习方法CUT。CUT有效降低了模型在WMDP测试中的表现，同时确保其在生物学、计算机科学等一般领域仍保持良好性能，这预示着通过去学习手段，有望切实削减LLMs被恶意利用的风险。现将我们的基准数据集与代码于https://wmdp.ai 网站上公开发布。

> The White House Executive Order on Artificial Intelligence highlights the risks of large language models (LLMs) empowering malicious actors in developing biological, cyber, and chemical weapons. To measure these risks of malicious use, government institutions and major AI labs are developing evaluations for hazardous capabilities in LLMs. However, current evaluations are private, preventing further research into mitigating risk. Furthermore, they focus on only a few, highly specific pathways for malicious use. To fill these gaps, we publicly release the Weapons of Mass Destruction Proxy (WMDP) benchmark, a dataset of 4,157 multiple-choice questions that serve as a proxy measurement of hazardous knowledge in biosecurity, cybersecurity, and chemical security. WMDP was developed by a consortium of academics and technical consultants, and was stringently filtered to eliminate sensitive information prior to public release. WMDP serves two roles: first, as an evaluation for hazardous knowledge in LLMs, and second, as a benchmark for unlearning methods to remove such hazardous knowledge. To guide progress on unlearning, we develop CUT, a state-of-the-art unlearning method based on controlling model representations. CUT reduces model performance on WMDP while maintaining general capabilities in areas such as biology and computer science, suggesting that unlearning may be a concrete path towards reducing malicious use from LLMs. We release our benchmark and code publicly at https://wmdp.ai

[Arxiv](https://arxiv.org/abs/2403.03218)