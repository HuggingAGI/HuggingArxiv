# 在大型语言模型中，长篇内容的真实性问题

发布时间：2024年03月27日

`LLM应用` `事实核查` `自动评估`

> Long-form factuality in large language models

# 摘要

> 在开放式主题的长篇幅回答中，大型语言模型（LLMs）常出现事实性错误。为此，我们利用GPT-4创建了LongFact，一个包含38个主题的数千问题集，以评估模型的长篇幅事实性。我们提出了一种名为搜索增强事实性评估器（SAFE）的方法，让LLM代理自动评估长篇幅内容的事实性。SAFE通过将长篇幅响应分解为单个事实，并利用Google搜索的多步骤推理过程来评估每个事实的准确性。我们还提出了扩展F1分数，作为衡量长篇幅事实性的综合指标，平衡响应中支持事实的百分比与用户期望的响应长度中提供事实的百分比。实证结果显示，LLM代理在评估约16,000个独立事实时，与人类评估者有72%的一致性，且在100个分歧案例中，SAFE正确率高达76%，成本却不到人类的1/20。此外，我们还对LongFact中的十三种语言模型进行了基准测试，发现更大的模型在长篇幅事实性方面表现更佳。相关资源已在https://github.com/google-deepmind/long-form-factuality发布。

> Large language models (LLMs) often generate content that contains factual errors when responding to fact-seeking prompts on open-ended topics. To benchmark a model's long-form factuality in open domains, we first use GPT-4 to generate LongFact, a prompt set comprising thousands of questions spanning 38 topics. We then propose that LLM agents can be used as automated evaluators for long-form factuality through a method which we call Search-Augmented Factuality Evaluator (SAFE). SAFE utilizes an LLM to break down a long-form response into a set of individual facts and to evaluate the accuracy of each fact using a multi-step reasoning process comprising sending search queries to Google Search and determining whether a fact is supported by the search results. Furthermore, we propose extending F1 score as an aggregated metric for long-form factuality. To do so, we balance the percentage of supported facts in a response (precision) with the percentage of provided facts relative to a hyperparameter representing a user's preferred response length (recall).
  Empirically, we demonstrate that LLM agents can achieve superhuman rating performance - on a set of ~16k individual facts, SAFE agrees with crowdsourced human annotators 72% of the time, and on a random subset of 100 disagreement cases, SAFE wins 76% of the time. At the same time, SAFE is more than 20 times cheaper than human annotators. We also benchmark thirteen language models on LongFact across four model families (Gemini, GPT, Claude, and PaLM-2), finding that larger language models generally achieve better long-form factuality. LongFact, SAFE, and all experimental code are available at https://github.com/google-deepmind/long-form-factuality.

[Arxiv](https://arxiv.org/abs/2403.18802)