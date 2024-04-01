# 大型语言模型能否为医生纠错？探究医学领域内的有效互动方式。

发布时间：2024年03月29日

`LLM应用` `决策支持系统`

> Can LLMs Correct Physicians, Yet? Investigating Effective Interaction Methods in the Medical Domain

# 摘要

> 本研究深入探讨了大型语言模型（LLMs）在辅助医生进行医疗决策方面的潜力，并可能纠正其决策。我们对Meditron、Llama2和Mistral等几款LLMs进行了评估，以检验它们在不同情境下与医生有效沟通的能力。任务类型多样，从简单的是非题到复杂的长答案生成，模型的答案均在与医生互动后形成。研究结果显示，提示的设计对LLMs的准确性有着重要影响，它们能够为医生提供宝贵的反馈，质疑错误的诊断，促进更精确的决策制定。例如，在医生正确率仅为38%的情况下，Mistral能够给出正确答案，借助恰当的提示，将正确率提升至74%。相较之下，Llama2和Meditron对提示的选择更为敏感。此外，我们还发现确保LLM提供的建议切实有用是一大挑战，这也凸显了未来研究在此领域的重要性。

> We explore the potential of Large Language Models (LLMs) to assist and potentially correct physicians in medical decision-making tasks. We evaluate several LLMs, including Meditron, Llama2, and Mistral, to analyze the ability of these models to interact effectively with physicians across different scenarios. We consider questions from PubMedQA and several tasks, ranging from binary (yes/no) responses to long answer generation, where the answer of the model is produced after an interaction with a physician. Our findings suggest that prompt design significantly influences the downstream accuracy of LLMs and that LLMs can provide valuable feedback to physicians, challenging incorrect diagnoses and contributing to more accurate decision-making. For example, when the physician is accurate 38% of the time, Mistral can produce the correct answer, improving accuracy up to 74% depending on the prompt being used, while Llama2 and Meditron models exhibit greater sensitivity to prompt choice. Our analysis also uncovers the challenges of ensuring that LLM-generated suggestions are pertinent and useful, emphasizing the need for further research in this area.

![大型语言模型能否为医生纠错？探究医学领域内的有效互动方式。](../../../paper_images/2403.20288/prompt_template.png)

[Arxiv](https://arxiv.org/abs/2403.20288)