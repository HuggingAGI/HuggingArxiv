# GOLD：一款能够理解自然语言描述来解决几何问题的智能求解器。

发布时间：2024年05月01日

`LLM应用` `AI自动化` `数学教育`

> GOLD: Geometry Problem Solver with Natural Language Description

# 摘要

> 面对AI领域自动化几何数学问题求解的挑战，关键在于理解多模态信息与数学概念。现有技术在精确解读几何图形方面力有未逮，这限制了问题解决的效率。为此，我们引入了一种名为GOLD（Geometry problem sOlver with natural Language Description）的模型。GOLD通过区分处理图形中的符号和几何元素，优化了几何关系的识别。然后，它将这些关系转化为自然语言描述，并借助大型语言模型高效解决几何数学问题。在UniGeo数据集上的实验结果显示，GOLD模型在计算和证明任务的准确度上分别比前最佳方法Geoformer模型提升了12.7%和42.1%。同时，在PGPS9K和Geometry3K数据集上，GOLD模型也超越了PGPSNet模型，准确度分别提升了1.8%和3.2%。

> Addressing the challenge of automated geometry math problem-solving in artificial intelligence (AI) involves understanding multi-modal information and mathematics. Current methods struggle with accurately interpreting geometry diagrams, which hinders effective problem-solving. To tackle this issue, we present the Geometry problem sOlver with natural Language Description (GOLD) model. GOLD enhances the extraction of geometric relations by separately processing symbols and geometric primitives within the diagram. Subsequently, it converts the extracted relations into natural language descriptions, efficiently utilizing large language models to solve geometry math problems. Experiments show that the GOLD model outperforms the Geoformer model, the previous best method on the UniGeo dataset, by achieving accuracy improvements of 12.7% and 42.1% in calculation and proving subsets. Additionally, it surpasses the former best model on the PGPS9K and Geometry3K datasets, PGPSNet, by obtaining accuracy enhancements of 1.8% and 3.2%, respectively.

[Arxiv](https://arxiv.org/abs/2405.00494)