# 大型语言模型能否媲美超级化学家？

发布时间：2024年04月01日

`LLM应用` `自动问答系统`

> Are large language models superhuman chemists?

# 摘要

> 大型语言模型（LLMs）因其在处理人类语言及未受专门训练的任务上表现出色而备受瞩目。在化学科学这一领域，面对数据集规模小、多样性大且多以文本形式呈现的挑战，LLMs展现出了解决问题的潜力，并日渐被用于预测化学特性、优化反应过程，甚至自动设计和实施实验。尽管如此，我们对LLMs的化学推理能力的认识仍然有限，而这些认识对于提升模型性能和降低潜在风险至关重要。本文介绍了“ChemBench”——一个旨在严格评估顶尖LLMs的化学知识和推理能力的自动化框架，与之相对照的是化学专家的专业水平。我们为化学科学的众多子领域精心准备了超过7,000组问答对，对主流的开源和闭源LLMs进行了评估，结果显示最佳模型在平均表现上超越了我们研究中的最佳人类化学家。然而，这些模型在一些对化学专家而言轻而易举的推理任务上却显得力不从心，有时还会提供过于自信且具有误导性的预测，比如对化学品安全档案的评估。这些发现揭示了一个双重事实：一方面，LLMs在化学任务上展现了非凡的才能；另一方面，为了提升它们在化学科学领域的安全性和实用性，深入研究迫在眉睫。我们的研究还指出了化学教育课程调整的必要性，并强调了持续完善评估框架，以促进LLMs在安全和有效性方面的进一步发展。

> Large language models (LLMs) have gained widespread interest due to their ability to process human language and perform tasks on which they have not been explicitly trained. This is relevant for the chemical sciences, which face the problem of small and diverse datasets that are frequently in the form of text. LLMs have shown promise in addressing these issues and are increasingly being harnessed to predict chemical properties, optimize reactions, and even design and conduct experiments autonomously. However, we still have only a very limited systematic understanding of the chemical reasoning capabilities of LLMs, which would be required to improve models and mitigate potential harms. Here, we introduce "ChemBench," an automated framework designed to rigorously evaluate the chemical knowledge and reasoning abilities of state-of-the-art LLMs against the expertise of human chemists. We curated more than 7,000 question-answer pairs for a wide array of subfields of the chemical sciences, evaluated leading open and closed-source LLMs, and found that the best models outperformed the best human chemists in our study on average. The models, however, struggle with some chemical reasoning tasks that are easy for human experts and provide overconfident, misleading predictions, such as about chemicals' safety profiles. These findings underscore the dual reality that, although LLMs demonstrate remarkable proficiency in chemical tasks, further research is critical to enhancing their safety and utility in chemical sciences. Our findings also indicate a need for adaptations to chemistry curricula and highlight the importance of continuing to develop evaluation frameworks to improve safe and useful LLMs.

[Arxiv](https://arxiv.org/abs/2404.01475)