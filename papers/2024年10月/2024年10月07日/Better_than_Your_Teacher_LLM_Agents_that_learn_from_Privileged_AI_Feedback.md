# 超越导师：LLM 代理从特权 AI 反馈中学习

发布时间：2024年10月07日

`Agent` `人工智能`

> Better than Your Teacher: LLM Agents that learn from Privileged AI Feedback

# 摘要

> 尽管 LLM 在决策方面表现出色，但现有方法缺乏从任务执行中的错误自动自我改进的能力。我们提出了 LEAP，一个通过 AI 专家教师反馈不断迭代微调 LLM 代理的框架。关键在于为专家教师提供训练时可见但测试时隐藏的特权信息，使弱专家也能提供精准指导，显著提升学生代理的性能。我们在多种决策任务中测试了 LEAP，包括文本游戏、网页导航和交互编码，结果显示 LEAP 不仅超越了基线方法，还让弱学生模型超越了强教师模型，并实现了自我改进。理论分析表明，LEAP 的成功在于平衡特权信息与学生的可实现性，这一结论已通过实证验证。代码已公开，详见 https://leap-llm.github.io。

> While large language models (LLMs) show impressive decision-making abilities, current methods lack a mechanism for automatic self-improvement from errors during task execution. We propose LEAP, an iterative fine-tuning framework that continually improves LLM agents using feedback from AI expert teachers. Our key insight is to equip the expert teachers with a privileged state -- information that is available during training but hidden at test time. This allows even weak experts to provide precise guidance, significantly improving the student agent's performance without access to privileged information at test time. We evaluate LEAP on diverse decision-making benchmarks, including text-based games (ALFWorld), web navigation (WebShop), and interactive coding (Intercode Bash). Our experiments show that LEAP (1) outperforms behavior cloning and ReAct baselines (2) enables weak student models (e.g., Llama3-8B) to exceed the performance of strong teacher models (GPT4-o), and (3) allows weak models to self-improve using privileged versions of themselves. We also provide a theoretical analysis showing that LEAP's success hinges on balancing privileged information with the student's realizability, which we empirically validate. Our code is available at https://leap-llm.github.io

[Arxiv](https://arxiv.org/abs/2410.05434)