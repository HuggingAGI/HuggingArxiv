# 通过分析用户编辑，我们能够学习用户的潜在偏好，并据此调整大型语言模型代理的行为，以更好地满足用户需求。

发布时间：2024年04月23日

`Agent` `写作辅助` `个性化学习`

> Aligning LLM Agents by Learning Latent Preference from User Edits

# 摘要

> 本研究探讨了语言代理如何通过用户对其生成内容的编辑来学习。在写作辅助工具等常见场景中，用户与语言代理互动，根据特定上下文生成回复，并可根据自己的隐性偏好对代理的回复进行编辑，以实现个性化并提升准确性。这种编辑反馈自然产生，有助于提升代理与用户偏好的契合度，同时降低用户随时间的编辑成本。我们提出了一个名为PRELUDE的学习框架，它通过分析历史编辑数据来推断用户的隐性偏好，并据此制定提示策略，引导未来生成的回复。这种方法避免了对代理进行微调，因为微调不仅成本高昂，而且难以适应用户数量的增长，还可能影响其在其他任务上的表现。此外，学习描述性偏好也增强了系统的可解释性，使用户能够查看并调整已学习到的偏好。然而，用户偏好复杂多变，受上下文影响，学习起来颇具挑战。为此，我们设计了一个简单高效的算法CIPHER，它利用大型语言模型（LLM）根据用户编辑来推断特定上下文下的用户偏好。CIPHER能够在历史中寻找k个最相似的上下文，从中提取出用户的偏好，并综合这些偏好以生成回复。我们创建了两个交互环境——文摘和电子邮件撰写，用GPT-4模拟用户进行评估。CIPHER在这两个任务中均展现出了最低的编辑成本，并学习到了与真实偏好高度相似的偏好。

> We study interactive learning of language agents based on user edits made to the agent's output. In a typical setting such as writing assistants, the user interacts with a language agent to generate a response given a context, and may optionally edit the agent response to personalize it based on their latent preference, in addition to improving the correctness. The edit feedback is naturally generated, making it a suitable candidate for improving the agent's alignment with the user's preference, and for reducing the cost of user edits over time. We propose a learning framework, PRELUDE that infers a description of the user's latent preference based on historic edit data and using it to define a prompt policy that drives future response generation. This avoids fine-tuning the agent, which is costly, challenging to scale with the number of users, and may even degrade its performance on other tasks. Furthermore, learning descriptive preference improves interpretability, allowing the user to view and modify the learned preference. However, user preference can be complex and vary based on context, making it challenging to learn. To address this, we propose a simple yet effective algorithm named CIPHER that leverages a large language model (LLM) to infer the user preference for a given context based on user edits. In the future, CIPHER retrieves inferred preferences from the k-closest contexts in the history, and forms an aggregate preference for response generation. We introduce two interactive environments -- summarization and email writing, for evaluation using a GPT-4 simulated user. We compare with algorithms that directly retrieve user edits but do not learn descriptive preference, and algorithms that learn context-agnostic preference. On both tasks, CIPHER achieves the lowest edit distance cost and learns preferences that show significant similarity to the ground truth preferences

[Arxiv](https://arxiv.org/abs/2404.15269)