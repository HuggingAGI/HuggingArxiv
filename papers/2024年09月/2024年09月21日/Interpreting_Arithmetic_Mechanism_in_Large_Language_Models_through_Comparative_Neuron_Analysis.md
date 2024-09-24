# 通过神经元对比分析，揭示大型语言模型中的算术机制

发布时间：2024年09月21日

`LLM理论` `人工智能` `机器学习`

> Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis

# 摘要

> 我们发现算术能力集中在少数注意力头中，每个头各司其职。为探究其原因，我们提出了比较神经元分析（CNA）方法，揭示了从输入到预测的四个阶段：浅层FFN神经元增强特征，浅层注意力层转移特征，算术头预测特征，深层FFN神经元增强预测。我们还识别了特征增强和预测阶段中的人类可解释神经元。这些发现帮助我们理解LoRA如何通过放大相关神经元的系数来提升预测准确性。最终，我们将此方法应用于算术任务的模型优化和性别偏见的减少。代码详见https://github.com/zepingyu0512/arithmetic-mechanism。

> We find arithmetic ability resides within a limited number of attention heads, with each head specializing in distinct operations. To delve into the reason, we introduce the Comparative Neuron Analysis (CNA) method, which identifies an internal logic chain consisting of four distinct stages from input to prediction: feature enhancing with shallow FFN neurons, feature transferring by shallow attention layers, feature predicting by arithmetic heads, and prediction enhancing among deep FFN neurons. Moreover, we identify the human-interpretable FFN neurons within both feature-enhancing and feature-predicting stages. These findings lead us to investigate the mechanism of LoRA, revealing that it enhances prediction probabilities by amplifying the coefficient scores of FFN neurons related to predictions. Finally, we apply our method in model pruning for arithmetic tasks and model editing for reducing gender bias. Code is on https://github.com/zepingyu0512/arithmetic-mechanism.

[Arxiv](https://arxiv.org/abs/2409.14144)