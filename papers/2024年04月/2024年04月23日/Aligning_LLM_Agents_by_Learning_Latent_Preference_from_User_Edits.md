# 通过分析用户编辑，我们能够学习到用户的潜在偏好，进而调整大型语言模型（LLM）代理的行为，使之更好地符合用户的需求。

发布时间：2024年04月23日

`Agent` `写作辅助` `个性化学习`

> Aligning LLM Agents by Learning Latent Preference from User Edits

# 摘要

> 本研究探讨了语言代理基于用户对其输出进行编辑的交互式学习方法。在写作助手等典型应用场景中，用户与语言代理互动生成特定上下文的回复，并可根据自身隐性偏好对代理的回复进行编辑，以实现个性化并提升准确性。这种编辑反馈自然形成，适合用于提升代理与用户偏好的契合度，同时降低用户随时间的编辑成本。我们提出了一个名为PRELUDE的学习框架，它依据历史编辑数据推断用户的隐性偏好，并据此制定提示策略，引导未来回复的生成，避免了成本高昂且难以扩展的代理微调过程，同时可能影响其在其他任务上的表现。此外，学习描述性偏好增强了模型的可解释性，使用户能够查看和调整已学习的偏好。然而，用户偏好复杂多变，受上下文影响，学习起来颇具挑战。为应对这一挑战，我们设计了一个高效简洁的算法CIPHER，该算法利用大型语言模型（LLM）基于用户编辑推断特定上下文中的用户偏好。未来，CIPHER将从历史中检索k个最相似的上下文的推断偏好，并综合这些偏好以生成回复。我们还构建了两个交互环境——文摘和电子邮件撰写，通过GPT-4模拟用户进行评估。在这两个任务中，CIPHER不仅实现了最低的编辑距离成本，而且学习到的偏好与真实偏好有显著的相似性，相较于其他直接检索用户编辑但不学习描述性偏好的算法，以及学习与上下文无关偏好的算法，表现更为出色。

> We study interactive learning of language agents based on user edits made to the agent's output. In a typical setting such as writing assistants, the user interacts with a language agent to generate a response given a context, and may optionally edit the agent response to personalize it based on their latent preference, in addition to improving the correctness. The edit feedback is naturally generated, making it a suitable candidate for improving the agent's alignment with the user's preference, and for reducing the cost of user edits over time. We propose a learning framework, PRELUDE that infers a description of the user's latent preference based on historic edit data and using it to define a prompt policy that drives future response generation. This avoids fine-tuning the agent, which is costly, challenging to scale with the number of users, and may even degrade its performance on other tasks. Furthermore, learning descriptive preference improves interpretability, allowing the user to view and modify the learned preference. However, user preference can be complex and vary based on context, making it challenging to learn. To address this, we propose a simple yet effective algorithm named CIPHER that leverages a large language model (LLM) to infer the user preference for a given context based on user edits. In the future, CIPHER retrieves inferred preferences from the k-closest contexts in the history, and forms an aggregate preference for response generation. We introduce two interactive environments -- summarization and email writing, for evaluation using a GPT-4 simulated user. We compare with algorithms that directly retrieve user edits but do not learn descriptive preference, and algorithms that learn context-agnostic preference. On both tasks, CIPHER achieves the lowest edit distance cost and learns preferences that show significant similarity to the ground truth preferences

[Arxiv](https://arxiv.org/abs/2404.15269)