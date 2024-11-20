# “表情符号攻击”：一种于安全风险检测中误导法官大型语言模型的手段

发布时间：2024年11月01日

`LLM应用` `网络安全` `语言模型`

> Emoji Attack: A Method for Misleading Judge LLMs in Safety Risk Detection

# 摘要

> 越狱攻击揭示了大型语言模型（LLMs）如何会被恶意提示诱骗从而生成有害输出。为防范此类攻击，常将其他LLMs用作评判者来评估所生成内容的有害程度。然而，依赖LLMs充当评判者可能会在检测过程中引入偏差，进而影响评估的有效性。在本文中，我们指出，与其他LLMs类似，评判LLMs也受令牌分割偏差的影响。当令牌被分割为较小的子令牌时，就会产生这种偏差，改变其嵌入情况。这使得模型更难以检测有害内容。具体来说，这种偏差会导致子令牌在嵌入空间中与原始令牌存在显著差异，致使对有害内容做出错误的“安全”预测。为利用评判LLMs中的这一偏差，我们引入了表情符号攻击——一种在令牌内放置表情符号以加大子令牌与原始令牌嵌入差异的方法。这些表情符号会创建新的令牌，进一步扭曲令牌嵌入，加剧偏差。为应对表情符号攻击，我们设计了提示，助力LLMs过滤掉异常字符。不过，这种防御仍能被表情符号与其他字符的混合所绕过。表情符号攻击还能通过少样本学习与现有的越狱提示相结合，让LLMs生成带有表情符号的有害响应。这些响应常被评判LLMs误判为“安全”，使得攻击得以得逞。我们针对六个先进的评判LLMs开展的实验表明，表情符号攻击能让25％的有害响应绕过Llama Guard和Llama Guard 2的检测，而ShieldLM的检测绕过率高达75％。这些结果凸显出需要更强大的评判LLMs来应对这一漏洞。

> Jailbreaking attacks show how Large Language Models (LLMs) can be tricked into generating harmful outputs using malicious prompts. To prevent these attacks, other LLMs are often used as judges to evaluate the harmfulness of the generated content. However, relying on LLMs as judges can introduce biases into the detection process, which in turn compromises the effectiveness of the evaluation. In this paper, we show that Judge LLMs, like other LLMs, are also affected by token segmentation bias. This bias occurs when tokens are split into smaller sub-tokens, altering their embeddings. This makes it harder for the model to detect harmful content. Specifically, this bias can cause sub-tokens to differ significantly from the original token in the embedding space, leading to incorrect "safe" predictions for harmful content. To exploit this bias in Judge LLMs, we introduce the Emoji Attack -- a method that places emojis within tokens to increase the embedding differences between sub-tokens and their originals. These emojis create new tokens that further distort the token embeddings, exacerbating the bias. To counter the Emoji Attack, we design prompts that help LLMs filter out unusual characters. However, this defense can still be bypassed by using a mix of emojis and other characters. The Emoji Attack can also be combined with existing jailbreaking prompts using few-shot learning, which enables LLMs to generate harmful responses with emojis. These responses are often mistakenly labeled as "safe" by Judge LLMs, allowing the attack to slip through. Our experiments with six state-of-the-art Judge LLMs show that the Emoji Attack allows 25\% of harmful responses to bypass detection by Llama Guard and Llama Guard 2, and up to 75\% by ShieldLM. These results highlight the need for stronger Judge LLMs to address this vulnerability.

[Arxiv](https://arxiv.org/abs/2411.01077)