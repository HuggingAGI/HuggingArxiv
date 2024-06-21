# Prose-to-P4: 借助高级语言之力

发布时间：2024年06月19日

`LLM应用

这篇论文探讨了利用大型语言模型（LLMs）将自然语言转换为高级网络代码的设想，这是一个具体的应用场景，涉及将LLMs应用于网络编程领域，以简化网络应用的开发过程。因此，它属于LLM应用分类。` `网络技术` `软件开发`

> Prose-to-P4: Leveraging High Level Languages

# 摘要

> P4和NPL等语言推动了利用可编程数据平面的网络应用的广泛发展，但这些语言的软件开发颇具挑战。为此，高级语言应运而生，它们通过提供强大的抽象能力，简化了网络应用的开发过程。这些高级语言经编译器转换为P4/NPL代码。借鉴大型语言模型（LLMs）在代码生成领域的成功，我们提出一个更高层次的抽象方案：利用LLMs将自然语言转换为高级网络代码。本文探讨了这一设想的动机、机遇与挑战，并规划了开发能够根据自然语言指令生成高级数据平面代码的系统的路线图。我们初步展示了将自然语言转换为Lucid代码的积极成果。

> Languages such as P4 and NPL have enabled a wide and diverse range of networking applications that take advantage of programmable dataplanes. However, software development in these languages is difficult. To address this issue, high-level languages have been designed to offer programmers powerful abstractions that reduce the time, effort and domain-knowledge required for developing networking applications. These languages are then translated by a compiler into P4/NPL code. Inspired by the recent success of Large Language Models (LLMs) in the task of code generation, we propose to raise the level of abstraction even higher, employing LLMs to translate prose into high-level networking code. We analyze the problem, focusing on the motivation and opportunities, as well as the challenges involved and sketch out a roadmap for the development of a system that can generate high-level dataplane code from natural language instructions. We present some promising preliminary results on generating Lucid code from natural language.

[Arxiv](https://arxiv.org/abs/2406.13679)