# 利用片段检索增强的分子生成

发布时间：2024年11月18日

`RAG` `药物发现` `分子生成`

> Molecule Generation with Fragment Retrieval Augmentation

# 摘要

> 基于片段的药物发现，也就是把分子片段组合成具备理想生化特性的新分子，成果斐然。但很多基于片段的分子生成方法在数据库现有片段之外的探索颇为有限，因为它们只是对给定片段进行重新组合或稍作修改。为应对此问题，我们提出了一个带有检索增强功能的新型基于片段的分子生成框架，即片段检索增强生成（f-RAG）。f-RAG基于预训练的分子生成模型，能从输入片段中提出额外片段来完成并生成新分子。给定一个片段词汇表，f-RAG 检索两类片段：（1）硬片段，作为构建模块会明确包含在新生成的分子中；（2）软片段，作为通过可训练的片段注入模块引导新片段生成的参考。为超越现有片段，f-RAG 通过迭代优化过程用生成的片段更新片段词汇表，这一过程还通过事后的遗传片段修改得到进一步强化。f-RAG 能够通过维持一个片段池，并凭借强大的生成先验，用新颖且高质量的片段对其进行扩展，从而实现更优的探索与利用平衡。

> Fragment-based drug discovery, in which molecular fragments are assembled into new molecules with desirable biochemical properties, has achieved great success. However, many fragment-based molecule generation methods show limited exploration beyond the existing fragments in the database as they only reassemble or slightly modify the given ones. To tackle this problem, we propose a new fragment-based molecule generation framework with retrieval augmentation, namely Fragment Retrieval-Augmented Generation (f-RAG). f-RAG is based on a pre-trained molecular generative model that proposes additional fragments from input fragments to complete and generate a new molecule. Given a fragment vocabulary, f-RAG retrieves two types of fragments: (1) hard fragments, which serve as building blocks that will be explicitly included in the newly generated molecule, and (2) soft fragments, which serve as reference to guide the generation of new fragments through a trainable fragment injection module. To extrapolate beyond the existing fragments, f-RAG updates the fragment vocabulary with generated fragments via an iterative refinement process which is further enhanced with post-hoc genetic fragment modification. f-RAG can achieve an improved exploration-exploitation trade-off by maintaining a pool of fragments and expanding it with novel and high-quality fragments through a strong generative prior.

[Arxiv](https://arxiv.org/abs/2411.12078)