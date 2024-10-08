# 通过 GL-等变处理低秩权重空间，提升大型微调模型的学习效果。

发布时间：2024年10月05日

`LLM理论` `机器学习` `人工智能`

> Learning on LoRAs: GL-Equivariant Processing of Low-Rank Weight Spaces for Large Finetuned Models

# 摘要

> 低秩适应 (LoRAs) 彻底改变了大型基础模型的微调，即使在资源有限的情况下也能高效适应。LoRAs 的广泛应用为机器学习技术带来了新机遇，尤其是那些以低秩权重为输入的技术。本文探讨了在 LoRAs 上学习 (LoL) 的潜力，即利用 LoRA 权重作为模型输入。例如，LoL 模型可以预测微调模型的下游任务性能，检测潜在有害的微调，甚至无需传统训练生成新模型。我们首先分析了权重低秩分解的固有对称性，这与标准神经网络有显著差异。为高效处理 LoRA 权重，我们开发了对称性感知的 LoL 模型，采用规范化、不变特征化和等变层等技术。通过微调数千个文本到图像扩散模型和语言模型，我们构建了 LoRAs 数据集。实验表明，我们的 LoL 架构能有效处理低秩权重，预测 CLIP 分数、微调数据属性及下游任务准确性。

> Low-rank adaptations (LoRAs) have revolutionized the finetuning of large foundation models, enabling efficient adaptation even with limited computational resources. The resulting proliferation of LoRAs presents exciting opportunities for applying machine learning techniques that take these low-rank weights themselves as inputs. In this paper, we investigate the potential of Learning on LoRAs (LoL), a paradigm where LoRA weights serve as input to machine learning models. For instance, an LoL model that takes in LoRA weights as inputs could predict the performance of the finetuned model on downstream tasks, detect potentially harmful finetunes, or even generate novel model edits without traditional training methods. We first identify the inherent parameter symmetries of low rank decompositions of weights, which differ significantly from the parameter symmetries of standard neural networks. To efficiently process LoRA weights, we develop several symmetry-aware invariant or equivariant LoL models, using tools such as canonicalization, invariant featurization, and equivariant layers. We finetune thousands of text-to-image diffusion models and language models to collect datasets of LoRAs. In numerical experiments on these datasets, we show that our LoL architectures are capable of processing low rank weight decompositions to predict CLIP score, finetuning data attributes, finetuning data membership, and accuracy on downstream tasks.

[Arxiv](https://arxiv.org/abs/2410.04207)