# 丰富的字符串组合式越狱

发布时间：2024年11月01日

`LLM应用` `语言模型` `网络安全`

> Plentiful Jailbreaks with String Compositions

# 摘要

> 大型语言模型（LLMs）极易遭受诸多对抗性攻击和越狱手段的侵扰。白帽攻击者，即“红队成员”，常用的一招是利用字符串级别的混淆来处理模型的输入与输出，比如 leetspeak、旋转密码、Base64、ASCII 等等。我们的工作将这些基于编码的攻击统一在可逆字符串变换的框架下，从而对其加以拓展。由于具备可逆性，我们能够设计出任意的“字符串组合”，即一系列变换的序列，并且能够通过编程实现端到端的编码与解码。我们设计了一种自动的 n 中选优攻击，从数量极为庞大的字符串组合中采样。我们的越狱手段在 HarmBench 上针对几个前沿领先模型进行评估时，取得了颇具竞争力的攻击成功率，这表明基于编码的攻击即便在先进的 LLMs 中依旧是个长期存在的漏洞。

> Large language models (LLMs) remain vulnerable to a slew of adversarial attacks and jailbreaking methods. One common approach employed by white-hat attackers, or \textit{red-teamers}, is to process model inputs and outputs using string-level obfuscations, which can include leetspeak, rotary ciphers, Base64, ASCII, and more. Our work extends these encoding-based attacks by unifying them in a framework of invertible string transformations. With invertibility, we can devise arbitrary \textit{string compositions}, defined as sequences of transformations, that we can encode and decode end-to-end programmatically. We devise a automated best-of-n attack that samples from a combinatorially large number of string compositions. Our jailbreaks obtain competitive attack success rates on several leading frontier models when evaluated on HarmBench, highlighting that encoding-based attacks remain a persistent vulnerability even in advanced LLMs.

[Arxiv](https://arxiv.org/abs/2411.01084)