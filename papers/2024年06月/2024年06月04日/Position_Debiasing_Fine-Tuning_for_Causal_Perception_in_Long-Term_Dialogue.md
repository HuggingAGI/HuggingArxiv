# 长期对话中因果感知的位置去偏差微调

发布时间：2024年06月04日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）在对话系统中的应用，特别是在处理长期对话时如何减少位置偏差，提高回复的相关性和信息丰富性。论文提出了一种名为因果感知长期对话框架（CPD）的新方法，该方法通过引入局部位置感知机制和因果感知微调策略，旨在增强模型对因果相关语句的识别能力，并减少位置偏差。这种方法可以被视为一种智能代理（Agent）的行为，因为它涉及到对模型行为的调整和优化，以更好地适应和响应对话环境。因此，这篇论文更适合归类于Agent分类。` `对话系统`

> Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue

# 摘要

> 对话系统的核心在于根据丰富的对话历史，生成既相关又信息丰富且类似人类的回复。近期，大型语言模型（LLMs）因其卓越的话语生成能力，已成为对话生成领域的主流选择。然而，这些模型固有的位置偏差问题，可能导致它们过度关注近邻语句，而忽视了真正因果相关的信息，导致长期对话中出现无关和泛化的回复。为此，本文提出了一种创新方法——因果感知长期对话框架（CPD），它通过基于扰动的因果变量发现技术，从对话历史中提取因果相关语句，并在模型微调阶段增强其因果感知能力。CPD中特别引入了一种局部位置感知机制，用以消除句子间的位置相关性，帮助模型更准确地识别因果相关语句。同时，我们还设计了一种因果感知微调策略，通过差异化处理因果相关与非因果相关的语句，提升模型识别因果不变因素的能力。实验结果显示，我们的方法能有效减少多个LLMs的位置偏差，并在性能上显著超越现有基线。

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