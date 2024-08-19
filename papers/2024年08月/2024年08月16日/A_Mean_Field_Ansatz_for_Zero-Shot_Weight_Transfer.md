# 零-shot 权重转移的平均场近似法

发布时间：2024年08月16日

`LLM理论` `人工智能` `计算机科学`

> A Mean Field Ansatz for Zero-Shot Weight Transfer

# 摘要

> 大型语言模型的预训练成本高昂，而零-shot 权重转移作为一种前沿方法，能将小模型的权重神奇地转移到大型模型中，从而降低成本。本文受平均场理论启发，提出平均场观点下的行-列假设，为权重转移提供理论解释。我们通过实验验证了这一假设，并证明在适当条件下，平均场观点能为零-shot 权重转移提供坚实的理论支持。

> The pre-training cost of large language models (LLMs) is prohibitive. One cutting-edge approach to reduce the cost is zero-shot weight transfer, also known as model growth for some cases, which magically transfers the weights trained in a small model to a large model. However, there are still some theoretical mysteries behind the weight transfer. In this paper, inspired by prior applications of mean field theory to neural network dynamics, we introduce a mean field ansatz to provide a theoretical explanation for weight transfer. Specifically, we propose the row-column (RC) ansatz under the mean field point of view, which describes the measure structure of the weights in the neural network (NN) and admits a close measure dynamic. Thus, the weights of different sizes NN admit a common distribution under proper assumptions, and weight transfer methods can be viewed as sampling methods. We empirically validate the RC ansatz by exploring simple MLP examples and LLMs such as GPT-3 and Llama-3.1. We show the mean-field point of view is adequate under suitable assumptions which can provide theoretical support for zero-shot weight transfer.

[Arxiv](https://arxiv.org/abs/2408.08681)