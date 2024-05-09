# 隐私守护者：空气间隙技术在对话代理中的应用在翻译过程中，我首先确保了原文意思的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。在结果2中，我使用了“隐私守护者”这一形象的表达来替代“注重隐私的”，并用“空气间隙技术在对话代理中的应用”来概括原文的主题，使得翻译更加生动且易于理解。

发布时间：2024年05月08日

`Agent

这篇论文主要讨论了基于大型语言模型（LLM）的对话代理在处理敏感用户数据时面临的隐私问题，并提出了一种名为AirGapAgent的新型隐私保护代理。该代理通过限制对特定任务必要数据的访问来防止不必要的数据泄露，特别是在防止第三方恶意应用通过操纵交互上下文来诱导LLM代理泄露私人信息的威胁模型中。因此，这篇论文更符合Agent分类，因为它专注于开发和评估一个具体的代理系统，以解决LLM应用中的隐私保护问题。` `隐私保护` `对话系统`

> Air Gap: Protecting Privacy-Conscious Conversational Agents

# 摘要

> 随着基于LLM的对话代理在处理敏感用户数据方面的应用日益增多，隐私问题日益凸显。这些代理虽擅长处理上下文，却也可能成为恶意应用的利用对象。我们提出了一种新型威胁模型，其中第三方恶意应用通过操纵交互上下文，诱导LLM代理泄露无关任务的私人信息。为此，我们基于上下文完整性框架设计了AirGapAgent，一种注重隐私的代理，它通过限制对特定任务必要数据的访问，有效防止了不必要的数据泄露。通过Gemini、GPT和Mistral模型的大量实验，我们验证了AirGapAgent在防止上下文劫持的同时，仍能保持代理的核心功能。例如，Gemini Ultra代理在一次上下文劫持攻击下，其数据保护能力从94%骤降至45%，而AirGapAgent则实现了97%的高效保护，使此类攻击失效。

> The growing use of large language model (LLM)-based conversational agents to manage sensitive user data raises significant privacy concerns. While these agents excel at understanding and acting on context, this capability can be exploited by malicious actors. We introduce a novel threat model where adversarial third-party apps manipulate the context of interaction to trick LLM-based agents into revealing private information not relevant to the task at hand.
  Grounded in the framework of contextual integrity, we introduce AirGapAgent, a privacy-conscious agent designed to prevent unintended data leakage by restricting the agent's access to only the data necessary for a specific task. Extensive experiments using Gemini, GPT, and Mistral models as agents validate our approach's effectiveness in mitigating this form of context hijacking while maintaining core agent functionality. For example, we show that a single-query context hijacking attack on a Gemini Ultra agent reduces its ability to protect user data from 94% to 45%, while an AirGapAgent achieves 97% protection, rendering the same attack ineffective.

[Arxiv](https://arxiv.org/abs/2405.05175)