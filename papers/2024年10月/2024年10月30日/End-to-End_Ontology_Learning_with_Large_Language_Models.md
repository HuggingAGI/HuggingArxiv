# 利用大型语言模型进行端到端的本体学习

发布时间：2024年10月30日

`LLM应用` `本体论`

> End-to-End Ontology Learning with Large Language Models

# 摘要

> 本体论以结构化的形式呈现领域知识，有助于机器对其进行自动处理。但构建本体论需要耗费大量人力。为实现部分流程的自动化，大型语言模型（LLMs）已被用于解决本体学习的各类子任务。然而，这种局部的本体学习未能捕捉到子任务间的相互作用。为此，我们引入了OLLM，这是一种通用且可扩展的方法，能够从零开始构建本体的分类架构。我们并非着眼于诸如实体间的个别关系等子任务，而是通过使用自定义正则化器微调LLM来对目标本体的整个子组件进行建模，该正则化器可减少对高频概念的过拟合。我们推出了一套新的指标，通过衡量生成的本体与真实情况在语义和结构上的相似度来评估其质量。与标准指标不同，我们的指标运用深度学习技术来定义更稳健的图间距离度量。我们在维基百科上的定量和定性结果均显示，OLLM优于子任务组合方法，生成的本体语义更准确，且结构完整。我们进一步证实，我们的模型能够有效适配新领域，如arXiv，仅需少量训练样本。我们的源代码和数据集可在https://github.com/andylolu2/ollm获取。

> Ontologies are useful for automatic machine processing of domain knowledge as they represent it in a structured format. Yet, constructing ontologies requires substantial manual effort. To automate part of this process, large language models (LLMs) have been applied to solve various subtasks of ontology learning. However, this partial ontology learning does not capture the interactions between subtasks. We address this gap by introducing OLLM, a general and scalable method for building the taxonomic backbone of an ontology from scratch. Rather than focusing on subtasks, like individual relations between entities, we model entire subcomponents of the target ontology by finetuning an LLM with a custom regulariser that reduces overfitting on high-frequency concepts. We introduce a novel suite of metrics for evaluating the quality of the generated ontology by measuring its semantic and structural similarity to the ground truth. In contrast to standard metrics, our metrics use deep learning techniques to define more robust distance measures between graphs. Both our quantitative and qualitative results on Wikipedia show that OLLM outperforms subtask composition methods, producing more semantically accurate ontologies while maintaining structural integrity. We further demonstrate that our model can be effectively adapted to new domains, like arXiv, needing only a small number of training examples. Our source code and datasets are available at https://github.com/andylolu2/ollm.

[Arxiv](https://arxiv.org/abs/2410.23584)