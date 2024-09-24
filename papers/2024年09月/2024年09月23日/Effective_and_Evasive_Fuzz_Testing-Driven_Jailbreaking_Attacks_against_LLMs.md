# 针对 LLM 的有效且隐蔽的模糊测试驱动越狱攻击

发布时间：2024年09月23日

`LLM应用` `网络安全` `人工智能`

> Effective and Evasive Fuzz Testing-Driven Jailbreaking Attacks against LLMs

# 摘要

> 大型语言模型（LLM）虽在多任务中表现优异，但仍易受越狱攻击，即攻击者通过精心设计的提示诱导模型输出有害内容。现有越狱手段或依赖手动模板，难以扩展和适应，或生成的提示语义不连贯，易被检测。此外，多数方法需冗长提示，查询成本高。为此，我们提出了一种自动化黑箱越狱框架，结合黑箱模糊测试与定制设计，无需预设模板，从空种子池开始。我们还创新了三种问题依赖的变异策略，借助LLM助手生成语义连贯且简短的提示。同时，我们设计了两级判断模块，精准识别成功越狱。实验表明，我们的方法在GPT-3.5 turbo、GPT-4和Gemini-Pro等模型上，攻击成功率分别达90%、80%和74%，远超现有基线。即使在100个标记的限制下，对GPT-4的攻击成功率仍超78%。此外，我们的方法具有良好的可转移性和防御鲁棒性。发表后，我们将开源代码。

> Large Language Models (LLMs) have excelled in various tasks but are still vulnerable to jailbreaking attacks, where attackers create jailbreak prompts to mislead the model to produce harmful or offensive content. Current jailbreak methods either rely heavily on manually crafted templates, which pose challenges in scalability and adaptability, or struggle to generate semantically coherent prompts, making them easy to detect. Additionally, most existing approaches involve lengthy prompts, leading to higher query costs.In this paper, to remedy these challenges, we introduce a novel jailbreaking attack framework, which is an automated, black-box jailbreaking attack framework that adapts the black-box fuzz testing approach with a series of customized designs. Instead of relying on manually crafted templates, our method starts with an empty seed pool, removing the need to search for any related jailbreaking templates. We also develop three novel question-dependent mutation strategies using an LLM helper to generate prompts that maintain semantic coherence while significantly reducing their length. Additionally, we implement a two-level judge module to accurately detect genuine successful jailbreaks.
  We evaluated our method on 7 representative LLMs and compared it with 5 state-of-the-art jailbreaking attack strategies. For proprietary LLM APIs, such as GPT-3.5 turbo, GPT-4, and Gemini-Pro, our method achieves attack success rates of over 90%, 80%, and 74%, respectively, exceeding existing baselines by more than 60%. Additionally, our method can maintain high semantic coherence while significantly reducing the length of jailbreak prompts. When targeting GPT-4, our method can achieve over 78\% attack success rate even with 100 tokens. Moreover, our method demonstrates transferability and is robust to state-of-the-art defenses. We will open-source our codes upon publication.

[Arxiv](https://arxiv.org/abs/2409.14866)