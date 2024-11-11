# 在一般指令微调中关于上下文感知的损失

发布时间：2024年11月04日

`LLM应用` `人工智能`

> On the loss of context-awareness in general instruction fine-tuning

# 摘要

> 预训练的大型语言模型（LLMs）需要诸如在指令-响应对上进行有监督的微调（SFT）之类的后训练方法来实现指令跟随。然而，这个过程可能会损害在预训练期间学到的现有能力。在本文中，我们研究了 SFT 后的上下文意识的损失，其定义为从用户提供的上下文中提取和理解信息并相应做出响应的能力。我们是第一个识别并表明，当聊天模板应用于输入提示时，在经过指令微调的 LLMs 上会出现上下文意识的损失。我们发现性能下降部分是由嵌入到聊天模板中的偏差引起的，该偏差较少关注用户提供的上下文。基于这些观察，我们提出了两种方法来减轻指令模型中上下文意识的损失：对用户提示的事后注意力引导和带有上下文依赖指标的条件指令微调。在 4 个上下文相关的下游任务和 3 个不同大小的预训练 LLMs 上的实证实验表明，我们的方法有效地减轻了上下文意识的损失，而不影响遵循指令的一般能力。我们的发现也强烈主张在指令微调后仔细对上下文意识进行基准测试的必要性。

> Pretrained Large Language Models (LLMs) require post-training methods such as supervised fine-tuning (SFT) on instruction-response pairs to enable instruction following. However, this process can potentially harm existing capabilities learned during pretraining. In this paper, we investigate the loss of context awareness after SFT, defined as the capability to extract and understand information from the user-provided context and respond accordingly. We are the first to identify and show that the loss of context-awareness appears on instruction-finetuned LLMs when the chat template is applied to the input prompts. We identify the performance decline is partially caused by the bias embedded into the chat template to focus less on the user-provided context. Based on these observations, we propose two methods to mitigate the loss of context awareness in instruct models: post-hoc attention steering on user prompts and conditional instruction fine-tuning with a context-dependency indicator. Empirical experiments on 4 context-dependent downstream tasks and 3 pretrained LLMs of different sizes show that our methods effectively mitigates the loss of context awareness without compromising the general ability to follow instructions. Our findings also strongly advocate the necessity to carefully benchmark context awareness after instruction fine-tuning.

[Arxiv](https://arxiv.org/abs/2411.02688)