# 基于 LLM 的评论生成在实践中的影响：一项混合开源/闭源的用户研究

发布时间：2024年11月11日

`LLM应用` `软件开发` `代码审查`

> Impact of LLM-based Review Comment Generation in Practice: A Mixed Open-/Closed-source User Study

# 摘要

> 我们在实际环境中进行了大规模的实证用户研究，以评估对 LLM 生成的评论的接受程度及其对审查过程的影响。这项用户研究在两个组织中进行，分别是 Mozilla（其代码库作为开源可用）和 Ubisoft（完全闭源）。在他们通常的审查环境中，参与者可以使用 RevMate，这是一个基于 LLM 的辅助工具，使用带有检索增强生成的现成 LLM 来提供额外的代码和审查上下文，并结合 LLM 作为法官，自动评估生成的评论并丢弃不相关的情况。基于 RevMate 提供的超过 587 个补丁审查，我们观察到每个组织中分别有 8.1％和 7.2％的 LLM 生成的评论被审查人员接受，而 14.6％和 20.5％的其他评论仍被标记为有价值的审查或开发提示。与功能评论相比，重构相关的评论更有可能被接受（分别为 18.2％和 18.6％，而功能评论为 4.8％和 5.2％）。审查人员检查生成的评论或编辑接受的评论所花费的额外时间（36/119），每个补丁的总体中位数为 43 秒，是合理的。被接受的生成评论与人工编写的评论一样有可能导致修改后的补丁的未来修订（在块级别分别为 74％对 73％）。

> We conduct a large-scale empirical user study in a live setup to evaluate the acceptance of LLM-generated comments and their impact on the review process. This user study was performed in two organizations, Mozilla (which has its codebase available as open source) and Ubisoft (fully closed-source). Inside their usual review environment, participants were given access to RevMate, an LLM-based assistive tool suggesting generated review comments using an off-the-shelf LLM with Retrieval Augmented Generation to provide extra code and review context, combined with LLM-as-a-Judge, to auto-evaluate the generated comments and discard irrelevant cases. Based on more than 587 patch reviews provided by RevMate, we observed that 8.1% and 7.2%, respectively, of LLM-generated comments were accepted by reviewers in each organization, while 14.6% and 20.5% other comments were still marked as valuable as review or development tips. Refactoring-related comments are more likely to be accepted than Functional comments (18.2% and 18.6% compared to 4.8% and 5.2%). The extra time spent by reviewers to inspect generated comments or edit accepted ones (36/119), yielding an overall median of 43s per patch, is reasonable. The accepted generated comments are as likely to yield future revisions of the revised patch as human-written comments (74% vs 73% at chunk-level).

[Arxiv](https://arxiv.org/abs/2411.07091)