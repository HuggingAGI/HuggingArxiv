![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 本研究旨在探究在多轮大型语言模型互动中出现的提示泄露现象，以及为这种交互模式设计的黑箱防御机制。
发布时间：2024年04月24日

`RAG`
> 大型语言模型（LLMs）中的提示泄露问题，对检索增强生成（RAG）系统构成了严重的安全和隐私风险。尽管如此，对于多轮LLM交互中的泄露现象及其缓解措施，目前还缺乏系统化的研究。本研究深入探讨了不同领域内，以及10种闭源和开源LLMs在面对提示泄露时的脆弱性。我们构建的多轮威胁模型巧妙利用了LLM的“拍马屁”效应，并通过深入分析，揭示了LLM回应中任务指令与知识泄露的关系。在模拟的多轮对话场景中，我们的模型将攻击者的平均成功率提升至86.2%，在某些情况下，如GPT-4和claude-1.3，泄露率甚至高达99%。我们还发现，部分黑盒LLMs，例如Gemini，在不同领域的泄露敏感性上表现出差异，它们在新闻领域比在医疗领域更容易泄露上下文信息。通过一系列实验，我们评估了六种黑盒防御策略的具体效果，包括RAG场景下的查询重写技术。我们提出的多层次防御策略组合，尽管将黑盒LLMs的平均攻击成功率降低到了5.3%，但仍显示出提升空间，为LLM安全研究的未来指明了方向。



- 论文原文 [https://arxiv.org/abs/2404.16251](https://arxiv.org/abs/2404.16251)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)