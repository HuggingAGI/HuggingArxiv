# 基于深度学习的代码审查：是范式转变还是双刃剑？

发布时间：2024年11月18日

`LLM应用` `软件工程` `代码审查`

> Deep Learning-based Code Reviews: A Paradigm Shift or a Double-Edged Sword?

# 摘要

> 已有若干技术被提出用于实现代码审查的自动化。早期的支持在于为给定的变更推荐最适合的审查者，或者为审查任务设定优先级。随着软件工程中深度学习的出现，自动化水平被推至新高度，有些方法能够像人类审查者一样以自然语言为源代码提供反馈。而且，近期工作记载了开源项目将大型语言模型（LLMs）用作共同审查者。尽管此领域的研究十分活跃，但对于在代码审查流程中纳入自动生成的代码审查的实际影响却知之甚少。虽然有众多方面值得探究，但在这项工作中，我们聚焦于其中三个：（i）审查质量，也就是审查者识别代码中问题的能力；（ii）审查成本，即审查代码所耗费的时间；（iii）审查者的信心，即审查者对所提供反馈的信心程度。我们对 29 位专家开展了一项对照实验，他们在有/无自动生成的代码审查支持的情况下审查了不同的程序。在实验过程中，我们监测了审查者的活动，记录了超过 50 小时的代码审查情况。我们发现，审查者认为 LLM 自动识别的大部分问题是有效的，并且以自动审查作为起点会极大地影响他们的行为：审查者倾向于关注 LLM 所指出的代码位置，而非在代码的其他部分寻找更多问题。与完全手动的流程相比，从自动审查开始的审查者能识别出更多低严重性的问题，然而，却并未识别出更多高严重性的问题。最后，自动化支持既未节省时间，也未增强审查者的信心。

> Several techniques have been proposed to automate code review. Early support consisted in recommending the most suited reviewer for a given change or in prioritizing the review tasks. With the advent of deep learning in software engineering, the level of automation has been pushed to new heights, with approaches able to provide feedback on source code in natural language as a human reviewer would do. Also, recent work documented open source projects adopting Large Language Models (LLMs) as co-reviewers. Although the research in this field is very active, little is known about the actual impact of including automatically generated code reviews in the code review process. While there are many aspects worth investigating, in this work we focus on three of them: (i) review quality, i.e., the reviewer's ability to identify issues in the code; (ii) review cost, i.e., the time spent reviewing the code; and (iii) reviewer's confidence, i.e., how confident is the reviewer about the provided feedback. We run a controlled experiment with 29 experts who reviewed different programs with/without the support of an automatically generated code review. During the experiment we monitored the reviewers' activities, for over 50 hours of recorded code reviews. We show that reviewers consider valid most of the issues automatically identified by the LLM and that the availability of an automated review as a starting point strongly influences their behavior: Reviewers tend to focus on the code locations indicated by the LLM rather than searching for additional issues in other parts of the code. The reviewers who started from an automated review identified a higher number of low-severity issues while, however, not identifying more high-severity issues as compared to a completely manual process. Finally, the automated support did not result in saved time and did not increase the reviewers' confidence.

[Arxiv](https://arxiv.org/abs/2411.11401)