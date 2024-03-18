# Neural Exec：针对提示注入攻击，研究并借鉴执行触发器的学习机制

发布时间：2024年03月06日

`Agent`

> Neural Exec: Learning (and Learning from) Execution Triggers for Prompt Injection Attacks

> 我们创新性地提出了一种名为Neural Exec的新一代提示注入攻击，不再依靠人工编写的特定字符串。研究揭示，通过将执行触发器生成视为一个可微优化问题，并利用学习型方法来自动生成触发器是可行的。实验结果显示，蓄意的攻击者能够创造出远超当前手工制作触发器效能的新触发器，这些触发器形态各异、属性灵活且功能多样。进一步来说，我们证实攻击者能设计并产出可在类似RAG应用中经受住多级预处理流程考验的Neural Execs。更为关键的是，研究揭示了攻击者能够炮制出与所有已知攻击形态迥异的触发器，巧妙规避现存基于黑名单的检测和清理策略。

> We introduce a new family of prompt injection attacks, termed Neural Exec. Unlike known attacks that rely on handcrafted strings (e.g., "Ignore previous instructions and..."), we show that it is possible to conceptualize the creation of execution triggers as a differentiable search problem and use learning-based methods to autonomously generate them.
  Our results demonstrate that a motivated adversary can forge triggers that are not only drastically more effective than current handcrafted ones but also exhibit inherent flexibility in shape, properties, and functionality. In this direction, we show that an attacker can design and generate Neural Execs capable of persisting through multi-stage preprocessing pipelines, such as in the case of Retrieval-Augmented Generation (RAG)-based applications. More critically, our findings show that attackers can produce triggers that deviate markedly in form and shape from any known attack, sidestepping existing blacklist-based detection and sanitation approaches.

[Arxiv](https://arxiv.org/abs/2403.03792)