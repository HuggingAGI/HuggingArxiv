# BackdoorLLM：大型语言模型后门攻击的综合评估基准

发布时间：2024年08月22日

`LLM应用` `人工智能安全` `网络安全`

> BackdoorLLM: A Comprehensive Benchmark for Backdoor Attacks on Large Language Models

# 摘要

> 生成型大型语言模型 (LLM) 虽在多任务上取得显著进展，但仍易受后门攻击，即特定触发词可诱导模型生成恶意响应。尽管后门研究多聚焦于视觉或文本分类，文本生成领域的后门攻击却鲜受关注。为此，我们推出了首个全面研究 LLM 后门攻击的基准 \textit{BackdoorLLM}，其特色包括：标准化训练流程的后门基准库、多元攻击策略（如数据中毒、权重中毒等）、涵盖 7 场景 6 架构的 200 余次实验评估，以及对 LLM 后门攻击有效性与局限的深入洞察。我们期望 \textit{BackdoorLLM} 能提升业界对后门威胁的警觉，并助力 AI 安全发展。相关代码已公开于 \url{https://github.com/bboylyg/BackdoorLLM}。

> Generative Large Language Models (LLMs) have made significant strides across various tasks, but they remain vulnerable to backdoor attacks, where specific triggers in the prompt cause the LLM to generate adversary-desired responses. While most backdoor research has focused on vision or text classification tasks, backdoor attacks in text generation have been largely overlooked. In this work, we introduce \textit{BackdoorLLM}, the first comprehensive benchmark for studying backdoor attacks on LLMs. \textit{BackdoorLLM} features: 1) a repository of backdoor benchmarks with a standardized training pipeline, 2) diverse attack strategies, including data poisoning, weight poisoning, hidden state attacks, and chain-of-thought attacks, 3) extensive evaluations with over 200 experiments on 8 attacks across 7 scenarios and 6 model architectures, and 4) key insights into the effectiveness and limitations of backdoors in LLMs. We hope \textit{BackdoorLLM} will raise awareness of backdoor threats and contribute to advancing AI safety. The code is available at \url{https://github.com/bboylyg/BackdoorLLM}.

[Arxiv](https://arxiv.org/abs/2408.12798)