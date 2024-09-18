# 大型语言模型的提示混淆技术

发布时间：2024年09月17日

`LLM应用` `知识产权保护` `网络安全`

> Prompt Obfuscation for Large Language Models

# 摘要

> 系统提示包含详细指令，描述了底层大型语言模型（LLM）的任务，能轻松将基础模型转化为工具和服务，且开销极低。因其对实用性的关键影响，常被视为知识产权，如同软件代码。然而，通过提示注入，提取系统提示易如反掌。至今，尚无有效对策防止系统提示被盗，所有保护措施均可被精心设计的提示注入绕过。为此，我们提出替代传统系统提示的新方法——提示混淆。通过混淆，我们既能防止提示被提取，又仅以微小开销维持系统功能。核心在于找到一种表示，使混淆后的提示与原始提示功能相同，但无法从中推断出原始信息。我们采用基于优化的方法实现这一目标。为评估效果，我们对比了原始与混淆提示下的系统性能，结果显示混淆版本始终与原始版本相当。此外，我们进行了三种去混淆攻击，证明即使掌握混淆提示和LLM，也无法稳定提取有用信息。综上所述，提示混淆是一种有效保护知识产权、同时保持原始提示实用性的方法。

> System prompts that include detailed instructions to describe the task performed by the underlying large language model (LLM) can easily transform foundation models into tools and services with minimal overhead. Because of their crucial impact on the utility, they are often considered intellectual property, similar to the code of a software product. However, extracting system prompts is easily possible by using prompt injection. As of today, there is no effective countermeasure to prevent the stealing of system prompts and all safeguarding efforts could be evaded with carefully crafted prompt injections that bypass all protection mechanisms.In this work, we propose an alternative to conventional system prompts. We introduce prompt obfuscation to prevent the extraction of the system prompt while maintaining the utility of the system itself with only little overhead. The core idea is to find a representation of the original system prompt that leads to the same functionality, while the obfuscated system prompt does not contain any information that allows conclusions to be drawn about the original system prompt. We implement an optimization-based method to find an obfuscated prompt representation while maintaining the functionality. To evaluate our approach, we investigate eight different metrics to compare the performance of a system using the original and the obfuscated system prompts, and we show that the obfuscated version is constantly on par with the original one. We further perform three different deobfuscation attacks and show that with access to the obfuscated prompt and the LLM itself, we are not able to consistently extract meaningful information. Overall, we showed that prompt obfuscation can be an effective method to protect intellectual property while maintaining the same utility as the original system prompt.

[Arxiv](https://arxiv.org/abs/2409.11026)