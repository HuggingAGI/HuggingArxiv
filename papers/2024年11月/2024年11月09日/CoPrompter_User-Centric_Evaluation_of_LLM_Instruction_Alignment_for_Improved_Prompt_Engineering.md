# CoPrompter：以用户为中心对 LLM 指令对齐进行评估以改进提示工程

发布时间：2024年11月09日

`LLM应用` `语言模型` `提示工程`

> CoPrompter: User-Centric Evaluation of LLM Instruction Alignment for Improved Prompt Engineering

# 摘要

> 确保大型语言模型（LLM）的响应与提示指令一致对于应用开发至关重要。根据我们与行业专业人士的形成性研究，这种一致性需要大量的人力参与和繁琐的试错，尤其是当提示中有许多指令时。为了应对这些挑战，我们引入了 CoPrompter，这是一个基于使用标准评估多个 LLM 响应来识别不一致的框架。它提出了一种直接从提示要求中生成评估标准问题的方法，以及一个将这些问题转换为用户可编辑清单的界面。我们对行业提示工程师的用户研究表明，与传统方法相比，CoPrompter 提高了识别和完善与提示要求的指令一致性的能力，帮助他们了解模型在何处以及多频繁地未能遵循用户的提示要求，并有助于澄清他们自己的要求，使他们在响应评估过程中拥有更大的控制权。我们还介绍了设计经验教训，以强调我们的系统在简化提示工程流程方面的潜力。

> Ensuring large language models' (LLMs) responses align with prompt instructions is crucial for application development. Based on our formative study with industry professionals, the alignment requires heavy human involvement and tedious trial-and-error especially when there are many instructions in the prompt. To address these challenges, we introduce CoPrompter, a framework that identifies misalignment based on assessing multiple LLM responses with criteria. It proposes a method to generate evaluation criteria questions derived directly from prompt requirements and an interface to turn these questions into a user-editable checklist. Our user study with industry prompt engineers shows that CoPrompter improves the ability to identify and refine instruction alignment with prompt requirements over traditional methods, helps them understand where and how frequently models fail to follow user's prompt requirements, and helps in clarifying their own requirements, giving them greater control over the response evaluation process. We also present the design lessons to underscore our system's potential to streamline the prompt engineering process.

[Arxiv](https://arxiv.org/abs/2411.06099)