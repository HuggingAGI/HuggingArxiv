# CoXQL：解析对话式XAI系统解释请求的数据集

发布时间：2024年06月12日

`Agent

理由：该论文主要关注的是基于大型语言模型（LLM）的ConvXAI系统中的用户意图识别问题，并推出了一个新的数据集CoXQL来解决这一问题。这个系统可以被视为一个智能代理（Agent），因为它旨在理解和响应用户的查询，并提供关于AI决策的解释。此外，论文中提到的系统改进和评估也是针对如何更好地作为代理来服务用户，而不是专注于LLM的理论研究或应用开发。因此，将其归类为Agent是合适的。` `人机交互`

> CoXQL: A Dataset for Parsing Explanation Requests in Conversational XAI Systems

# 摘要

> 基于LLMs的ConvXAI系统在NLP和HCI领域备受瞩目，它们不仅能解答用户关于AI决策的疑问，还能增进用户对AI过程的理解。然而，现有的ConvXAI系统依赖于意图识别而非自由对话，这使得准确捕捉用户意图成为一大难题。为此，我们推出了首个专注于ConvXAI用户意图识别的数据集CoXQL，包含31种意图，其中7种需额外填充信息。我们通过引入模板验证优化了解析技术，并对多个LLMs在CoXQL上的表现进行了评估，发现改进后的解析方法（MP+）显著优于以往。尽管如此，处理多槽意图对LLMs而言依旧充满挑战。

> Conversational explainable artificial intelligence (ConvXAI) systems based on large language models (LLMs) have garnered significant interest from the research community in natural language processing (NLP) and human-computer interaction (HCI). Such systems can provide answers to user questions about explanations, have the potential to enhance users' comprehension and offer more information about the decision-making and generation processes of LLMs. Currently available ConvXAI systems are based on intent recognition rather than free chat. Thus, reliably grasping users' intentions in ConvXAI systems still presents a challenge, because there is a broad range of XAI methods to map requests onto and each of them can have multiple slots to take care of. In order to bridge this gap, we present CoXQL, the first dataset for user intent recognition in ConvXAI, covering 31 intents, seven of which require filling additional slots. Subsequently, we enhance an existing parsing approach by incorporating template validations, and conduct an evaluation of several LLMs on CoXQL using different parsing strategies. We conclude that the improved parsing approach (MP+) surpasses the performance of previous approaches. We also discover that intents with multiple slots remain highly challenging for LLMs.

[Arxiv](https://arxiv.org/abs/2406.08101)