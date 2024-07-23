# 针对大型语言模型的情境上下文，我们提出了一种人类可理解的对抗性提示攻击方法。

发布时间：2024年07月19日

`LLM应用` `网络安全` `人工智能`

> Human-Interpretable Adversarial Prompt Attack on Large Language Models with Situational Context

# 摘要

> 以往研究多关注于通过无意义提示注入来测试大型语言模型的安全性，但这些方法易被检测。本研究则探索了将恶意但人类可理解的提示与对抗性注入结合，通过情境驱动的上下文重写，将无意义攻击转化为有意义提示，以此评估模型安全性。我们利用电影情境和独立对抗性插入，从IMDB数据集中提取情境，定义少样本思维链提示，验证了这种攻击在开源和专有LLM上的有效性。结果显示，仅需一次尝试即可成功攻击，且攻击可在不同LLM间转移。详细代码请访问 \url{https://anonymous.4open.science/r/Situation-Driven-Adversarial-Attacks-7BB1/README.md}。

> Previous research on testing the vulnerabilities in Large Language Models (LLMs) using adversarial attacks has primarily focused on nonsensical prompt injections, which are easily detected upon manual or automated review (e.g., via byte entropy). However, the exploration of innocuous human-understandable malicious prompts augmented with adversarial injections remains limited. In this research, we explore converting a nonsensical suffix attack into a sensible prompt via a situation-driven contextual re-writing. This allows us to show suffix conversion without any gradients, using only LLMs to perform the attacks, and thus better understand the scope of possible risks. We combine an independent, meaningful adversarial insertion and situations derived from movies to check if this can trick an LLM. The situations are extracted from the IMDB dataset, and prompts are defined following a few-shot chain-of-thought prompting. Our approach demonstrates that a successful situation-driven attack can be executed on both open-source and proprietary LLMs. We find that across many LLMs, as few as 1 attempt produces an attack and that these attacks transfer between LLMs. The link to our code is available at \url{https://anonymous.4open.science/r/Situation-Driven-Adversarial-Attacks-7BB1/README.md}.

[Arxiv](https://arxiv.org/abs/2407.14644)