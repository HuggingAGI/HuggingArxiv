# 在利用大型语言模型（LLM）进行程序修复时，事实选择问题尤为突出。

发布时间：2024年04月08日

`LLM应用` `软件开发` `程序修复`

> The Fact Selection Problem in LLM-Based Program Repair

# 摘要

> 最新研究发现，将bug相关信息纳入提示，如堆栈跟踪和GitHub问题，能显著提升大型语言模型（LLMs）的bug修复效率。随着模型上下文窗口的不断扩大，我们面临一个关键问题：在提示中应该包含哪些信息，以及包含多少，才能最有效地修复bug？为解答这一问题，我们展开了一项广泛的研究，利用超过19,000个不同组合的提示，涵盖七种多样的信息，来修复开源Python项目中的314个bug，这些项目均来自BugsInPy基准测试。研究结果显示，无论是简单的代码上下文等语法细节，还是天使值等在LLMs领域尚未被深入探讨的语义信息，每一条信息都对修复bug有所帮助。每一种信息都能解决一些特定的bug，否则这些bug可能无法解决，或仅有很低的修复成功率。值得注意的是，我们发现，随着使用的信息数量增加，程序修复提示的有效性并不是单调提升的；过多信息反而会导致效果下降。基于这些发现，我们提出了事实选择问题：如何确定最优的事实组合，以便在特定任务中最大化LLM的性能。我们发现，并没有一套适用于所有bug修复的事实集。因此，我们开发了一个名为Maniple的基础统计模型，它能针对特定bug选择相关事实来优化提示。该模型的修复效果显著优于任何通用事实集。为了凸显事实选择的重要性，我们将Maniple与目前最先进的零-shot、非对话式LLM基础bug修复方法进行了比较。在包含157个bug的测试数据集上，Maniple成功修复了88个bug，修复率比最佳配置高出17%。

> Recent research has shown that incorporating bug-related facts, such as stack traces and GitHub issues, into prompts enhances the bug-fixing capabilities of large language models (LLMs). Considering the ever-increasing context window of these models, a critical question arises: what and how many facts should be included in prompts to maximise the chance of correctly fixing bugs? To answer this question, we conducted a large-scale study, employing over 19K prompts featuring various combinations of seven diverse facts to rectify 314 bugs from open-source Python projects within the BugsInPy benchmark. Our findings revealed that each fact, ranging from simple syntactic details like code context to semantic information previously unexplored in the context of LLMs such as angelic values, is beneficial. Specifically, each fact aids in fixing some bugs that would remain unresolved or only be fixed with a low success rate without it. Importantly, we discovered that the effectiveness of program repair prompts is non-monotonic over the number of used facts; using too many facts leads to subpar outcomes. These insights led us to define the fact selection problem: determining the optimal set of facts for inclusion in a prompt to maximise LLM's performance on a given task instance. We found that there is no one-size-fits-all set of facts for bug repair. Therefore, we developed a basic statistical model, named Maniple, which selects facts specific to a given bug to include in the prompt. This model significantly surpasses the performance of the best generic fact set. To underscore the significance of the fact selection problem, we benchmarked Maniple against the state-of-the-art zero-shot, non-conversational LLM-based bug repair methods. On our testing dataset of 157 bugs, Maniple repairs 88 bugs, 17% above the best configuration.

[Arxiv](https://arxiv.org/abs/2404.05520)