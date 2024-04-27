# 探究在多轮次的大型语言模型互动中，提示泄露的影响以及黑盒防御机制。

发布时间：2024年04月24日

`分类：LLM应用` `安全和隐私` `人工智能`

> Investigating the prompt leakage effect and black-box defenses for multi-turn LLM interactions

# 摘要

> 大型语言模型（LLMs）中的提示泄露问题在检索增强生成（RAG）系统中尤为突出，对安全和隐私构成了严峻挑战。尽管如此，对于多轮对话中LLM的泄露问题及其应对策略，目前还缺乏系统化的研究。本研究深入探讨了不同领域内10种封闭与开源LLMs在面对提示泄露时的脆弱性。我们创新的多轮威胁模型巧妙利用了LLM的“拍马屁”效应，并对LLM回应中的任务指令泄露和知识泄露进行了深入分析。在模拟的多轮对话场景中，我们的模型成功将攻击成功率提升至86.2%，特别是在针对GPT-4和claude-1.3的测试中，泄露率高达99%。研究发现，某些黑盒LLMs，例如Gemini，在不同领域的泄露敏感性表现出差异性，它们在新闻领域的上下文知识泄露风险高于医疗领域。我们还对六种黑盒防御策略进行了实验评估，包括在RAG场景中应用的查询重写器。我们提出的多层次防御策略组合，即使在黑盒LLMs中，仍能将攻击成功率控制在5.3%，这表明LLM安全性研究仍有提升空间，并为未来的研究方向提供了指引。

> Prompt leakage in large language models (LLMs) poses a significant security and privacy threat, particularly in retrieval-augmented generation (RAG) systems. However, leakage in multi-turn LLM interactions along with mitigation strategies has not been studied in a standardized manner. This paper investigates LLM vulnerabilities against prompt leakage across 4 diverse domains and 10 closed- and open-source LLMs. Our unique multi-turn threat model leverages the LLM's sycophancy effect and our analysis dissects task instruction and knowledge leakage in the LLM response. In a multi-turn setting, our threat model elevates the average attack success rate (ASR) to 86.2%, including a 99% leakage with GPT-4 and claude-1.3. We find that some black-box LLMs like Gemini show variable susceptibility to leakage across domains - they are more likely to leak contextual knowledge in the news domain compared to the medical domain. Our experiments measure specific effects of 6 black-box defense strategies, including a query-rewriter in the RAG scenario. Our proposed multi-tier combination of defenses still has an ASR of 5.3% for black-box LLMs, indicating room for enhancement and future direction for LLM security research.

[Arxiv](https://arxiv.org/abs/2404.16251)