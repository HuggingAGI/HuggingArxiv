# 对文本分类器的反事实解释方法的比较分析

发布时间：2024年11月04日

`LLM应用` `文本分类` `反事实解释`

> A Comparative Analysis of Counterfactual Explanation Methods for Text Classifiers

# 摘要

> 反事实解释可用于解释和调试文本分类器，通过生成最小改变的文本输入来改变分类器的输出。在这项工作中，我们使用三个评估指标在两个数据集上评估了为 BERT 文本分类器生成反事实解释的五种方法。我们的实验结果表明，已建立的基于白盒替换的方法在生成改变分类器输出的有效反事实方面是有效的。相比之下，基于大型语言模型（LLM）的较新方法在生成自然且语言上合理的文本反事实方面表现出色，但往往无法生成改变分类器输出的有效反事实。基于这些结果，我们建议开发新的反事实解释方法，将已建立的基于梯度的方法和较新的基于 LLM 的技术的优势相结合，以生成高质量、有效且合理的文本反事实解释。

> Counterfactual explanations can be used to interpret and debug text classifiers by producing minimally altered text inputs that change a classifier's output. In this work, we evaluate five methods for generating counterfactual explanations for a BERT text classifier on two datasets using three evaluation metrics. The results of our experiments suggest that established white-box substitution-based methods are effective at generating valid counterfactuals that change the classifier's output. In contrast, newer methods based on large language models (LLMs) excel at producing natural and linguistically plausible text counterfactuals but often fail to generate valid counterfactuals that alter the classifier's output. Based on these results, we recommend developing new counterfactual explanation methods that combine the strengths of established gradient-based approaches and newer LLM-based techniques to generate high-quality, valid, and plausible text counterfactual explanations.

[Arxiv](https://arxiv.org/abs/2411.02643)