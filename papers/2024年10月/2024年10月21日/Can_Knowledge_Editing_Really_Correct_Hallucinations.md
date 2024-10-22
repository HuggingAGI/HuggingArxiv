# 知识编辑能否真正修正幻觉？

发布时间：2024年10月21日

`LLM理论` `人工智能` `数据集`

> Can Knowledge Editing Really Correct Hallucinations?

# 摘要

> 尽管大型语言模型 (LLM) 在多项任务中表现卓越，但仍存在生成内容中包含非事实信息的幻觉问题。为此，知识编辑作为一种无需从头训练即可纠正错误知识的新方法应运而生。然而，现有评估数据集的一个缺陷是，它们无法确保 LLM 在编辑前对评估问题生成幻觉答案。这使得在不同技术编辑后的 LLM 评估中，难以直接衡量知识编辑方法在纠正幻觉方面的有效性。因此，一个关键问题仍待解答：知识编辑真的能有效纠正 LLM 中的幻觉吗？我们提出了 HalluEditBench，旨在全面评估知识编辑方法在现实世界幻觉纠正中的表现。首先，我们构建了一个包含 9 个领域、26 个主题和超过 6,000 个幻觉的大规模数据集。接着，我们在五个维度（功效、泛化性、可移植性、局部性和鲁棒性）上全面评估这些方法。通过 HalluEditBench，我们揭示了不同知识编辑方法在幻觉纠正中的潜力与局限，为未来的改进和知识编辑领域的发展提供了新的思路。

> Large Language Models (LLMs) suffer from hallucinations, referring to the non-factual information in generated content, despite their superior capacities across tasks. Meanwhile, knowledge editing has been developed as a new popular paradigm to correct the erroneous factual knowledge encoded in LLMs with the advantage of avoiding retraining from scratch. However, one common issue of existing evaluation datasets for knowledge editing is that they do not ensure LLMs actually generate hallucinated answers to the evaluation questions before editing. When LLMs are evaluated on such datasets after being edited by different techniques, it is hard to directly adopt the performance to assess the effectiveness of different knowledge editing methods in correcting hallucinations. Thus, the fundamental question remains insufficiently validated: Can knowledge editing really correct hallucinations in LLMs? We proposed HalluEditBench to holistically benchmark knowledge editing methods in correcting real-world hallucinations. First, we rigorously construct a massive hallucination dataset with 9 domains, 26 topics and more than 6,000 hallucinations. Then, we assess the performance of knowledge editing methods in a holistic way on five dimensions including Efficacy, Generalization, Portability, Locality, and Robustness. Through HalluEditBench, we have provided new insights into the potentials and limitations of different knowledge editing methods in correcting hallucinations, which could inspire future improvements and facilitate the progress in the field of knowledge editing.

[Arxiv](https://arxiv.org/abs/2410.16251)