# 非标准Unicode字符对大型语言模型安全与理解的双重挑战

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）在性能上的挑战，包括越狱、幻觉和理解错误，并通过标准化测试对十五种模型进行了比较分析。此外，论文还分析了非标准Unicode字符对模型保护机制的影响，并提出了改进建议。这些内容更偏向于对LLM理论层面的探讨和分析，而不是具体的应用、Agent行为或RAG（检索增强生成）技术。因此，将其归类为LLM理论是合适的。` `模型评估`

> Impact of Non-Standard Unicode Characters on Security and Comprehension in Large Language Models

# 摘要

> 大型语言模型的进步是显著提高了自然语言处理的能力，但仍面临越狱、幻觉和理解错误等挑战。本报告对十五种模型的性能进行了比较分析，通过标准化测试评估了它们在越狱、幻觉和理解错误方面的表现。我们的研究发现，这些模型存在固有弱点，对人类级别的语言理解能力提出了质疑。此外，我们分析了非标准Unicode字符对模型保护机制的影响，发现这些机制在面对非标准字符时效果减弱，增加了模型对内容政策违规和提示泄露的脆弱性。因此，我们建议在LLM训练数据中加入非标准Unicode文本，以提升模型的鲁棒性。

> The advancement of large language models has significantly improved natural language processing. However, challenges such as jailbreaks (prompt injections that cause an LLM to follow instructions contrary to its intended use), hallucinations (generating incorrect or misleading information), and comprehension errors remain prevalent. In this report, we present a comparative analysis of the performance of fifteen distinct models, with each model undergoing a standardized test comprising 38 queries across three key metrics: jailbreaks, hallucinations, and comprehension errors. The models are assessed based on the total occurrences of jailbreaks, hallucinations, and comprehension errors. Our work exposes these models' inherent vulnerabilities and challenges the notion of human-level language comprehension of these models. We have empirically analysed the impact of non-standard Unicode characters on LLMs and their safeguarding mechanisms on the best-performing LLMs, including GPT-4, Gemini 1.5 Pro, LlaMA-3-70B, and Claude 3 Opus. By incorporating alphanumeric symbols from Unicode outside the standard Latin block and variants of characters in other languages, we observed a reduction in the efficacy of guardrails implemented through Reinforcement Learning Human Feedback (RLHF). Consequently, these models exhibit heightened vulnerability to content policy breaches and prompt leakage. Our study also suggests a need to incorporate non-standard Unicode text in LLM training data to enhance the capabilities of these models.

[Arxiv](https://arxiv.org/abs/2405.14490)