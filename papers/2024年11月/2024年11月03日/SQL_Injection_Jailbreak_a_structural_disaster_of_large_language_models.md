# SQL 注入越狱：大型语言模型的结构性灾祸

发布时间：2024年11月03日

`LLM应用` `语言模型` `网络安全`

> SQL Injection Jailbreak: a structural disaster of large language models

# 摘要

> 近年来，大型语言模型（LLMs）的迅猛发展为众多领域注入了新的活力，创造了可观的社会和经济效益。然而，LLMs 的快速进步也带来了新的安全隐患。“越狱”这种通过精心设计的提示诱使 LLMs 输出有害内容的攻击方式，给 LLMs 的安全可靠发展带来了挑战。以往的越狱攻击方法主要借助模型的内部能力。其中，一类利用模型的隐性能力进行越狱攻击，攻击者并不清楚攻击成功的具体原因；另一类则利用模型的显性能力进行越狱攻击，攻击者知晓攻击成功的缘由。比如，这些攻击利用了模型在编码、上下文学习或者理解 ASCII 字符等方面的能力。不过，这些早期的越狱攻击存在一定局限性，因为它们仅仅利用了模型的固有能力。在本文中，我们提出了一种全新的越狱方法——SQL 注入越狱（SIJ），它借助 LLMs 构建输入提示，将越狱信息注入用户提示，从而成功实现对 LLMs 的越狱。我们的 SIJ 方法在 AdvBench 环境下对五个知名的开源 LLMs 达成了近 100％的攻击成功率，且相比以往方法，所耗费的时间成本更低。尤为重要的是，SIJ 揭示了 LLMs 中一个亟待解决的新漏洞。为此，我们提出了一种名为“自我提醒密钥”的防御方法，并通过实验证明了其有效性。我们的代码可在 \href{https://github.com/weiyezhimeng/SQL-Injection-Jailbreak}{https://github.com/weiyezhimeng/SQL-Injection-Jailbreak} 获取。

> In recent years, the rapid development of large language models (LLMs) has brought new vitality to the various domains and generated substantial social and economic benefits. However, the swift advancement of LLMs has introduced new security vulnerabilities. Jailbreak, a form of attack that induces LLMs to output harmful content through carefully crafted prompts, poses a challenge to the safe and trustworthy development of LLMs. Previous jailbreak attack methods primarily exploited the internal capabilities of the model. Among them, one category leverages the model's implicit capabilities for jailbreak attacks, where the attacker is unaware of the exact reasons for the attack's success. The other category utilizes the model's explicit capabilities for jailbreak attacks, where the attacker understands the reasons for the attack's success. For example, these attacks exploit the model's abilities in coding, contextual learning, or understanding ASCII characters. However, these earlier jailbreak attacks have certain limitations, as they only exploit the inherent capabilities of the model. In this paper, we propose a novel jailbreak method, SQL Injection Jailbreak (SIJ), which utilizes the construction of input prompts by LLMs to inject jailbreak information into user prompts, enabling successful jailbreak of the LLMs. Our SIJ method achieves nearly 100\% attack success rates on five well-known open-source LLMs in the context of AdvBench, while incurring lower time costs compared to previous methods. More importantly, SIJ reveals a new vulnerability in LLMs that urgently needs to be addressed. To this end, we propose a defense method called Self-Reminder-Key and demonstrate its effectiveness through experiments. Our code is available at \href{https://github.com/weiyezhimeng/SQL-Injection-Jailbreak}{https://github.com/weiyezhimeng/SQL-Injection-Jailbreak}.

[Arxiv](https://arxiv.org/abs/2411.01565)