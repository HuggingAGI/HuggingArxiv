# AgentCourt：模拟法庭，律师代理对抗进化

发布时间：2024年08月15日

`Agent` `人工智能`

> AgentCourt: Simulating Court with Adversarial Evolvable Lawyer Agents

# 摘要

> 本文介绍的 AgentCourt 系统，通过模拟法庭全过程，让法官、律师等角色由 LLM 驱动的自主代理扮演。我们的目标是让律师代理在模拟中学习辩论技巧和提升法律素养。为此，我们采用了对抗性进化策略。AgentCourt 能基于知识库和 LLM 模拟法庭动态，使律师代理从真实案例中不断学习。实验表明，经过千次模拟对抗，律师代理的法律处理能力显著提升。我们还邀请专业律师评估，结果显示代理在反应速度、专业度和逻辑性上均有显著进步。这项研究为法律领域应用 LLM 技术开辟了新途径。项目代码已公开在 GitHub。

> In this paper, we present a simulation system called AgentCourt that simulates the entire courtroom process. The judge, plaintiff's lawyer, defense lawyer, and other participants are autonomous agents driven by large language models (LLMs). Our core goal is to enable lawyer agents to learn how to argue a case, as well as improving their overall legal skills, through courtroom process simulation. To achieve this goal, we propose an adversarial evolutionary approach for the lawyer-agent. Since AgentCourt can simulate the occurrence and development of court hearings based on a knowledge base and LLM, the lawyer agents can continuously learn and accumulate experience from real court cases. The simulation experiments show that after two lawyer-agents have engaged in a thousand adversarial legal cases in AgentCourt (which can take a decade for real-world lawyers), compared to their pre-evolutionary state, the evolved lawyer agents exhibit consistent improvement in their ability to handle legal tasks. To enhance the credibility of our experimental results, we enlisted a panel of professional lawyers to evaluate our simulations. The evaluation indicates that the evolved lawyer agents exhibit notable advancements in responsiveness, as well as expertise and logical rigor. This work paves the way for advancing LLM-driven agent technology in legal scenarios. Code is available at https://github.com/relic-yuexi/AgentCourt.

[Arxiv](https://arxiv.org/abs/2408.08089)