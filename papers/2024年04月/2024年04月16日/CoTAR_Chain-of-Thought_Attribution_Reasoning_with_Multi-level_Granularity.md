# CoTAR：采用多级细节的思考路径归因分析

发布时间：2024年04月16日

`LLM应用` `问答系统` `人工智能`

> CoTAR: Chain-of-Thought Attribution Reasoning with Multi-level Granularity

# 摘要

> 在问答任务上，应用大型语言模型（LLMs）的系统正引领着最先进的技术水平，但这些模型有时会在回答中捏造信息。为了解决这一问题，一种新兴的方法通过将输入到输出的归因整合进生成过程中，来提升回答的质量。然而，要找到恰当的归因并验证其准确性，仍是一个充满挑战的复杂过程，亟需对这类系统的评估机制进行改进。我们提出了一种以归因为核心的“思维链”推理新方法，旨在提升归因的精确度。通过在两个增强上下文的问答数据集上应用GPT-4进行测试，我们的方法是归因的准确度和正确性得到了提升。此外，将此方法与微调相结合，还能进一步提高两个规模较小的LLMs的性能，使其在某些情形下有望超越GPT-4。

> State-of-the-art performance in QA tasks is currently achieved by systems employing Large Language Models (LLMs), however these models tend to hallucinate information in their responses. One approach focuses on enhancing the generation process by incorporating attribution from the given input to the output. However, the challenge of identifying appropriate attributions and verifying their accuracy against a source is a complex task that requires significant improvements in assessing such systems. We introduce an attribution-oriented Chain-of-Thought reasoning method to enhance the accuracy of attributions. This approach focuses the reasoning process on generating an attribution-centric output. Evaluations on two context-enhanced question-answering datasets using GPT-4 demonstrate improved accuracy and correctness of attributions. In addition, the combination of our method with finetuning enhances the response and attribution accuracy of two smaller LLMs, showing their potential to outperform GPT-4 in some cases.

![CoTAR：采用多级细节的思考路径归因分析](../../../paper_images/2404.10513/x1.png)

[Arxiv](https://arxiv.org/abs/2404.10513)