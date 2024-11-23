# 利用多智能体反射框架提升金融问题的回答能力

发布时间：2024年10月29日

`Agent` `问答系统`

> Enhancing Financial Question Answering with a Multi-Agent Reflection Framework

# 摘要

> 尽管大型语言模型（LLMs）在众多自然语言处理（NLP）任务中展现出强大能力，但在金融问答（QA）领域，尤其涉及数值推理时，仍面临挑战。近期，基于LLM的多智能体框架在多步推理方面成效显著，这对金融QA任务意义重大，因其需从表格和文本中提取相关信息，再对所提取数据进行数值推理以得出答案。本研究中，我们提出了一个融入评论智能体的多智能体框架，该智能体对每个问题的推理步骤和最终答案进行思考。此外，我们增添多个评论智能体以强化系统，每个智能体专注于答案的特定方面。结果显示，与单智能体推理相比，此框架显著提升性能，LLaMA3-8B模型平均性能提升15%，LLaMA3-70B模型平均提升5%。而且，我们的框架表现与LLaMA3.1-405B和GPT-4o-mini等更大的单智能体LLM相当，有时甚至更优，不过与Claude-3.5 Sonnet相比稍逊一筹。总之，我们的框架为强化用于金融QA任务的开源LLM提供了有效方案，是Claude-3.5 Sonnet等大型模型的高性价比替代选择。

> While Large Language Models (LLMs) have shown impressive capabilities in numerous Natural Language Processing (NLP) tasks, they still struggle with financial question answering (QA), particularly when numerical reasoning is required. Recently, LLM-based multi-agent frameworks have demonstrated remarkable effectiveness in multi-step reasoning, which is crucial for financial QA tasks as it involves extracting relevant information from tables and text and then performing numerical reasoning on the extracted data to infer answers. In this study, we propose a multi-agent framework incorporating a critic agent that reflects on the reasoning steps and final answers for each question. Additionally, we enhance our system by adding multiple critic agents, each focusing on a specific aspect of the answer. Our results indicate that this framework significantly improves performance compared to single-agent reasoning, with an average performance increase of 15% for the LLaMA3-8B model and 5% for the LLaMA3-70B model. Furthermore, our framework performs on par with, and in some cases surpasses, larger single-agent LLMs such as LLaMA3.1-405B and GPT-4o-mini, though it falls slightly short compared to Claude-3.5 Sonnet. Overall, our framework presents an effective solution to enhance open-source LLMs for financial QA tasks, offering a cost-effective alternative to larger models like Claude-3.5 Sonnet.

[Arxiv](https://arxiv.org/abs/2410.21741)