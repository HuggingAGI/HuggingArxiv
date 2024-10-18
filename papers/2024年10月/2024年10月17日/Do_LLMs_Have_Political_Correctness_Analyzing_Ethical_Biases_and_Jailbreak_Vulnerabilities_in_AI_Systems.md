# LLM 是否能做到政治正确？探讨 AI 系统中的伦理偏见与越狱风险

发布时间：2024年10月17日

`LLM应用` `人工智能安全` `社会伦理`

> Do LLMs Have Political Correctness? Analyzing Ethical Biases and Jailbreak Vulnerabilities in AI Systems

# 摘要

> 尽管 LLM 在多任务中表现出色，但存在“越狱”等安全风险，恶意输入可能诱导其生成有害内容。为应对这些风险，开发者采用了多种安全措施，包括预训练数据过滤、监督微调、人类反馈强化学习及红队演练，这些措施常引入类似政治正确性的有意偏见，以确保模型道德行为。本文探讨了这些安全偏见，并研究了规避方法。研究发现，GPT-4o 模型中，非二元与顺性别关键词、白人与黑人关键词的越狱成功率分别相差 20% 和 16%，即使提示其他部分相同。我们提出 PCJailbreak 概念，强调安全偏见的内在风险，并引入 PCDefense 防御方法，通过预生成防御提示防止越狱，无需额外推理成本。研究强调，LLM 开发者需在安全措施设计中采取更负责任的态度。

> Although large language models (LLMs) demonstrate impressive proficiency in various tasks, they present potential safety risks, such as `jailbreaks', where malicious inputs can coerce LLMs into generating harmful content. To address these issues, many LLM developers have implemented various safety measures to align these models. This alignment involves several techniques, including data filtering during pre-training, supervised fine-tuning, reinforcement learning from human feedback, and red-teaming exercises. These methods often introduce deliberate and intentional biases similar to Political Correctness (PC) to ensure the ethical behavior of LLMs. In this paper, we delve into the intentional biases injected into LLMs for safety purposes and examine methods to circumvent these safety alignment techniques. Notably, these intentional biases result in a jailbreaking success rate in GPT-4o models that differs by 20% between non-binary and cisgender keywords and by 16% between white and black keywords, even when the other parts of the prompts are identical. We introduce the concept of PCJailbreak, highlighting the inherent risks posed by these safety-induced biases. Additionally, we propose an efficient defense method PCDefense, which prevents jailbreak attempts by injecting defense prompts prior to generation. PCDefense stands as an appealing alternative to Guard Models, such as Llama-Guard, that require additional inference cost after text generation. Our findings emphasize the urgent need for LLM developers to adopt a more responsible approach when designing and implementing safety measures.

[Arxiv](https://arxiv.org/abs/2410.13334)