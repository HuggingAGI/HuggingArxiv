# 探究大型语言模型中的关键神经元

发布时间：2024年06月16日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）内部知识的定位和编辑问题，特别是如何在现代自回归LLMs中有效定位相关神经元，并解决长篇文本生成的难题。研究提出了一个新的框架（NA-ICA），并通过创建跨领域和语言的多选QA数据集来验证其有效性。此外，论文还分析了神经元分布，揭示了领域内明显的局部知识区域，并展示了这些关键神经元在知识编辑和预测中的应用潜力。这些内容更偏向于LLM的理论研究，因此归类为LLM理论。`

> Analyzing Key Neurons in Large Language Models

# 摘要

> 大型语言模型（LLMs）内含丰富知识，激发了研究者探索如何定位和编辑这些知识的方法。以往研究多聚焦于小型语言模型中的填空任务和实体相关信息的定位。但关键问题依旧悬而未决：如何在如LLaMA和Mistral等现代自回归LLMs中有效定位相关神经元？如何解决长篇文本生成的难题？LLMs中是否存在知识局部化区域？本研究提出了一种名为神经元归属-逆向聚类归属（NA-ICA）的新框架，它能识别LLMs中的关键神经元，并通过多选题回答任务来分析长篇答案。我们创建了跨领域和语言的多选QA数据集，以验证NA-ICA的有效性，结果显示其性能显著超越基线方法。神经元分布分析揭示了领域内明显的局部知识区域。最后，我们展示了这些关键神经元在知识编辑和预测中的应用潜力。

> Large Language Models (LLMs) possess vast amounts of knowledge within their parameters, prompting research into methods for locating and editing this knowledge. Previous investigations have primarily focused on fill-in-the-blank tasks and locating entity-related usually single-token facts) information in relatively small-scale language models. However, several key questions remain unanswered: (1) How can we effectively locate query-relevant neurons in contemporary autoregressive LLMs, such as LLaMA and Mistral? (2) How can we address the challenge of long-form text generation? (3) Are there localized knowledge regions in LLMs? In this study, we introduce Neuron Attribution-Inverse Cluster Attribution (NA-ICA), a novel architecture-agnostic framework capable of identifying key neurons in LLMs. NA-ICA allows for the examination of long-form answers beyond single tokens by employing the proxy task of multi-choice question answering. To evaluate the effectiveness of our detected key neurons, we construct two multi-choice QA datasets spanning diverse domains and languages. Empirical evaluations demonstrate that NA-ICA outperforms baseline methods significantly. Moreover, analysis of neuron distributions reveals the presence of visible localized regions, particularly within different domains. Finally, we demonstrate the potential applications of our detected key neurons in knowledge editing and neuron-based prediction.

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x1.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x2.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x3.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x4.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x5.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x6.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x7.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x8.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x9.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/embeddings_visualisation_full.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x10.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x11.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x12.png)

![探究大型语言模型中的关键神经元](../../../paper_images/2406.10868/x13.png)

[Arxiv](https://arxiv.org/abs/2406.10868)