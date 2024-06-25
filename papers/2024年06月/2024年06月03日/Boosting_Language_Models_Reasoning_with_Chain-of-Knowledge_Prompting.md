# 借助知识链提示，增强语言模型的推理能力

发布时间：2024年06月03日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在复杂推理任务中的应用，并提出了一种新的提示方法——知识链（CoK）提示，以及一种验证方法F^2-Verification。这些研究内容涉及LLMs的理论和方法改进，旨在提高模型的推理能力和准确性，因此属于LLM理论分类。` `人工智能`

> Boosting Language Models Reasoning with Chain-of-Knowledge Prompting

# 摘要

> 思维链（CoT）提示近期在复杂推理任务中大放异彩，通过“让我们一步步思考”等简单提示或精心设计理由的上下文示例，引导大型语言模型（LLMs）展现中间推理步骤。但这些推理链常因错误理由而失真。为此，我们创新提出知识链（CoK）提示，旨在让LLMs以结构三元组形式输出明确知识证据，灵感源自人类在解答难题前构建的思维图。结合CoK，我们开发了F^2-Verification方法，评估并确保推理链的真实与忠实。对于有误的推理，该方法能指出错误证据，促使LLM重新审视。实验证明，我们的方法在提升常识、事实、符号及算术推理任务性能上卓有成效。

> Recently, Chain-of-Thought (CoT) prompting has delivered success on complex reasoning tasks, which aims at designing a simple prompt like ``Let's think step by step'' or multiple in-context exemplars with well-designed rationales to elicit Large Language Models (LLMs) to generate intermediate reasoning steps. However, the generated rationales often come with mistakes, making unfactual and unfaithful reasoning chains. To mitigate this brittleness, we propose a novel Chain-of-Knowledge (CoK) prompting, where we aim at eliciting LLMs to generate explicit pieces of knowledge evidence in the form of structure triple. This is inspired by our human behaviors, i.e., we can draw a mind map or knowledge map as the reasoning evidence in the brain before answering a complex question. Benefiting from CoK, we additionally introduce a F^2-Verification method to estimate the reliability of the reasoning chains in terms of factuality and faithfulness. For the unreliable response, the wrong evidence can be indicated to prompt the LLM to rethink. Extensive experiments demonstrate that our method can further improve the performance of commonsense, factual, symbolic, and arithmetic reasoning tasks.

[Arxiv](https://arxiv.org/abs/2306.06427)