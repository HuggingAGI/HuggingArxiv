# UrBench：全面评估大型多模态模型在多视角城市场景中的基准

发布时间：2024年08月30日

`LLM应用` `城市规划` `人工智能`

> UrBench: A Comprehensive Benchmark for Evaluating Large Multimodal Models in Multi-View Urban Scenarios

# 摘要

> 近期评估显示，大型多模态模型 (LMMs) 虽在多领域表现出色，但在城市环境方面的基准测试仍显不足。现有城市基准仅限于单一视角下的基础任务评估，未能全面展现 LMMs 在城市环境中的真实能力。为此，我们推出了 UrBench，一个专为复杂多视角城市场景设计的全面基准。UrBench 包含 11.6K 精心设计的问题，覆盖地理定位、场景推理、场景理解和对象理解四大任务维度，共计 14 种任务类型。我们结合现有数据集和从 11 个城市新收集的数据，采用跨视角检测匹配方法进行标注，进而整合基于 LMM、规则和人类的方法，构建了大规模高质量问题集。评估结果表明，即便是最先进的 GPT-4o，在城市环境中的表现也远不及人类，平均差距达 17.4%。此外，LMMs 在不同城市视角下的表现存在显著差异，尤其是在跨视角关系理解方面。UrBench 数据集及评估结果将在 https://opendatalab.github.io/UrBench/ 公开发布。

> Recent evaluations of Large Multimodal Models (LMMs) have explored their capabilities in various domains, with only few benchmarks specifically focusing on urban environments. Moreover, existing urban benchmarks have been limited to evaluating LMMs with basic region-level urban tasks under singular views, leading to incomplete evaluations of LMMs' abilities in urban environments. To address these issues, we present UrBench, a comprehensive benchmark designed for evaluating LMMs in complex multi-view urban scenarios. UrBench contains 11.6K meticulously curated questions at both region-level and role-level that cover 4 task dimensions: Geo-Localization, Scene Reasoning, Scene Understanding, and Object Understanding, totaling 14 task types. In constructing UrBench, we utilize data from existing datasets and additionally collect data from 11 cities, creating new annotations using a cross-view detection-matching method. With these images and annotations, we then integrate LMM-based, rule-based, and human-based methods to construct large-scale high-quality questions. Our evaluations on 21 LMMs show that current LMMs struggle in the urban environments in several aspects. Even the best performing GPT-4o lags behind humans in most tasks, ranging from simple tasks such as counting to complex tasks such as orientation, localization and object attribute recognition, with an average performance gap of 17.4%. Our benchmark also reveals that LMMs exhibit inconsistent behaviors with different urban views, especially with respect to understanding cross-view relations. UrBench datasets and benchmark results will be publicly available at https://opendatalab.github.io/UrBench/.

[Arxiv](https://arxiv.org/abs/2408.17267)