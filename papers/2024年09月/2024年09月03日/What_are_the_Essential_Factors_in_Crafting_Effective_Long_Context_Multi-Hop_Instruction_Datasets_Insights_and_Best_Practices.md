# 制作高效长篇多跳指令数据集的关键要素是什么？探索见解与最佳实践

发布时间：2024年09月03日

`LLM应用` `人工智能` `数据科学`

> What are the Essential Factors in Crafting Effective Long Context Multi-Hop Instruction Datasets? Insights and Best Practices

# 摘要

> 随着大型语言模型（LLMs）上下文窗口的扩展，信息提取、问答和复杂规划等任务的性能得到了显著提升。为了在长上下文任务中取得成功，业界通过合成数据大力提升模型的长上下文处理能力。现有方法多采用Self-Instruct框架生成指令调优数据，以期更好地改进长上下文能力。然而，我们的初步实验发现，生成的样本中多跳问题不足35%，且超过40%质量欠佳，这限制了全面理解和深入研究。为此，我们提出了多智能体交互多跳生成（MIMG）框架，该框架通过引入质量验证智能体、单跳问题生成智能体、多问题采样策略和多跳问题合并智能体，大幅提升了数据质量，使得高质量、多跳和多样化数据的比例超过85%。通过在多种模型上进行广泛实验，我们系统地探讨了文档选择、问题合并和验证技术等策略。研究结果表明，我们合成的优质长上下文指令数据不仅显著提升了模型性能，甚至超越了那些依赖更多人类标注数据训练的模型。相关代码已公开，详见：https://github.com/WowCZ/LongMIT。

> Recent advancements in large language models (LLMs) with extended context windows have significantly improved tasks such as information extraction, question answering, and complex planning scenarios. In order to achieve success in long context tasks, a large amount of work has been done to enhance the long context capabilities of the model through synthetic data. Existing methods typically utilize the Self-Instruct framework to generate instruction tuning data for better long context capability improvement. However, our preliminary experiments indicate that less than 35% of generated samples are multi-hop, and more than 40% exhibit poor quality, limiting comprehensive understanding and further research. To improve the quality of synthetic data, we propose the Multi-agent Interactive Multi-hop Generation (MIMG) framework, incorporating a Quality Verification Agent, a Single-hop Question Generation Agent, a Multiple Question Sampling Strategy, and a Multi-hop Question Merger Agent. This framework improves the data quality, with the proportion of high-quality, multi-hop, and diverse data exceeding 85%. Furthermore, we systematically investigate strategies for document selection, question merging, and validation techniques through extensive experiments across various models. Our findings show that our synthetic high-quality long-context instruction data significantly enhances model performance, even surpassing models trained on larger amounts of human-annotated data. Our code is available at: https://github.com/WowCZ/LongMIT.

[Arxiv](https://arxiv.org/abs/2409.01893)