# 借助大型语言模型，我们实现了语义增强的间接调用分析。

发布时间：2024年08月08日

`LLM应用` `软件开发` `静态分析`

> Semantic-Enhanced Indirect Call Analysis with Large Language Models

# 摘要

> 在现代软件开发中，间接调用的广泛使用给精确构建控制流图（CFGs）带来了挑战，进而影响了静态分析的性能。为此，本文提出了语义增强分析（SEA），一种新方法，旨在通过利用大型语言模型（LLMs）的语义分析能力，提升间接调用分析的准确性。SEA通过生成间接调用及其目标函数的自然语言摘要，进一步分析这些摘要以确定其适宜性，从而显著提高现有静态分析方法的精确度。实验结果证实了SEA的有效性，它能够为间接调用提供更精确的目标集，增强静态分析的实际应用效果。

> In contemporary software development, the widespread use of indirect calls to achieve dynamic features poses challenges in constructing precise control flow graphs (CFGs), which further impacts the performance of downstream static analysis tasks. To tackle this issue, various types of indirect call analyzers have been proposed. However, they do not fully leverage the semantic information of the program, limiting their effectiveness in real-world scenarios. To address these issues, this paper proposes Semantic-Enhanced Analysis (SEA), a new approach to enhance the effectiveness of indirect call analysis. Our fundamental insight is that for common programming practices, indirect calls often exhibit semantic similarity with their invoked targets. This semantic alignment serves as a supportive mechanism for static analysis techniques in filtering out false targets. Notably, contemporary large language models (LLMs) are trained on extensive code corpora, encompassing tasks such as code summarization, making them well-suited for semantic analysis. Specifically, SEA leverages LLMs to generate natural language summaries of both indirect calls and target functions from multiple perspectives. Through further analysis of these summaries, SEA can determine their suitability as caller-callee pairs. Experimental results demonstrate that SEA can significantly enhance existing static analysis methods by producing more precise target sets for indirect calls.

[Arxiv](https://arxiv.org/abs/2408.04344)