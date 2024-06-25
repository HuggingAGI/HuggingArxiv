# 大型语言模型展现出零-shot推理能力

发布时间：2023年01月29日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在零样本推理任务中的潜力，特别是通过思维链（CoT）提示技术。研究展示了如何通过简单的提示，如在答案前加上“让我们一步一步思考”，可以显著提高LLMs在多种推理任务中的性能，无需任何手工少量示例。这种方法在多个任务中超越了传统的零样本性能，显示了LLMs潜在的高级认知能力。这项研究不仅为挑战性推理任务提供了一个强有力的零样本基准，也强调了深入探索和分析LLMs中隐藏的零样本知识的重要性。因此，这篇论文属于LLM理论分类，因为它深入探讨了LLMs的内在能力和潜在的认知机制。` `人工智能`

> Large Language Models are Zero-Shot Reasoners

# 摘要

> 预训练的大型语言模型（LLMs）在自然语言处理（NLP）的多个领域中表现出色，尤其擅长通过特定任务示例进行少量学习。最近，思维链（CoT）提示技术通过逐步答案示例引导复杂推理，在算术和符号推理等系统2任务中取得了顶尖成果，这些任务通常不遵循LLMs的标准缩放规律。尽管这些成就常归功于LLMs的少量学习能力，我们发现只需在答案前加上“让我们一步一步思考”，LLMs就能成为出色的零样本推理者。实验证明，我们的零样本-CoT方法，使用单一提示模板，在多种推理任务中大幅超越了零样本LLM性能，无需任何手工少量示例，例如在MultiArith和GSM8K任务中，准确率分别从17.7%和10.4%提升至78.7%和40.7%，使用大型InstructGPT模型（text-davinci-002），以及使用540B参数的PaLM模型也实现了类似幅度的提升。这一单一提示在多样推理任务中的广泛适用性，揭示了LLMs潜在的零样本能力，暗示通过简单提示可能激发高级、多任务的认知能力。我们希望这项研究不仅为挑战性推理任务提供了一个强有力的零样本基准，也强调了在制作微调数据集或少量示例之前，深入探索和分析LLMs中隐藏的零样本知识的重要性。

> Pretrained large language models (LLMs) are widely used in many sub-fields of natural language processing (NLP) and generally known as excellent few-shot learners with task-specific exemplars. Notably, chain of thought (CoT) prompting, a recent technique for eliciting complex multi-step reasoning through step-by-step answer examples, achieved the state-of-the-art performances in arithmetics and symbolic reasoning, difficult system-2 tasks that do not follow the standard scaling laws for LLMs. While these successes are often attributed to LLMs' ability for few-shot learning, we show that LLMs are decent zero-shot reasoners by simply adding "Let's think step by step" before each answer. Experimental results demonstrate that our Zero-shot-CoT, using the same single prompt template, significantly outperforms zero-shot LLM performances on diverse benchmark reasoning tasks including arithmetics (MultiArith, GSM8K, AQUA-RAT, SVAMP), symbolic reasoning (Last Letter, Coin Flip), and other logical reasoning tasks (Date Understanding, Tracking Shuffled Objects), without any hand-crafted few-shot examples, e.g. increasing the accuracy on MultiArith from 17.7% to 78.7% and GSM8K from 10.4% to 40.7% with large InstructGPT model (text-davinci-002), as well as similar magnitudes of improvements with another off-the-shelf large model, 540B parameter PaLM. The versatility of this single prompt across very diverse reasoning tasks hints at untapped and understudied fundamental zero-shot capabilities of LLMs, suggesting high-level, multi-task broad cognitive capabilities may be extracted by simple prompting. We hope our work not only serves as the minimal strongest zero-shot baseline for the challenging reasoning benchmarks, but also highlights the importance of carefully exploring and analyzing the enormous zero-shot knowledge hidden inside LLMs before crafting finetuning datasets or few-shot exemplars.

[Arxiv](https://arxiv.org/abs/2205.11916)