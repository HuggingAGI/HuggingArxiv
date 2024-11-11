# 多跳证据追踪遇见网络：FEVER 2024 中的 Papelo 团队

发布时间：2024年11月08日

`LLM应用` `信息验证`

> Multi-hop Evidence Pursuit Meets the Web: Team Papelo at FEVER 2024

# 摘要

> 在网络上区分虚假信息和事实长期以来一直挑战着人类的搜索和推理能力。我们表明，大型语言模型（LLM）的推理能力和现代搜索引擎的检索能力可以结合起来，使这个过程自动化，并对声明进行可解释的验证。我们在多跳证据追踪策略下整合了LLM和搜索。该策略使用序列到序列模型根据输入声明生成初始问题，搜索并制定问题的答案，并迭代生成后续问题，以使用LLM追踪缺失的证据。我们在FEVER 2024（AVeriTeC）共享任务上展示了我们的系统。与一次性生成所有问题的策略相比，我们的方法获得了0.045更高的标签准确率和0.155更高的AVeriTeC分数（评估证据的充分性）。通过消融实验，我们展示了各种设计选择的重要性，如问题生成方法、中型上下文、一次推理一个文档、添加元数据、改述、将问题简化为两类以及重新考虑最终裁决。我们提交的系统在开发集上获得了0.510的AVeriTeC分数，在测试集上获得了0.477的AVeriTeC分数。

> Separating disinformation from fact on the web has long challenged both the search and the reasoning powers of humans. We show that the reasoning power of large language models (LLMs) and the retrieval power of modern search engines can be combined to automate this process and explainably verify claims. We integrate LLMs and search under a multi-hop evidence pursuit strategy. This strategy generates an initial question based on an input claim using a sequence to sequence model, searches and formulates an answer to the question, and iteratively generates follow-up questions to pursue the evidence that is missing using an LLM. We demonstrate our system on the FEVER 2024 (AVeriTeC) shared task. Compared to a strategy of generating all the questions at once, our method obtains .045 higher label accuracy and .155 higher AVeriTeC score (evaluating the adequacy of the evidence). Through ablations, we show the importance of various design choices, such as the question generation method, medium-sized context, reasoning with one document at a time, adding metadata, paraphrasing, reducing the problem to two classes, and reconsidering the final verdict. Our submitted system achieves .510 AVeriTeC score on the dev set and .477 AVeriTeC score on the test set.

[Arxiv](https://arxiv.org/abs/2411.05762)