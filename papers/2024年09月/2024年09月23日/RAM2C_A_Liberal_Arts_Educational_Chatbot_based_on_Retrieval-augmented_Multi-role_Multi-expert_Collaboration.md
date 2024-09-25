# RAM2C：一款结合检索增强技术，实现多角色与多专家协作的文科教育聊天机器人

发布时间：2024年09月23日

`RAG` `人工智能`

> RAM2C: A Liberal Arts Educational Chatbot based on Retrieval-augmented Multi-role Multi-expert Collaboration

# 摘要

> 近期，众多研究致力于将大型语言模型 (LLM) 融入教育对话，特别是在文科领域，教育者需在专业知识外，兼顾人性化沟通、教学专长与安全伦理 (\textbf{HTS})。然而，由于收集大量符合 HTS 标准的真实教学对话成本高昂，现有 LLM 在教学对话中的表现仍未达人类标准。为此，我们设计了检索增强的多角色多专家协作 (RAM2C) 框架，自动生成此类对话数据。首先，我们构建了涵盖教学技能、心理学及安全伦理的 HTS 引导知识库。随后，RAM2C 将通过不同知识库增强检索能力的 LLM 组织成多专家小组，生成符合 HTS 标准的教育对话数据集，并对其进行微调。实证评估显示，RM2C 赋能的 LLM 在中文阅读教学中表现卓越，提供更个性化且伦理安全的教学响应，彰显了 RAM2C 的实用价值与高质量。实验已在 \hyperlink{https://github.com/ram2c/ram2c}{https://github.com/ram2c/ram2c} 发布。

> Recently, many studies focus on utilizing large language models (LLMs) into educational dialogues. Especially, within liberal arts dialogues, educators must balance \textbf{H}umanized communication, \textbf{T}eaching expertise, and \textbf{S}afety-ethics (\textbf{HTS}), besides the subject knowledge itself. However, due to collecting massive amounts of HTS-compliant teaching dialogues from real world as training corpus is expensive, the outputs of existing LLMs in teaching dialogues fall short of human standards. To address this, we design a Retrieval-augmented Multi-role Multi-expert Collaboration (RAM2C) framework to automatically generate such dialogues data. Specifically, we first establish HTS-guided knowledge bases, encompassing three domain knowledge in teaching skills, psychology, and safety ethics. Then, RAM2C organizes LLMs, which are retrieval-augmented by the above different knowledge bases, into multi-experts groups with distinct roles to generate the HTS-compliant educational dialogues dataset. We then fine-tuned the LLMs using this dataset. Empirical evaluations indicate that RM2C-empowered LLMs excel in Chinese reading teaching, offering more personalized, and ethically safe teaching response, demonstrating RAM2C's practicality and high quality. We release the experiments at \hyperlink{https://github.com/ram2c/ram2c}{https://github.com/ram2c/ram2c}.

[Arxiv](https://arxiv.org/abs/2409.15461)