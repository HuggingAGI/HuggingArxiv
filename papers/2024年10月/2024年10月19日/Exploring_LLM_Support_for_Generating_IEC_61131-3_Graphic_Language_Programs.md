# 探究 LLM 在生成 IEC 61131-3 图形语言程序方面的支持能力

发布时间：2024年10月19日

`LLM应用` `工业自动化`

> Exploring LLM Support for Generating IEC 61131-3 Graphic Language Programs

# 摘要

> 大型语言模型 (LLM) 的强大能力激发了其在工业自动化中的应用。在 PLC 编程领域，研究人员已尝试用 LLM 生成结构化文本 (ST)，并构建自动编程流程。然而，广泛使用的 IEC 61131 图形编程语言却未受重视。本文探讨了 LLM 生成 ASCII 艺术图形语言以辅助工程师的可能性。实验显示，尽管通常认为 LLM 难以生成复杂图形，但通过提供示例，LLM 能正确生成简单需求的顺序功能图 (SFC)。然而，自动生成梯形图 (LD) 仍具挑战，且仅凭提示工程无法实现 LD 与 SFC 的自动转换。

> The capabilities demonstrated by Large Language Models (LLMs) inspire researchers to integrate them into industrial production and automation. In the field of Programmable Logic Controller (PLC) programming, previous researchers have focused on using LLMs to generate Structured Text (ST) language, and created automatic programming workflows based on it. The IEC 61131 graphic programming languages, which still has the most users, have however been overlooked.
  In this paper we explore using LLMs to generate graphic languages in ASCII art to provide assistance to engineers. Our series of experiments indicate that, contrary to what researchers usually think, it is possible to generate a correct Sequential Function Chart (SFC) for simple requirements when LLM is provided with several examples. On the other hand, generating a Ladder Diagram (LD) automatically remains a challenge even for very simple use cases. The automatic conversion between LD and SFC without extra information also fails when using prompt engineering alone.

[Arxiv](https://arxiv.org/abs/2410.15200)