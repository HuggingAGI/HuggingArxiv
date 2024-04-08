# 大型语言模型充当领域专业知识本体的即插即用式智能顾问。

发布时间：2024年04月05日

`LLM应用` `语义数据` `本体论构建`

> Large language models as oracles for instantiating ontologies with domain-specific knowledge

# 摘要

> 背景介绍。为智能系统注入语义数据，通常需要专家设计并构建含有特定领域知识的本体论。这个过程在初期阶段大多是手工完成的，专家们可能会依赖个人经验。这样的做法既费时又容易出错，且往往受到设计者个人背景的影响。我们的目标是解决这一问题。为此，我们提出了一种新颖的、与领域无关的方法，通过使用大型语言模型（LLMs）作为决策辅助工具，自动构建含有特定领域知识的本体论。研究方法。我们从一个包含相互关联的类别和属性的初始架构（i）和一组查询模板（ii）出发，通过多次向LLM发起查询，根据其反馈为类别和属性生成实例。这样，本体论便自动填充了与初始架构相符的特定领域知识。最终，本体论迅速自动地得到了丰富的实例，专家们可以根据自己的需求和专业知识决定保留、调整、舍弃或补充这些实例。我们的研究贡献在于，我们将这种方法进行了一般性的规范化，并在多个LLMs上进行了实例化，以及在一个具体的案例研究中得到应用。我们在一个营养领域的实验中报告了结果，其中从餐点分类及其相互关系出发，半自动地构建了一个关于食物餐点和成分的本体论。我们分析了生成的本体论的质量，并比较了利用不同LLMs得到的结果。最后，我们对所提出的方法进行了SWOT分析。

> Background. Endowing intelligent systems with semantic data commonly requires designing and instantiating ontologies with domain-specific knowledge. Especially in the early phases, those activities are typically performed manually by human experts possibly leveraging on their own experience. The resulting process is therefore time-consuming, error-prone, and often biased by the personal background of the ontology designer. Objective. To mitigate that issue, we propose a novel domain-independent approach to automatically instantiate ontologies with domain-specific knowledge, by leveraging on large language models (LLMs) as oracles. Method. Starting from (i) an initial schema composed by inter-related classes andproperties and (ii) a set of query templates, our method queries the LLM multi- ple times, and generates instances for both classes and properties from its replies. Thus, the ontology is automatically filled with domain-specific knowledge, compliant to the initial schema. As a result, the ontology is quickly and automatically enriched with manifold instances, which experts may consider to keep, adjust, discard, or complement according to their own needs and expertise. Contribution. We formalise our method in general way and instantiate it over various LLMs, as well as on a concrete case study. We report experiments rooted in the nutritional domain where an ontology of food meals and their ingredients is semi-automatically instantiated from scratch, starting from a categorisation of meals and their relationships. There, we analyse the quality of the generated ontologies and compare ontologies attained by exploiting different LLMs. Finally, we provide a SWOT analysis of the proposed method.

![大型语言模型充当领域专业知识本体的即插即用式智能顾问。](../../../paper_images/2404.04108/x1.png)

![大型语言模型充当领域专业知识本体的即插即用式智能顾问。](../../../paper_images/2404.04108/x2.png)

[Arxiv](https://arxiv.org/abs/2404.04108)