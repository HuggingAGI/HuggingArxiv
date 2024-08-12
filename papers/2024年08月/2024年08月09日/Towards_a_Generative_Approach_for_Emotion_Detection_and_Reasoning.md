# 探索情感检测与推理的生成途径

发布时间：2024年08月09日

`LLM应用` `情感分析` `人工智能`

> Towards a Generative Approach for Emotion Detection and Reasoning

# 摘要

> 大型语言模型 (LLM) 在数学和常识推理任务中通过链式思维 (CoT) 提示技术表现卓越。然而，我们探索了 LLM 是否能通过简单的 `让我们一步一步思考' 提示进行情感推理。为此，我们提出了一种新颖的零-shot 情感检测和推理方法，并批评了现有方法依赖固定标签的局限性。我们建议将情感分析视为生成式问答 (QA) 任务，通过两步法逐步生成相关上下文来解答情感问题。这是首次尝试使用生成方法联合解决情感检测和推理任务，我们在两个数据集上验证了方法，并提供了细粒度情感标签和解释，以促进情感推理系统的进一步训练和优化。

> Large language models (LLMs) have demonstrated impressive performance in mathematical and commonsense reasoning tasks using chain-of-thought (CoT) prompting techniques. But can they perform emotional reasoning by concatenating `Let's think step-by-step' to the input prompt? In this paper we investigate this question along with introducing a novel approach to zero-shot emotion detection and emotional reasoning using LLMs. Existing state of the art zero-shot approaches rely on textual entailment models to choose the most appropriate emotion label for an input text. We argue that this strongly restricts the model to a fixed set of labels which may not be suitable or sufficient for many applications where emotion analysis is required. Instead, we propose framing the problem of emotion analysis as a generative question-answering (QA) task. Our approach uses a two step methodology of generating relevant context or background knowledge to answer the emotion detection question step-by-step. Our paper is the first work on using a generative approach to jointly address the tasks of emotion detection and emotional reasoning for texts. We evaluate our approach on two popular emotion detection datasets and also release the fine-grained emotion labels and explanations for further training and fine-tuning of emotional reasoning systems.

[Arxiv](https://arxiv.org/abs/2408.04906)