# 对话蕴含任务的对抗性攻击与防御策略

发布时间：2024年04月30日

`LLM应用` `对话系统`

> Adversarial Attacks and Defense for Conversation Entailment Task

# 摘要

> 大型语言模型（LLMs）在多种自然语言处理（NLP）任务上展现出强大能力，但它们也面临着低成本攻击的威胁。如何加固这些模型，提升其防御能力，成为了一个亟待解决的问题。本研究将对抗性攻击视为模型面对的一个新领域，并围绕如何增强模型在这一新领域的鲁棒性展开探讨。我们着眼于对话蕴含任务，即以多轮自然语言对话为前提，通过微调变换模型来预测关于对话的给定假设是否成立。攻击者会尝试对假设进行篡改，误导模型做出错误判断。我们采用同义词替换作为攻击手段。为了增强模型的鲁棒性，我们实施了若干微调策略，并引入了嵌入扰动损失方法。最终，我们通过分析自然语言处理领域中的真实对抗性攻击案例，强调了本研究的重要性和实用价值。

> Large language models (LLMs) that are proved to be very powerful on different NLP tasks. However, there are still many ways to attack the model with very low costs. How to defend the model becomes an important problem. In our work, we treat adversarial attack results as a new (unseen) domain of the model, and we frame the defending problem into how to improve the robustness of the model on the new domain. We focus on the task of conversation entailment, where multi-turn natural language dialogues are the premise, and the transformer model is fine-tuned to predict whether a given hypothesis about the given dialogue is true or false. The adversary would attack the hypothesis to fool the model to make the wrong predictions. We apply synonym-swapping as the attack method. To show the robustness of the model, we implement some fine-tuning strategies and propose the embedding perturbation loss as a method to improve the robustness of the model. Finally, we show the importance of our work by discussing the adversarial attacks in NLP in the real world.

[Arxiv](https://arxiv.org/abs/2405.00289)