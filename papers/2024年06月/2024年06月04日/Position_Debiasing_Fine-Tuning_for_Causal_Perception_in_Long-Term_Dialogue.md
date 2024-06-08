# 长期对话中因果感知的位置去偏差微调

发布时间：2024年06月04日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在对话生成领域的应用，特别是在处理长期对话中的位置偏差问题。论文提出了一种新的框架（CPD），旨在通过因果感知的方法改进对话系统的性能。这种方法通过识别和强化对话历史中的因果相关语句，以及消除位置偏差，来提高模型的响应质量。因此，这篇论文属于LLM应用类别，因为它专注于改进和应用LLMs以解决实际的对话生成问题。` `对话系统`

> Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue

# 摘要

> 对话系统的核心在于根据丰富的对话历史，生成既相关又信息丰富的人类化响应。近期，大型语言模型（LLMs）因其卓越的话语生成能力，已成为对话生成领域的主流选择。然而，这些模型天然存在位置偏差，倾向于关注邻近语句而非因果相关的语句，导致长期对话中出现无关和泛化的响应。为此，本文创新性地提出了因果感知长期对话框架（CPD），通过基于扰动的因果变量发现方法，从对话历史中提取因果相关语句，并在模型微调中强化因果感知。CPD特别引入了一种局部位置感知机制，用以消除句子间的位置相关性，助力模型识别因果相关语句。同时，提出了一种因果感知微调策略，通过差异化扰动因果与非因果相关语句，提升模型识别因果不变因素的能力。实验结果显示，该方法能有效减少多个LLMs的位置偏差，并在性能上超越现有基线，取得显著进步。

> The core of the dialogue system is to generate relevant, informative, and human-like responses based on extensive dialogue history. Recently, dialogue generation domain has seen mainstream adoption of large language models (LLMs), due to its powerful capability in generating utterances. However, there is a natural deficiency for such models, that is, inherent position bias, which may lead them to pay more attention to the nearby utterances instead of causally relevant ones, resulting in generating irrelevant and generic responses in long-term dialogue. To alleviate such problem, in this paper, we propose a novel method, named Causal Perception long-term Dialogue framework (CPD), which employs perturbation-based causal variable discovery method to extract casually relevant utterances from the dialogue history and enhances model causal perception during fine-tuning. Specifically, a local-position awareness method is proposed in CPD for inter-sentence position correlation elimination, which helps models extract causally relevant utterances based on perturbations. Then, a casual-perception fine-tuning strategy is also proposed, to enhance the capability of discovering the causal invariant factors, by differently perturbing causally relevant and non-casually relevant ones for response generation. Experimental results on two datasets prove that our proposed method can effectively alleviate the position bias for multiple LLMs and achieve significant progress compared with existing baselines.

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/x1.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/x2.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/llama2_raw.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/llama2_finetune.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/llama2_finetune_no_pos.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/llama2_finetune_ours.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/model.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/multi_ppl.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/causal_dist.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/causal_num.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/qwen_raw.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/qwen_finetune.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/qwen_finetune_no_pos.png)

![长期对话中因果感知的位置去偏差微调](../../../paper_images/2406.02002/qwen_finetune_ours.png)

[Arxiv](https://arxiv.org/abs/2406.02002)