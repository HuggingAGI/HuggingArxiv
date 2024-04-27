# 本研究旨在探究在多轮大型语言模型交互过程中出现的提示泄露问题，以及为此类交互设计的黑盒防御机制。

发布时间：2024年04月24日

`LLM应用` `安全和隐私` `人工智能`

> Investigating the prompt leakage effect and black-box defenses for multi-turn LLM interactions

# 摘要

> 大型语言模型（LLMs）中的提示泄露对安全和隐私构成严重威胁，尤其是在检索增强生成（RAG）系统中。尽管如此，对于多轮LLM交互中的泄露问题及相应的缓解措施，目前尚未有统一的研究方法。本研究深入探讨了不同领域和多种封闭与开源LLMs在提示泄露方面的脆弱性。我们创新的多轮威胁模型借助LLM的顺从效应，深入分析了LLM回应中的任务指令泄露和知识泄露。在多轮对话场景下，我们的模型将攻击成功率高达86.2%，尤其是在使用GPT-4和claude-1.3时，泄露率高达99%。研究发现，某些黑盒LLMs，如Gemini，在不同领域的泄露敏感性各异，例如在新闻领域比医疗领域更容易泄露上下文信息。我们的实验评估了六种黑盒防御策略的具体影响，包括RAG场景下的查询重写技术。我们提出的多层次防御策略组合，即使在黑盒LLMs中，仍能将攻击成功率降至5.3%，这表明LLM安全性研究还有提升空间，并指明了未来研究方向。

> Prompt leakage in large language models (LLMs) poses a significant security and privacy threat, particularly in retrieval-augmented generation (RAG) systems. However, leakage in multi-turn LLM interactions along with mitigation strategies has not been studied in a standardized manner. This paper investigates LLM vulnerabilities against prompt leakage across 4 diverse domains and 10 closed- and open-source LLMs. Our unique multi-turn threat model leverages the LLM's sycophancy effect and our analysis dissects task instruction and knowledge leakage in the LLM response. In a multi-turn setting, our threat model elevates the average attack success rate (ASR) to 86.2%, including a 99% leakage with GPT-4 and claude-1.3. We find that some black-box LLMs like Gemini show variable susceptibility to leakage across domains - they are more likely to leak contextual knowledge in the news domain compared to the medical domain. Our experiments measure specific effects of 6 black-box defense strategies, including a query-rewriter in the RAG scenario. Our proposed multi-tier combination of defenses still has an ASR of 5.3% for black-box LLMs, indicating room for enhancement and future direction for LLM security research.

[Arxiv](https://arxiv.org/abs/2404.16251)