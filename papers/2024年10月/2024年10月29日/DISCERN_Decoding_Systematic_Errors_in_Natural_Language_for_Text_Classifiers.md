# DISCERN：对文本分类器中自然语言的系统性错误进行解码

发布时间：2024年10月29日

`LLM应用` `机器学习` `文本分类`

> DISCERN: Decoding Systematic Errors in Natural Language for Text Classifiers

# 摘要

> 尽管当下的机器学习系统预测准确率颇高，但常因标注瑕疵或数据集里某些类别的支持不够，而呈现出系统性偏差。近期工作提出了借助关键字来识别与解释系统性偏差的自动方法。我们推出了 DISCERN，这是一个运用语言解释来阐释文本分类器中系统性偏差的框架。DISCERN 借助两个大型语言模型之间的交互循环，反复生成系统性错误的精准自然语言描述。最终，我们利用这些描述，通过给分类器训练集增添合成生成的实例或者通过主动学习标注的示例，来优化分类器。在三个文本分类数据集中，我们表明，我们框架的语言解释所带来的性能提升是持续的，且超越了仅靠系统性偏差的示例所能达成的效果。最后，在人类评估里，我们显示，当通过语言解释而非聚类示例来进行描述时，用户能够更有效地（相对超过 25％）且高效地解读系统性偏差。

> Despite their high predictive accuracies, current machine learning systems often exhibit systematic biases stemming from annotation artifacts or insufficient support for certain classes in the dataset. Recent work proposes automatic methods for identifying and explaining systematic biases using keywords. We introduce DISCERN, a framework for interpreting systematic biases in text classifiers using language explanations. DISCERN iteratively generates precise natural language descriptions of systematic errors by employing an interactive loop between two large language models. Finally, we use the descriptions to improve classifiers by augmenting classifier training sets with synthetically generated instances or annotated examples via active learning. On three text-classification datasets, we demonstrate that language explanations from our framework induce consistent performance improvements that go beyond what is achievable with exemplars of systematic bias. Finally, in human evaluations, we show that users can interpret systematic biases more effectively (by over 25% relative) and efficiently when described through language explanations as opposed to cluster exemplars.

[Arxiv](https://arxiv.org/abs/2410.22239)