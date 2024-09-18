# 借助评审者经验，优化代码评审评论生成

发布时间：2024年09月17日

`LLM应用` `软件工程` `人工智能`

> Leveraging Reviewer Experience in Code Review Comment Generation

# 摘要

> 现代代码审查旨在发现新代码中的潜在问题，但这一过程需要大量人力。为减轻负担，研究人员训练了深度学习模型来模仿人类审查员进行自然语言代码审查，这一任务被称为代码审查评论生成。尽管已有研究通过机器学习技术和神经模型（如迁移学习和变换器架构）改进了此任务，但由于开源代码审查数据的质量问题，生成的审查质量仍不理想。为解决这一问题，我们提出了一套经验感知的训练方法，利用审查员的过往经验作为质量信号，并设计了经验感知损失函数（ELF），使经验丰富的审查员对模型行为产生更大影响。实验表明，ELF在生成高质量审查方面优于现有模型。这项研究展示了如何将传统软件工程概念融入AI自动化代码审查模型设计中。

> Modern code review is a ubiquitous software quality assurance process aimed at identifying potential issues within newly written code. Despite its effectiveness, the process demands large amounts of effort from the human reviewers involved. To help alleviate this workload, researchers have trained deep learning models to imitate human reviewers in providing natural language code reviews. Formally, this task is known as code review comment generation. Prior work has demonstrated improvements in this task by leveraging machine learning techniques and neural models, such as transfer learning and the transformer architecture. However, the quality of the model generated reviews remain sub-optimal due to the quality of the open-source code review data used in model training. This is in part due to the data obtained from open-source projects where code reviews are conducted in a public forum, and reviewers possess varying levels of software development experience, potentially affecting the quality of their feedback. To accommodate for this variation, we propose a suite of experience-aware training methods that utilise the reviewers' past authoring and reviewing experiences as signals for review quality. Specifically, we propose experience-aware loss functions (ELF), which use the reviewers' authoring and reviewing ownership of a project as weights in the model's loss function. Through this method, experienced reviewers' code reviews yield larger influence over the model's behaviour. Compared to the SOTA model, ELF was able to generate higher quality reviews in terms of accuracy, informativeness, and comment types generated. The key contribution of this work is the demonstration of how traditional software engineering concepts such as reviewer experience can be integrated into the design of AI-based automated code review models.

[Arxiv](https://arxiv.org/abs/2409.10959)