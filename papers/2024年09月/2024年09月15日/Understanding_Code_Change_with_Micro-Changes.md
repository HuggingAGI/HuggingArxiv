# 洞悉代码变迁中的微妙变化

发布时间：2024年09月15日

`LLM应用` `软件开发` `软件维护`

> Understanding Code Change with Micro-Changes

# 摘要

> 在软件维护和演进中，理解开发者在提交拉取请求或执行提交时的代码更改至关重要。通常，这些更改以代码差异的形式呈现，突出显示文件版本间的差异。然而，这种基于文本的表示繁琐且需要深厚的领域知识和编程技能。为此，我们提出了一种基于微更改概念的方法，将代码差异转化为一系列自然语言描述的预定义更改操作。我们不仅提供了一个微更改目录，还开发了自动检测器。实证研究表明，该检测器在解释条件逻辑相关的更改时，准确率超过67%。

> A crucial activity in software maintenance and evolution is the comprehension of the changes performed by developers, when they submit a pull request and/or perform a commit on the repository. Typically, code changes are represented in the form of code diffs, textual representations highlighting the differences between two file versions, depicting the added, removed, and changed lines. This simplistic representation must be interpreted by developers, and mentally lifted to a higher abstraction level, that more closely resembles natural language descriptions, and eases the creation of a mental model of the changes. However, the textual diff-based representation is cumbersome, and the lifting requires considerable domain knowledge and programming skills. We present an approach, based on the concept of micro-change, to overcome these difficulties, translating code diffs into a series of pre-defined change operations, which can be described in natural language. We present a catalog of micro-changes, together with an automated micro-change detector. To evaluate our approach, we performed an empirical study on a large set of open-source repositories, focusing on a subset of our micro-change catalog, namely those related to changes affecting the conditional logic. We found that our detector is capable of explaining more than 67% of the changes taking place in the systems under study.

[Arxiv](https://arxiv.org/abs/2409.09923)