# 针对图表理解定制的多模态语言模型的预训练研究

发布时间：2024年07月19日

`LLM应用` `科学研究` `数据分析`

> On Pre-training of Multimodal Language Models Customized for Chart Understanding

# 摘要

> 近期研究针对特定领域任务定制的多模态大型语言模型 (MLLMs) 取得了显著成果，特别是在科学图表理解领域。这些研究通过视觉指令调优与专业数据集，有效提升了图表领域内的问答 (QA) 准确性。然而，这些研究往往忽视了自然图像-标题预训练数据与数字图表图像-QA数据之间的根本差异，尤其是在模型从图表中提取潜在数值的能力方面。本文通过探索改进 MLLMs 图表理解所需的训练过程，填补了这一研究空白。我们提出了三个关键发现：首先，在预训练中融入原始数据值，显著提升了对图表数据的解读能力；其次，在端到端微调过程中随机用文本表示替换图像，有效转移了语言推理能力至图表解释技能；最后，要求模型先提取图表的潜在数据再回答问题，进一步提高了准确性。基于这些发现，我们推出了 CHOPINLLM，一个专为深入图表理解设计的 MLLM。CHOPINLLM 不仅能够有效解释各种类型的图表，包括未注释的图表，还保持了强大的推理能力。此外，我们建立了一个新的基准，用于评估 MLLMs 对不同图表类型在不同理解水平上的表现。实验结果表明，CHOPINLLM 在理解广泛类型的注释和未注释图表方面均表现卓越。

> Recent studies customizing Multimodal Large Language Models (MLLMs) for domain-specific tasks have yielded promising results, especially in the field of scientific chart comprehension. These studies generally utilize visual instruction tuning with specialized datasets to enhance question and answer (QA) accuracy within the chart domain. However, they often neglect the fundamental discrepancy between natural image-caption pre-training data and digital chart image-QA data, particularly in the models' capacity to extract underlying numeric values from charts. This paper tackles this oversight by exploring the training processes necessary to improve MLLMs' comprehension of charts. We present three key findings: (1) Incorporating raw data values in alignment pre-training markedly improves comprehension of chart data. (2) Replacing images with their textual representation randomly during end-to-end fine-tuning transfer the language reasoning capability to chart interpretation skills. (3) Requiring the model to first extract the underlying chart data and then answer the question in the fine-tuning can further improve the accuracy. Consequently, we introduce CHOPINLLM, an MLLM tailored for in-depth chart comprehension. CHOPINLLM effectively interprets various types of charts, including unannotated ones, while maintaining robust reasoning abilities. Furthermore, we establish a new benchmark to evaluate MLLMs' understanding of different chart types across various comprehension levels. Experimental results show that CHOPINLLM exhibits strong performance in understanding both annotated and unannotated charts across a wide range of types.

[Arxiv](https://arxiv.org/abs/2407.14506)