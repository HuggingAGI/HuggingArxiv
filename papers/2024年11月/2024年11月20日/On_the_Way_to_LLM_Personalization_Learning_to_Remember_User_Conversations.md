# 在实现 LLM 个性化的进程中：学会铭记用户对话

发布时间：2024年11月20日

`LLM应用` `语言模型` `对话系统`

> On the Way to LLM Personalization: Learning to Remember User Conversations

# 摘要

> 大型语言模型（LLMs）很快成为各类任务的得力助手。不过，其有效性受限于通过个性化来贴合人类偏好和行为做出响应的能力。此前在 LLM 个性化方面的工作，多集中于风格转换或融入有关用户的小细节，知识注入仍是一大难题。本文中，我们探索向 LLMs 注入先前对话的知识，以推动未来关于更精简、个性化对话的研究。我们明确了两个现实约束：（1）对话在时间上是有序的，训练时必须如此对待；（2）针对每个用户的个性化只有在参数高效的设置中才可行。为此，我们提出 PLUM，这是一个把对话当作问答对进行数据增强的流程，然后用于通过加权交叉熵损失来微调低秩适应适配器。即便在对该问题的首次探索中，我们与 RAG 等基线的表现旗鼓相当，在 100 次对话中达到了 81.5％的准确率。

> Large Language Models (LLMs) have quickly become an invaluable assistant for a variety of tasks. However, their effectiveness is constrained by their ability to tailor responses to human preferences and behaviors via personalization. Prior work in LLM personalization has largely focused on style transfer or incorporating small factoids about the user, as knowledge injection remains an open challenge. In this paper, we explore injecting knowledge of prior conversations into LLMs to enable future work on less redundant, personalized conversations. We identify two real-world constraints: (1) conversations are sequential in time and must be treated as such during training, and (2) per-user personalization is only viable in parameter-efficient settings. To this aim, we propose PLUM, a pipeline performing data augmentation for up-sampling conversations as question-answer pairs, that are then used to finetune a low-rank adaptation adapter with a weighted cross entropy loss. Even in this first exploration of the problem, we perform competitively with baselines such as RAG, attaining an accuracy of 81.5% across 100 conversations.

[Arxiv](https://arxiv.org/abs/2411.13405)