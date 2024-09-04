# 自我指导派生提示与上下文学习相结合，为黑盒LLM开辟新天地。

发布时间：2024年09月02日

`LLM应用` `人工智能`

> Self-Instructed Derived Prompt Generation Meets In-Context Learning: Unlocking New Potential of Black-Box LLMs

# 摘要

> 大型语言模型（LLM）在生成高质量响应方面表现出色。为了更好地与人类偏好对齐，尽管基于特定优化过程提出了多种方法，但这些方法不适用于参数不可访问的黑盒LLM，如GPT-4。在黑盒LLM中，性能高度依赖于提示的质量。现有提升响应质量的方法常涉及提示细化，但可能导致细化提示与原始提示间的语义不一致，且忽视了两者关系。为此，我们提出了一种自我指导的上下文学习框架，通过生成可靠的派生提示来构建信息丰富的上下文环境，从而提升LLM的响应效果。该框架结合了自我指导的强化学习机制，允许在生成派生提示时直接与响应模型交互，以更好地对齐。此外，我们将查询视为上下文学习任务，利用LLM的响应和派生提示为原始提示建立上下文演示，确保与原始查询对齐，减少与细化提示的差异，并最大化LLM的上下文学习能力。实验证明，该方法不仅能生成更可靠的派生提示，还能显著提升LLM的响应效果，包括GPT-4等黑盒模型。

> Large language models (LLMs) have shown success in generating high-quality responses. In order to achieve better alignment with LLMs with human preference, various works are proposed based on specific optimization process, which, however, is not suitable to Black-Box LLMs like GPT-4, due to inaccessible parameters. In Black-Box LLMs case, their performance is highly dependent on the quality of the provided prompts. Existing methods to enhance response quality often involve a prompt refinement model, yet these approaches potentially suffer from semantic inconsistencies between the refined and original prompts, and typically overlook the relationship between them. To address these challenges, we introduce a self-instructed in-context learning framework that empowers LLMs to deliver more effective responses by generating reliable derived prompts to construct informative contextual environments. Our approach incorporates a self-instructed reinforcement learning mechanism, enabling direct interaction with the response model during derived prompt generation for better alignment. We then formulate querying as an in-context learning task, using responses from LLMs combined with the derived prompts to establish a contextual demonstration for the original prompt. This strategy ensures alignment with the original query, reduces discrepancies from refined prompts, and maximizes the LLMs' in-context learning capability. Extensive experiments demonstrate that the proposed method not only generates more reliable derived prompts but also significantly enhances LLMs' ability to deliver more effective responses, including Black-Box models such as GPT-4.

[Arxiv](https://arxiv.org/abs/2409.01552)