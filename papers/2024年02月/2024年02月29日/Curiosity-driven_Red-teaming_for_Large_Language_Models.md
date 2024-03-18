# [为探究大型语言模型的安全性与潜在漏洞，我们引入了“好奇心驱动的红队”策略，通过模拟攻击者对大型语言模型进行挑战和检验，以挖掘其可能存在的问题。]

发布时间：2024年02月29日

`LLM应用`

> Curiosity-driven Red-teaming for Large Language Models

> 尽管LLMs在各类自然语言应用中蕴含无限可能，却有误生不当或有毒内容的风险。目前，检测LLM何时生成不受欢迎内容的方法是组织一支人类测试团队，即“红队”，来设计能触发LLM不良回应的输入提示。然而，单靠人力测试成本高昂且耗时。近期研究借助强化学习（RL），训练了一个专门的红队LLM，自动寻找最可能诱发目标LLM不良反应的测试案例。不过，现存的RL技术只能产出少量有效的测试案例，难以全面覆盖可能导致LLM输出不良信息的所有提示情境。为此，我们借鉴了广受研究的好奇心驱动探索原理——追求新颖性的方法，以此提升生成测试案例的覆盖率。我们提出的好奇心驱动红队策略（CRT）在扩大测试案例覆盖面的同时，保证甚至提升了它们的有效性。实验表明，CRT成功激发出已深度优化并依据人类偏好调整以避免毒性输出的LLaMA2模型产生毒性回应。相关代码已发布于 \url{https://github.com/Improbable-AI/curiosity_redteam}。

> Large language models (LLMs) hold great potential for many natural language applications but risk generating incorrect or toxic content. To probe when an LLM generates unwanted content, the current paradigm is to recruit a \textit{red team} of human testers to design input prompts (i.e., test cases) that elicit undesirable responses from LLMs. However, relying solely on human testers is expensive and time-consuming. Recent works automate red teaming by training a separate red team LLM with reinforcement learning (RL) to generate test cases that maximize the chance of eliciting undesirable responses from the target LLM. However, current RL methods are only able to generate a small number of effective test cases resulting in a low coverage of the span of prompts that elicit undesirable responses from the target LLM. To overcome this limitation, we draw a connection between the problem of increasing the coverage of generated test cases and the well-studied approach of curiosity-driven exploration that optimizes for novelty. Our method of curiosity-driven red teaming (CRT) achieves greater coverage of test cases while mantaining or increasing their effectiveness compared to existing methods. Our method, CRT successfully provokes toxic responses from LLaMA2 model that has been heavily fine-tuned using human preferences to avoid toxic outputs. Code is available at \url{https://github.com/Improbable-AI/curiosity_redteam}

[Arxiv](https://arxiv.org/abs/2402.19464)