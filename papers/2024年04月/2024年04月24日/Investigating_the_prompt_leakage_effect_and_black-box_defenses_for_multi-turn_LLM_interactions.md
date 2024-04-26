# 本研究旨在探究在多轮大型语言模型交互过程中出现的提示泄露问题，以及为此类交互设计的黑箱防御机制。

发布时间：2024年04月24日

`LLM应用` `安全与隐私` `人工智能`

> Investigating the prompt leakage effect and black-box defenses for multi-turn LLM interactions

# 摘要

> 大型语言模型（LLMs）中的提示泄露对安全和隐私构成严重威胁，尤其是在检索增强生成（RAG）系统中。尽管如此，对于多轮LLM交互中的泄露现象及缓解措施，目前尚未有标准化的研究方法。本研究深入探讨了不同领域和多种开源及闭源LLMs在面对提示泄露时的脆弱性。我们创新的多轮威胁模型借助LLM的迎合效应，深入分析了LLM回应中的任务指令泄露和知识泄露。在多轮对话环境中，我们的模型将攻击成功率提升至86.2%，特别是在针对GPT-4和claude-1.3的测试中，泄露率高达99%。我们还发现，某些黑盒LLMs（例如Gemini）在不同领域的泄露敏感性各异，它们在新闻领域比在医疗领域更容易泄露上下文信息。通过实验，我们评估了六种黑盒防御策略的具体效果，包括在RAG场景中应用的查询重写器。我们提出的多层次防御策略组合，即使在黑盒LLMs中，仍能将攻击成功率控制在5.3%，这表明LLM安全性研究还有很大的提升空间和未来的发展方向。

> Prompt leakage in large language models (LLMs) poses a significant security and privacy threat, particularly in retrieval-augmented generation (RAG) systems. However, leakage in multi-turn LLM interactions along with mitigation strategies has not been studied in a standardized manner. This paper investigates LLM vulnerabilities against prompt leakage across 4 diverse domains and 10 closed- and open-source LLMs. Our unique multi-turn threat model leverages the LLM's sycophancy effect and our analysis dissects task instruction and knowledge leakage in the LLM response. In a multi-turn setting, our threat model elevates the average attack success rate (ASR) to 86.2%, including a 99% leakage with GPT-4 and claude-1.3. We find that some black-box LLMs like Gemini show variable susceptibility to leakage across domains - they are more likely to leak contextual knowledge in the news domain compared to the medical domain. Our experiments measure specific effects of 6 black-box defense strategies, including a query-rewriter in the RAG scenario. Our proposed multi-tier combination of defenses still has an ASR of 5.3% for black-box LLMs, indicating room for enhancement and future direction for LLM security research.

[Arxiv](https://arxiv.org/abs/2404.16251)