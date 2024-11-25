# MolReFlect：致力于实现分子与文本之间的上下文细粒度对齐

发布时间：2024年11月21日

`LLM应用` `分子研究`

> MolReFlect: Towards In-Context Fine-grained Alignments between Molecules and Texts

# 摘要

> 分子发现是一个至关重要的研究领域，其影响涵盖了从我们服用的药物到使用的材料等诸多方面。近来，大型语言模型（LLMs）在分子的理解与生成领域得到了广泛应用，然而分子与其对应描述之间的对齐问题仍是重大挑战。过往的尝试往往将分子视作普通的 SMILES 字符串或分子图，忽略了分子子结构与描述性文本短语之间的细粒度对齐，而这对于实现准确且可解释的预测极为关键。在此情形下，我们推出了 MolReFlect，这是一个全新的师生框架，旨在以细粒度的方式在上下文中实现分子与描述的对齐。我们的方法起初借助更大的教师 LLM，直接从分子描述或 SMILES 字符串中提取关键短语，并将其与相应的子结构或特征关联，以标记详细的对齐情况。为优化这些对齐，我们提出了上下文选择性反射，它会检索先前的提取结果作为教师 LLM 的上下文示例进行反射，同时让较小的学生 LLM 从上下文反射和先前的提取结果中进行选择。最后，我们通过思维链上下文分子调整来强化学生 LLM 的学习过程，将细粒度的对齐与思维链格式中的推理过程加以整合。我们的实验结果显示，MolReFlect 让像 Mistral-7B 这样的 LLMs 大幅超越以往的基线，在 ChEBI-20 数据集上达成了 SOTA 性能。这一进展不但增强了 LLMs 在分子与描述翻译任务中的生成能力，还有助于构建一个更具解释性的框架。

> Molecule discovery is a pivotal research field, impacting everything from the medicines we take to the materials we use. Recently, Large Language Models (LLMs) have been widely adopted in molecule understanding and generation, yet the alignments between molecules and their corresponding captions remain a significant challenge. Previous endeavours often treat the molecule as a general SMILES string or molecular graph, neglecting the fine-grained alignments between the molecular sub-structures and the descriptive textual phrases, which are crucial for accurate and explainable predictions. In this case, we introduce MolReFlect, a novel teacher-student framework designed to contextually perform the molecule-caption alignments in a fine-grained way. Our approach initially leverages a larger teacher LLM to label the detailed alignments by directly extracting critical phrases from molecule captions or SMILES strings and implying them to corresponding sub-structures or characteristics. To refine these alignments, we propose In-Context Selective Reflection, which retrieves previous extraction results as context examples for teacher LLM to reflect and lets a smaller student LLM select from in-context reflection and previous extraction results. Finally, we enhance the learning process of the student LLM through Chain-of-Thought In-Context Molecule Tuning, integrating the fine-grained alignments and the reasoning processes within the Chain-of-Thought format. Our experimental results demonstrate that MolReFlect enables LLMs like Mistral-7B to significantly outperform the previous baselines, achieving SOTA performance on the ChEBI-20 dataset. This advancement not only enhances the generative capabilities of LLMs in the molecule-caption translation task, but also contributes to a more explainable framework.

[Arxiv](https://arxiv.org/abs/2411.14721)