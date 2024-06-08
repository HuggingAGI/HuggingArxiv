# 长期对话中因果感知的位置去偏差微调

发布时间：2024年06月04日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在对话系统中的应用，特别是在解决位置偏差问题和提高对话生成的质量方面。论文提出的因果感知长期对话框架（CPD）和相关的微调策略，旨在改善LLMs在处理对话历史时的性能，确保生成的响应既相关又信息丰富。这些内容直接关联到LLMs的具体应用，特别是在对话生成领域的改进，因此属于LLM应用分类。` `对话系统`

> Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue

# 摘要

> 对话系统的核心在于根据丰富的对话历史，生成既相关又信息丰富的人类化响应。近期，大型语言模型（LLMs）因其卓越的话语生成能力，已成为对话生成领域的主流选择。然而，这些模型固有的位置偏差问题不容忽视，它们往往更关注近邻语句而非因果相关的语句，导致长期对话中出现无关和泛化的响应。为解决这一问题，本文创新性地提出了因果感知长期对话框架（CPD），通过基于扰动的因果变量发现方法，从对话历史中精准提取因果相关语句，并在模型微调中强化其因果感知能力。CPD特别引入了局部位置感知机制，有效消除了句子间的位置相关性，助力模型依据扰动识别因果相关语句。同时，我们还设计了一种因果感知微调策略，通过差异化扰动因果与非因果相关语句，提升模型识别因果不变因素的能力，从而优化响应生成。实验结果显示，我们的方法在多个LLMs上有效缓解了位置偏差问题，并显著超越了现有基线水平。

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