# 本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。

发布时间：2024年04月09日

`LLM理论` `隐私保护`

> Privacy Preserving Prompt Engineering: A Survey

# 摘要

> 预训练语言模型（PLMs）展现出了在处理众多通用自然语言处理（NLP）任务上的卓越能力。研究发现，模型性能与其规模大小直接相关。因此，近年来这些模型的规模急剧增长，研究人员开始用“大型语言模型（LLMs）”来指代这些大规模的PLMs。随着规模的扩大，出现了一种名为上下文学习（ICL）的特殊能力，它是一种专门的提示方式。这种方法通过向LLMs展示示例，使其能够处理特定的下游任务，而无需改变模型参数。尽管这一发现颇具吸引力，但隐私问题却成为了普及应用的一大阻碍。众多研究致力于探讨ICL和提示所带来的隐私风险，并提出了相应的缓解策略。本综述系统性地梳理了在ICL和提示过程中采用的隐私保护措施，并对比分析了不同的方法。同时，我们还汇总了开发这些框架的可用资源，并讨论了这些框架的局限性，以及需要进一步研究的有前景的领域。

> Pre-trained language models (PLMs) have demonstrated significant proficiency in solving a wide range of general natural language processing (NLP) tasks. Researchers have observed a direct correlation between the performance of these models and their sizes. As a result, the sizes of these models have notably expanded in recent years, persuading researchers to adopt the term large language models (LLMs) to characterize the larger-sized PLMs. The increased size is accompanied by a distinct capability known as in-context learning (ICL), which represents a specialized form of prompting. This enables the utilization of LLMs for specific downstream tasks by presenting them with demonstration examples while keeping the model parameters frozen. Although interesting, privacy concerns have become a major obstacle in its widespread usage. Multiple studies have examined the privacy risks linked to ICL and prompting in general, and have devised techniques to alleviate these risks. Thus, there is a necessity to organize these mitigation techniques for the benefit of the community. This survey provides a systematic overview of the privacy protection methods employed during ICL and prompting in general. We review, analyze, and compare different methods under this paradigm. Furthermore, we provide a summary of the resources accessible for the development of these frameworks. Finally, we discuss the limitations of these frameworks and offer a detailed examination of the promising areas that necessitate further exploration.

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x1.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x2.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x3.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x4.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x5.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x6.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x7.png)

![本调查研究了如何在保护隐私的前提下，通过提示工程技术提升大型语言模型的性能。](../../../paper_images/2404.06001/x8.png)

[Arxiv](https://arxiv.org/abs/2404.06001)