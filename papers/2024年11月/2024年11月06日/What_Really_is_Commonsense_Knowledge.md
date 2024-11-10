# 什么才是真正的常识知识？

发布时间：2024年11月06日

`LLM应用` `常识推理`

> What Really is Commonsense Knowledge?

# 摘要

> 常识数据集在自然语言处理中已经得到了很好的发展，主要通过众包人工标注。然而，关于常识推理基准的真实性存在争议。具体来说，一些常识基准中的很大一部分实例与常识知识无关。这个问题会削弱对被评估模型真正的常识推理能力的衡量。也有人认为，这个问题源于常识知识与其他类型知识相区别的概念模糊。为了揭开上述所有说法的神秘面纱，在本研究中，我们调查了常识知识的现有定义，深入研究了定义概念的三个框架，并将它们整合成一个多框架统一的常识知识定义（所谓的综合定义）。然后，我们使用综合定义对 CommonsenseQA 和 CommonsenseQA 2.0 数据集进行标注和实验，以检验上述说法。我们的研究表明，在这两个数据集中存在很大一部分非常识知识实例，并且在这两个子集上存在很大的性能差距，大型语言模型（LLM）在常识知识实例上表现更差。

> Commonsense datasets have been well developed in Natural Language Processing, mainly through crowdsource human annotation. However, there are debates on the genuineness of commonsense reasoning benchmarks. In specific, a significant portion of instances in some commonsense benchmarks do not concern commonsense knowledge. That problem would undermine the measurement of the true commonsense reasoning ability of evaluated models. It is also suggested that the problem originated from a blurry concept of commonsense knowledge, as distinguished from other types of knowledge. To demystify all of the above claims, in this study, we survey existing definitions of commonsense knowledge, ground into the three frameworks for defining concepts, and consolidate them into a multi-framework unified definition of commonsense knowledge (so-called consolidated definition). We then use the consolidated definition for annotations and experiments on the CommonsenseQA and CommonsenseQA 2.0 datasets to examine the above claims. Our study shows that there exists a large portion of non-commonsense-knowledge instances in the two datasets, and a large performance gap on these two subsets where Large Language Models (LLMs) perform worse on commonsense-knowledge instances.

[Arxiv](https://arxiv.org/abs/2411.03964)