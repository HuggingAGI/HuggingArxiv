# Archimedes-AUEB 团队在 SemEval-2024 的第五项任务中，运用大型语言模型（LLM）对民法程序进行了解释。本研究聚焦于利用 LLM 的强大功能，深入剖析民法程序的复杂性，并探索其在法律领域的应用潜力。

发布时间：2024年05月14日

`Agent

这篇论文介绍了一种使用ChatGPT作为教师级LLM来指导和扩展训练集，进而微调一个小型学生级LLM的方法。这种方法涉及生成合成数据和提供基于人类分析的解释，以增强推理能力。论文中提到的系统在SemEval竞赛中取得了成绩，并能够生成与人类分析相符的解释，这表明该系统具有一定的自主推理和学习能力，因此可以归类为Agent。`

> Archimedes-AUEB at SemEval-2024 Task 5: LLM explains Civil Procedure

# 摘要

> SemEval的民事诉讼程序论据推理任务因其对法律概念的深刻理解和复杂论据的推断而颇具挑战。尽管大型语言模型（LLM）在法律领域表现卓越，但它们多用于分类任务，其推理逻辑常受质疑。我们提出的方法采用ChatGPT这一强大的教师级LLM，通过提供解释和生成合成数据来扩展训练集，进而微调一个小型学生级LLM。与以往依赖教师内部知识的解释不同，我们的解释扎根于真实的人类分析，从而传递出更强的推理信号。我们还创新了一种“变异”方法，从现有数据中创造出人工数据实例。我们不仅公开了这些解释作为数据集的扩展，还分享了用于生成它们的合成数据和提示。在SemEval竞赛中，我们的系统名列第15，不仅超越了其教师，还能生成与人类分析相符的解释，这一点已得到法律专家的确认。

> The SemEval task on Argument Reasoning in Civil Procedure is challenging in that it requires understanding legal concepts and inferring complex arguments. Currently, most Large Language Models (LLM) excelling in the legal realm are principally purposed for classification tasks, hence their reasoning rationale is subject to contention. The approach we advocate involves using a powerful teacher-LLM (ChatGPT) to extend the training dataset with explanations and generate synthetic data. The resulting data are then leveraged to fine-tune a small student-LLM. Contrary to previous work, our explanations are not directly derived from the teacher's internal knowledge. Instead they are grounded in authentic human analyses, therefore delivering a superior reasoning signal. Additionally, a new `mutation' method generates artificial data instances inspired from existing ones. We are publicly releasing the explanations as an extension to the original dataset, along with the synthetic dataset and the prompts that were used to generate both. Our system ranked 15th in the SemEval competition. It outperforms its own teacher and can produce explanations aligned with the original human analyses, as verified by legal experts.

[Arxiv](https://arxiv.org/abs/2405.08502)