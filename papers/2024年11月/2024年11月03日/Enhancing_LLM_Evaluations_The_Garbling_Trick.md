# 提升 LLM 评估：乱序之法

发布时间：2024年11月03日

`LLM应用` `语言模型` `评估方法`

> Enhancing LLM Evaluations: The Garbling Trick

# 摘要

> 随着大型语言模型（LLMs）愈发强大，传统评估指标趋于饱和，依据性能区分模型变得困难重重。我们提出了一种通用办法，把现有的 LLM 评估转变成一系列难度渐增的任务。这些强化评估注重推理能力，能够揭示出原始评估中不显著的相对性能差异。
    为展示我们方法的成效，我们创建了一个新的多项选择测试语料库，将其拓展为一系列评估，并对一组 LLM 进行了评估。我们的结果为这些模型的比较推理能力提供了见解，尤其凸显了 OpenAI 的 o1-preview 与 Google 的 gemini-pro-1.5-002 之间的差别。

> As large language models (LLMs) become increasingly powerful, traditional evaluation metrics tend to saturate, making it challenging to distinguish between models based on their performance. We propose a general method to transform existing LLM evaluations into a series of progressively more difficult tasks. These enhanced evaluations emphasize reasoning capabilities and can reveal relative performance differences that are not apparent in the original assessments.
  To demonstrate the effectiveness of our approach, we create a new multiple-choice test corpus, extend it into a family of evaluations, and assess a collection of LLMs. Our results offer insights into the comparative reasoning abilities of these models, particularly highlighting distinctions between OpenAI's o1-preview and Google's gemini-pro-1.5-002.

[Arxiv](https://arxiv.org/abs/2411.01533)