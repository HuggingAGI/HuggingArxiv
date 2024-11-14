# Polymetis：用于多个材料领域的大型语言建模

发布时间：2024年11月13日

`LLM应用` `材料科学` `人工智能`

> Polymetis:Large Language Modeling for Multiple Material Domains

# 摘要

> 随着大型语言模型在各个领域的应用不断扩大，材料科学也迎来了人工智能驱动创新的机遇。传统依靠人工搜索材料科学相关信息的方式，现在正将人工智能技术作为辅助工具，以提高材料科学研究的效率。为了加快研究人员在材料科学研究中的知识获取和智能决策支持，本文提出了一个针对多种材料领域的大型语言模型 Polymetis 模型，旨在为材料领域提供高度专业的知识答案，涵盖能源材料、功能材料、合金材料、物理化学、生物学和其他材料方向。该模型使用了约 200 万条材料知识指令的数据集，在构建数据集的过程中，我们开发了智能提取大型模型（IELM），专门用于从科学文本中提取并形成结构化知识，避免了大量需要人工标注的成本，提高了效率。我们将这些数据注入 GLM4 - 9B 模型进行学习，以增强其在多种材料领域的推理能力。此外，我们还引入了增强的提示策略，以确保模型的答案更有条理和全面，为材料科学探索的多样化需求提供高效和全面的智能支持，促进材料科学的发展。

> As the application of large language models in various fields continues to expand, materials science also ushers in opportunities for AI-driven innovation. The traditional way of relying on manual search for materials science-related information is now using artificial intelligence technology as an auxiliary tool to improve the efficiency of materials science research. To accelerate researchers' knowledge acquisition and intelligent decision-making support in materials science research, this paper proposes a large language model Polymetis model for a variety of materials fields, aiming to provide highly professional knowledge answers in the field of materials, covering energy materials, functional materials, alloy materials, physical chemistry, biology, and other material directions. The model uses a dataset of about 2 million material knowledge instructions, and in the process of building the dataset, we developed the Intelligent Extraction Large Model (IELM), which is specially used to extract and form structured knowledge from scientific texts, avoiding a large number of costs that need to be manually annotated, and improving efficiency. We inject this data into the GLM4-9B model for learning to enhance its inference capabilities in a variety of material domains. In addition, we have introduced enhanced prompt strategies to ensure that the answers to the model are more organized and comprehensive, providing efficient and comprehensive intelligent support for the diverse needs of materials science exploration, and promoting the development of material science.

[Arxiv](https://arxiv.org/abs/2411.08728)