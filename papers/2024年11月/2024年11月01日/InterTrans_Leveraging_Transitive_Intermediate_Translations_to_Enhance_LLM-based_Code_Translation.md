# InterTrans：借助传递性中间翻译提升基于 LLM 的代码翻译能力

发布时间：2024年11月01日

`LLM应用` `软件工程` `代码翻译`

> InterTrans: Leveraging Transitive Intermediate Translations to Enhance LLM-based Code Translation

# 摘要

> 代码翻译的目标是把程序从一种编程语言（PL）转换为另一种。这一长期存在的软件工程任务，对遗留系统的现代化、保障跨平台兼容性、提升性能等意义重大。不过，由于编程语言间存在众多语法和语义差异，实现这一过程的自动化颇具挑战。近期研究显示，即便像大型语言模型（LLMs）这类先进技术，尤其是开源的LLMs，在完成此任务时也困难重重。当下，代码LLMs通过多种编程语言的源代码进行训练，由此具备了多语言能力。
  在本文中，我们探究这种多语言能力能否用于强化代码翻译。为达成此目标，我们引入了InterTrans，这是一种基于LLM的自动化代码翻译方法，与现有方法不同，它借助编程语言间的中间翻译来填补源语言和目标语言之间的语法及语义鸿沟。
  InterTrans包含两个阶段。它先是运用一种新颖的代码翻译树（ToCT）算法来规划给定的源语言和目标语言之间的过渡性中间翻译序列，然后按特定顺序对其进行验证。我们在三个基准（即CodeNet、HumanEval-X和TransCoder）上，使用三个开源LLMs对InterTrans进行评估，涉及六种编程语言。结果表明，InterTrans在计算精度（CA）方面相较于直接翻译，经过10次尝试，绝对提升了18.3%至43.3%。InterTrans表现最佳的变体（采用Magicoder LLM）在三个基准上的平均CA达到了87.3%-95.4%。

> Code translation aims to convert a program from one programming language (PL) to another. This long-standing software engineering task is crucial for modernizing legacy systems, ensuring cross-platform compatibility, enhancing performance, and more. However, automating this process remains challenging due to many syntactic and semantic differences between PLs. Recent studies show that even advanced techniques such as large language models (LLMs), especially open-source LLMs, still struggle with the task. Currently, code LLMs are trained with source code from multiple programming languages, thus presenting multilingual capabilities.
  In this paper, we investigate whether such multilingual capabilities can be harnessed to enhance code translation. To achieve this goal, we introduce InterTrans, an LLM-based automated code translation approach that, in contrast to existing approaches, leverages intermediate translations across PLs to bridge the syntactic and semantic gaps between source and target PLs.
  InterTrans contains two stages. It first utilizes a novel Tree of Code Translation (ToCT) algorithm to plan transitive intermediate translation sequences between a given source and target PL, then validates them in a specific order. We evaluate InterTrans with three open LLMs on three benchmarks (i.e., CodeNet, HumanEval-X, and TransCoder) involving six PLs. Results show an absolute improvement between 18.3% to 43.3% in Computation Accuracy (CA) for InterTrans over Direct Translation with 10 attempts. The best-performing variant of InterTrans (with Magicoder LLM) achieved an average CA of 87.3%-95.4% on three benchmarks.

[Arxiv](https://arxiv.org/abs/2411.01063)