# 精神分裂症聊天机器人的提示工程：通过多代理方法提升对提示指令的遵守效果

发布时间：2024年10月10日

`LLM应用` `心理健康`

> Prompt Engineering a Schizophrenia Chatbot: Utilizing a Multi-Agent Approach for Enhanced Compliance with Prompt Instructions

# 摘要

> 精神分裂症患者常因认知障碍而难以了解自身病情。利用GPT-4等大型语言模型（LLMs）的教育平台，能极大帮助这些患者。尽管LLMs能让心理健康信息更易获取和吸引人，但其黑箱特性引发伦理和安全担忧。提示技术虽能生成基于指令和验证信息的聊天机器人，但对话中可能偏离预期身份。为此，我们提出关键分析过滤器，通过提示工程的LLM代理，批判性分析和优化聊天机器人响应，并实时反馈。我们开发了精神分裂症信息聊天机器人，未激活过滤器时对话，直到其超出范围。AI代理生成越界话题的样本对话，手动分配合规分数，量化其指令遵守程度。激活过滤器后，67.0%响应合规分数达到可接受水平（>=2），未激活时仅8.7%。这表明，自我反思层能让LLMs在心理健康平台上安全有效使用，保持适应性，并限制在适当用例中。

> Patients with schizophrenia often present with cognitive impairments that may hinder their ability to learn about their condition. These individuals could benefit greatly from education platforms that leverage the adaptability of Large Language Models (LLMs) such as GPT-4. While LLMs have the potential to make topical mental health information more accessible and engaging, their black-box nature raises concerns about ethics and safety. Prompting offers a way to produce semi-scripted chatbots with responses anchored in instructions and validated information, but prompt-engineered chatbots may drift from their intended identity as the conversation progresses. We propose a Critical Analysis Filter for achieving better control over chatbot behavior. In this system, a team of prompted LLM agents are prompt-engineered to critically analyze and refine the chatbot's response and deliver real-time feedback to the chatbot. To test this approach, we develop an informational schizophrenia chatbot and converse with it (with the filter deactivated) until it oversteps its scope. Once drift has been observed, AI-agents are used to automatically generate sample conversations in which the chatbot is being enticed to talk about out-of-bounds topics. We manually assign to each response a compliance score that quantifies the chatbot's compliance to its instructions; specifically the rules about accurately conveying sources and being transparent about limitations. Activating the Critical Analysis Filter resulted in an acceptable compliance score (>=2) in 67.0% of responses, compared to only 8.7% when the filter was deactivated. These results suggest that a self-reflection layer could enable LLMs to be used effectively and safely in mental health platforms, maintaining adaptability while reliably limiting their scope to appropriate use cases.

[Arxiv](https://arxiv.org/abs/2410.12848)