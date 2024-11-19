# AutoPT：我们离端到端的自动化网络渗透测试还有多远？

发布时间：2024年11月02日

`Agent` `网络安全` `渗透测试`

> AutoPT: How Far Are We from the End2End Automated Web Penetration Testing?

# 摘要

> 渗透测试对于保障网络安全极为关键，能够提前察觉并修复漏洞，避免数据泄露及严重后果。大型语言模型（LLMs）强大的推理能力在众多领域都有显著进步，基于LLMs的代理的发展潜力有望彻底变革网络安全渗透测试行业。在此次工作中，我们借助真实的渗透测试环境构建了一个全面的端到端渗透测试基准，以探究基于LLMs的代理在该领域的能力。我们的成果显示，这些代理熟悉渗透测试任务的框架，但在生成精确命令和执行完整流程方面仍存在局限。于是，我们总结了当下的挑战，如难以留存完整的消息历史以及代理易陷入困境等趋势。
基于上述认识，我们提出了一种渗透测试状态机（PSM），运用有限状态机（FSM）方法来应对这些限制。接着，我们引入了AutoPT，这是一个基于LLMs驱动的PSM原则的自动化渗透测试代理，它借助了LLM的固有推理能力和状态机的约束框架。我们的评估结果表明，AutoPT在GPT-4o迷你模型上优于基线框架ReAct，将基准目标上的任务完成率从22%提升至41%。与基线框架和人工操作相比，AutoPT还进一步减少了时间和经济成本。所以，我们的AutoPT推动了自动化渗透测试的发展，对学术界和工业界都产生了重大影响。

> Penetration testing is essential to ensure Web security, which can detect and fix vulnerabilities in advance, and prevent data leakage and serious consequences. The powerful inference capabilities of large language models (LLMs) have made significant progress in various fields, and the development potential of LLM-based agents can revolutionize the cybersecurity penetration testing industry. In this work, we establish a comprehensive end-to-end penetration testing benchmark using a real-world penetration testing environment to explore the capabilities of LLM-based agents in this domain. Our results reveal that the agents are familiar with the framework of penetration testing tasks, but they still face limitations in generating accurate commands and executing complete processes. Accordingly, we summarize the current challenges, including the difficulty of maintaining the entire message history and the tendency for the agent to become stuck.
  Based on the above insights, we propose a Penetration testing State Machine (PSM) that utilizes the Finite State Machine (FSM) methodology to address these limitations. Then, we introduce AutoPT, an automated penetration testing agent based on the principle of PSM driven by LLMs, which utilizes the inherent inference ability of LLM and the constraint framework of state machines. Our evaluation results show that AutoPT outperforms the baseline framework ReAct on the GPT-4o mini model and improves the task completion rate from 22% to 41% on the benchmark target. Compared with the baseline framework and manual work, AutoPT also reduces time and economic costs further. Hence, our AutoPT has facilitated the development of automated penetration testing and significantly impacted both academia and industry.

[Arxiv](https://arxiv.org/abs/2411.01236)