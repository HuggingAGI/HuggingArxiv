# 针对大型语言模型的人类可解释情境对抗提示攻击

发布时间：2024年07月19日

`LLM应用` `网络安全` `人工智能`

> Human-Interpretable Adversarial Prompt Attack on Large Language Models with Situational Context

# 摘要

> 以往研究多关注于通过无意义提示注入来测试大型语言模型的安全性，但这些方法易被检测。本研究则探索了将恶意但人类可理解的提示与对抗性注入结合，通过情境驱动的重写将无意义攻击转化为有意义提示。我们利用电影情境和独立对抗性插入，验证了这种策略能有效欺骗各类LLM。实验表明，仅需一次尝试即可成功攻击，且攻击效果在不同LLM间可迁移。详细代码请访问 \url{https://anonymous.4open.science/r/Situation-Driven-Adversarial-Attacks-7BB1/README.md}。

> Previous research on testing the vulnerabilities in Large Language Models (LLMs) using adversarial attacks has primarily focused on nonsensical prompt injections, which are easily detected upon manual or automated review (e.g., via byte entropy). However, the exploration of innocuous human-understandable malicious prompts augmented with adversarial injections remains limited. In this research, we explore converting a nonsensical suffix attack into a sensible prompt via a situation-driven contextual re-writing. This allows us to show suffix conversion without any gradients, using only LLMs to perform the attacks, and thus better understand the scope of possible risks. We combine an independent, meaningful adversarial insertion and situations derived from movies to check if this can trick an LLM. The situations are extracted from the IMDB dataset, and prompts are defined following a few-shot chain-of-thought prompting. Our approach demonstrates that a successful situation-driven attack can be executed on both open-source and proprietary LLMs. We find that across many LLMs, as few as 1 attempt produces an attack and that these attacks transfer between LLMs. The link to our code is available at \url{https://anonymous.4open.science/r/Situation-Driven-Adversarial-Attacks-7BB1/README.md}.

[Arxiv](https://arxiv.org/abs/2407.14644)