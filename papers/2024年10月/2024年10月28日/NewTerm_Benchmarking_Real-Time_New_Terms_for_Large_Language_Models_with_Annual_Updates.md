# NewTerm: 对大型语言模型的实时新术语进行基准测试，且每年更新

发布时间：2024年10月28日

`LLM应用` `语言模型` `基准测试`

> NewTerm: Benchmarking Real-Time New Terms for Large Language Models with Annual Updates

# 摘要

> 尽管大型语言模型（LLMs）在各类任务中能力出众，但因其开发过程中的知识截止，在实时信息（如新的事实和术语）上仍力不从心。然而，现有的基准测试聚焦于过时内容和有限领域，实时更新困难重重，对新术语也缺乏探索。为应对此问题，我们提出了自适应基准测试 NewTerm，用于新术语的实时评估。我们设计了高度自动化的构建方法，以最少人力确保高质量基准构建，还能灵活更新实时信息。在各类 LLMs 上的实践结果显示，新术语致使性能降低超 20%。另外，虽然更新 LLMs 的知识截止能涵盖部分新术语，但无法推广到更久远的新术语。我们还剖析了哪些类型的术语更具挑战性以及 LLMs 为何应对新术语困难，为后续研究铺平道路。最后，我们构建了 NewTerm 2022 和 2023 来评估每年更新的新术语，并会持续每年更新。基准测试和代码可在 https://github.com/hexuandeng/NewTerm 找到。

> Despite their remarkable abilities in various tasks, large language models (LLMs) still struggle with real-time information (e.g., new facts and terms) due to the knowledge cutoff in their development process. However, existing benchmarks focus on outdated content and limited fields, facing difficulties in real-time updating and leaving new terms unexplored. To address this problem, we propose an adaptive benchmark, NewTerm, for real-time evaluation of new terms. We design a highly automated construction method to ensure high-quality benchmark construction with minimal human effort, allowing flexible updates for real-time information. Empirical results on various LLMs demonstrate over 20% performance reduction caused by new terms. Additionally, while updates to the knowledge cutoff of LLMs can cover some of the new terms, they are unable to generalize to more distant new terms. We also analyze which types of terms are more challenging and why LLMs struggle with new terms, paving the way for future research. Finally, we construct NewTerm 2022 and 2023 to evaluate the new terms updated each year and will continue updating annually. The benchmark and codes can be found at https://github.com/hexuandeng/NewTerm.

[Arxiv](https://arxiv.org/abs/2410.20814)