# SPML：一种专为抵御提示攻击而设计的领域特定语言，用于保护语言模型的安全。

发布时间：2024年02月18日

`LLM应用` `网络安全`

> SPML: A DSL for Defending Language Models Against Prompt Attacks

# 摘要

> 大型语言模型（LLMs）彻底革新了自然语言处理应用，尤其在基于指令的设计上，聊天机器人的依赖日益增加。但部署后的聊天机器人定义变得僵化，易受恶意用户攻击，这凸显了防范不当应用和避免财务损失的重要性。尽管现有研究已探讨用户输入对LLM驱动的聊天机器人的影响，但如何有效防御特定应用聊天机器人的攻击仍是一个未解之谜。本文提出了系统提示元语言（SPML），这是一门专为优化聊天机器人提示和监控输入而设计的语言。SPML能够主动识别并阻止攻击性输入，确保用户操作与机器人预设的定义相匹配，从而在LLM基础上防止恶意操作，同时降低成本。它还利用编程语言的特性，简化了聊天机器人的定义过程，解决了自然语言设计的难题。文章还首次提出了一个包含1800个系统提示和20000个用户输入的创新基准测试，为聊天机器人定义的评估提供了新的语言和标准。跨多个数据集的实验证明，SPML在识别攻击性输入方面的能力超过了GPT-4、GPT-3.5和LLAMA等模型。相关数据和代码已在 https://prompt-compiler.github.io/SPML/ 公开发布。

> Large language models (LLMs) have profoundly transformed natural language applications, with a growing reliance on instruction-based definitions for designing chatbots. However, post-deployment the chatbot definitions are fixed and are vulnerable to attacks by malicious users, emphasizing the need to prevent unethical applications and financial losses. Existing studies explore user prompts' impact on LLM-based chatbots, yet practical methods to contain attacks on application-specific chatbots remain unexplored. This paper presents System Prompt Meta Language (SPML), a domain-specific language for refining prompts and monitoring the inputs to the LLM-based chatbots. SPML actively checks attack prompts, ensuring user inputs align with chatbot definitions to prevent malicious execution on the LLM backbone, optimizing costs. It also streamlines chatbot definition crafting with programming language capabilities, overcoming natural language design challenges. Additionally, we introduce a groundbreaking benchmark with 1.8k system prompts and 20k user inputs, offering the inaugural language and benchmark for chatbot definition evaluation. Experiments across datasets demonstrate SPML's proficiency in understanding attacker prompts, surpassing models like GPT-4, GPT-3.5, and LLAMA. Our data and codes are publicly available at: https://prompt-compiler.github.io/SPML/.

[Arxiv](https://arxiv.org/abs/2402.11755)