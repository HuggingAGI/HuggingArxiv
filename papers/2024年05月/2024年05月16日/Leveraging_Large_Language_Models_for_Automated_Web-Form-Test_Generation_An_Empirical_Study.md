# 大型语言模型助力自动化网页表单测试生成：实证探索之旅在这项研究中，我们探索了如何利用大型语言模型（LLMs）的强大能力，自动化生成网页表单测试。通过一系列实证分析，我们揭示了LLMs在提高测试效率和准确性方面的潜力，为软件测试领域带来了新的视角和可能性。

发布时间：2024年05月16日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在网页表单测试生成方面的应用，特别是评估了不同LLMs在生成高质量测试用例方面的表现。它关注的是LLMs在实际应用场景中的效能，特别是在软件测试领域，这与LLM的应用相关，而不是专注于LLM的理论研究或Agent的设计与实现，也不是关于检索增强生成（RAG）的研究。因此，根据论文摘要的内容，它最符合LLM应用这一分类。` `软件测试` `网页开发`

> Leveraging Large Language Models for Automated Web-Form-Test Generation: An Empirical Study

# 摘要

> 网页表单测试是确保网页应用质量的关键，它关注用户与表单的互动。自动生成测试用例在网页表单测试中仍是一大挑战，因为网页的复杂结构使得自动捕捉上下文信息变得困难。大型语言模型（LLMs）在生成上下文相关的文本方面展现出巨大潜力，尤其是OpenAI的GPT模型在软件测试领域备受瞩目。然而，由于信息安全顾虑，这些模型在实际应用中可能受限。目前，尚未有研究对比不同LLMs在网页表单测试生成方面的表现。为此，我们开展了一项深入研究，评估了11种LLMs在30个开源Java网页应用的146个表单上的效果。研究发现，GPT-4、GLM-4和Baichuan2在生成高质量网页表单测试方面表现突出。相比之下，其他LLMs在生成适当测试方面遇到困难，导致成功提交率（SSRs）大幅下降。尽管如此，某些LLMs的SSRs超过了GPT-3.5，显示出它们在生成合适测试方面的优势。我们还发现，当提示包含完整且清晰的网页表单上下文信息时，所有LLMs都能生成更有效的测试。最后，我们分享了如何利用LLMs优化自动网页表单测试的策略。

> The testing of web forms is an essential activity for ensuring the quality of web applications, which mainly involves evaluating the interactions between users and forms. Automated test-case generation remains a challenge for web-form testing: Due to the complex, multi-level structure of web pages, it can be difficult to automatically capture their inherent contextual information for inclusion in the tests. Large Language Models (LLMs) have great potential for contextual text generation. OpenAI's GPT LLMs have been receiving a lot of attention in software testing, however, they may fail to be applied in practice because of information security concerns. To the best of our knowledge, no comparative study examining different LLMs has yet been reported for web-form-test generation. To address this gap in the literature, we conducted a comprehensive empirical study investigating the effectiveness of 11 LLMs on 146 web forms from 30 open-source Java web applications. According to the experimental results, different LLMs can achieve different testing effectiveness. Notably, the GPT-4, GLM-4, and Baichuan2 LLMs can generate better web-form tests than the others. Compared with GPT-4, other LLMs find it difficult to generate appropriate tests for web forms, resulting in decreased successfully-submitted rates (SSRs, measured by the proportions of the LLMs-generated web-form tests that can be successfully inserted into the web forms and submitted) ranging from 9.10% to 74.15%. Nevertheless, some LLMs achieve higher SSRs than GPT-3.5, indicating a better ability to generate appropriate tests for web forms. Our findings also show that, for all LLMs, when the designed prompts include complete and clear contextual information about the web forms, more effective web-form tests were generated. Finally, we offer some insights for using LLMs to guide automated web-form testing.

[Arxiv](https://arxiv.org/abs/2405.09965)