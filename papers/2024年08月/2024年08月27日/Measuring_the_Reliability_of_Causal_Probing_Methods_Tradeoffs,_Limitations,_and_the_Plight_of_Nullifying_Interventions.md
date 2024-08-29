# 评估因果探查方法的可靠性涉及权衡与局限，尤其是消除干预的难题。

发布时间：2024年08月27日

`LLM理论` `人工智能` `机器学习`

> Measuring the Reliability of Causal Probing Methods: Tradeoffs, Limitations, and the Plight of Nullifying Interventions

# 摘要

> 因果探针法通过训练探针识别嵌入中的潜在属性，并干预探针以改变其表示，进而分析模型行为的改变，以此解读大型语言模型等基础模型。尽管有研究对某些因果探针干预法的理论基础提出质疑，但如何系统评估其实际效果仍未明朗。为此，我们提出了一套经验分析框架，旨在评估因果探针干预的可靠性，并正式定义了两个关键指标：完整性和选择性。我们的框架首次实现了不同因果探针方法间的直接比较，如线性与非线性干预、反事实与无效干预。实验结果显示，这些标准间存在权衡，且无效干预的完整性远不如反事实干预，暗示无效方法在因果探针中可能并非有效选择。

> Causal probing is an approach to interpreting foundation models, such as large language models, by training probes to recognize latent properties of interest from embeddings, intervening on probes to modify this representation, and analyzing the resulting changes in the model's behavior. While some recent works have cast doubt on the theoretical basis of several leading causal probing intervention methods, it has been unclear how to systematically and empirically evaluate their effectiveness in practice. To address this problem, we propose a general empirical analysis framework to evaluate the reliability of causal probing interventions, formally defining and quantifying two key causal probing desiderata: completeness (fully transforming the representation of the target property) and selectivity (minimally impacting other properties). Our formalism allows us to make the first direct comparisons between different families of causal probing methods (e.g., linear vs. nonlinear or counterfactual vs. nullifying interventions). We conduct extensive experiments across several leading methods, finding that (1) there is an inherent tradeoff between these criteria, and no method is able to consistently satisfy both at once; and (2) across the board, nullifying interventions are always far less complete than counterfactual interventions, indicating that nullifying methods may not be an effective approach to causal probing.

[Arxiv](https://arxiv.org/abs/2408.15510)