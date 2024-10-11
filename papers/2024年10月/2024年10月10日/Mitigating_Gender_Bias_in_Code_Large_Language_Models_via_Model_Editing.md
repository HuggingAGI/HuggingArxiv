# 通过模型编辑技术，我们致力于减轻代码大型语言模型中的性别偏见问题。

发布时间：2024年10月10日

`LLM应用` `软件开发` `人工智能`

> Mitigating Gender Bias in Code Large Language Models via Model Editing

# 摘要

> 随着大型语言模型（LLM）技术的成熟和高质量编程代码数据集的涌现，自动解决程序合成挑战的信心日益增强。然而，未经筛选的训练样本可能导致LLM性能与现实脱节，引发社会偏见。为此，我们提出了CodeGenBias数据集和FB-Score评估指标，以量化代码LLM中的性别偏见。通过这些工具，我们分析了八种主流代码LLM的性别偏见。先前研究表明，优秀的模型编辑方法能有效减轻偏见。因此，我们开发了MG-Editing方法，涵盖定位与编辑两个阶段，可在五个参数粒度级别上应用。实验证明，MG-Editing不仅能有效减少性别偏见，还能保持代码生成能力，且在行和神经元级别上效果最佳。

> In recent years, with the maturation of large language model (LLM) technology and the emergence of high-quality programming code datasets, researchers have become increasingly confident in addressing the challenges of program synthesis automatically. However, since most of the training samples for LLMs are unscreened, it is inevitable that LLMs' performance may not align with real-world scenarios, leading to the presence of social bias. To evaluate and quantify the gender bias in code LLMs, we propose a dataset named CodeGenBias (Gender Bias in the Code Generation) and an evaluation metric called FB-Score (Factual Bias Score) based on the actual gender distribution of correlative professions. With the help of CodeGenBias and FB-Score, we evaluate and analyze the gender bias in eight mainstream Code LLMs. Previous work has demonstrated that model editing methods that perform well in knowledge editing have the potential to mitigate social bias in LLMs. Therefore, we develop a model editing approach named MG-Editing (Multi-Granularity model Editing), which includes the locating and editing phases. Our model editing method MG-Editing can be applied at five different levels of model parameter granularity: full parameters level, layer level, module level, row level, and neuron level. Extensive experiments not only demonstrate that our MG-Editing can effectively mitigate the gender bias in code LLMs while maintaining their general code generation capabilities, but also showcase its excellent generalization. At the same time, the experimental results show that, considering both the gender bias of the model and its general code generation capability, MG-Editing is most effective when applied at the row and neuron levels of granularity.

[Arxiv](https://arxiv.org/abs/2410.07820)