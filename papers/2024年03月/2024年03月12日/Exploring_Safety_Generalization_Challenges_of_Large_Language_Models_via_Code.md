# 我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。

发布时间：2024年03月12日

`LLM应用`

> Exploring Safety Generalization Challenges of Large Language Models via Code

# 摘要

> 随着LLMs的飞速发展，它们在自然语言处理方面的卓越表现也引发了对其潜在滥用的担忧。尽管已有监督微调和借助人类反馈的强化学习等手段提升其安全性，但这些方法大多局限于自然语言领域，难以推广至其他领域。为此，本研究引入了一个名为CodeAttack的新框架，它能将自然语言输入转换为代码输入，为评估LLMs在不同情境下的安全泛化能力提供了创新试验场。我们在当前顶尖的LLMs如GPT-4、Claude-2及Llama-2系列上进行了深入研究，发现这些模型普遍存在一个针对代码输入的安全弱点：CodeAttack能够以超过80%的概率成功突破所有模型的安全屏障。同时，我们还观察到，当CodeAttack与自然语言输入间的分布差异增大，比如采用数据结构对自然语言进行编码或者运用较为冷门的编程语言时，LLMs的安全泛化性能会明显削弱。这些新发现揭示了代码领域中的安全隐患，并强调了亟需研发更为稳健的安全对齐算法以适应LLMs日益增强的代码处理能力。

> The rapid advancement of Large Language Models (LLMs) has brought about remarkable capabilities in natural language processing but also raised concerns about their potential misuse. While strategies like supervised fine-tuning and reinforcement learning from human feedback have enhanced their safety, these methods primarily focus on natural languages, which may not generalize to other domains. This paper introduces CodeAttack, a framework that transforms natural language inputs into code inputs, presenting a novel environment for testing the safety generalization of LLMs. Our comprehensive studies on state-of-the-art LLMs including GPT-4, Claude-2, and Llama-2 series reveal a common safety vulnerability of these models against code input: CodeAttack consistently bypasses the safety guardrails of all models more than 80\% of the time. Furthermore, we find that a larger distribution gap between CodeAttack and natural language leads to weaker safety generalization, such as encoding natural language input with data structures or using less popular programming languages. These findings highlight new safety risks in the code domain and the need for more robust safety alignment algorithms to match the code capabilities of LLMs.

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x1.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x2.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x3.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x4.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x5.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x6.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x7.png)

![我们通过编码实践深入探究大型语言模型在安全性泛化方面所面临的挑战。](../../../paper_images/2403.07865/x8.png)

[Arxiv](https://arxiv.org/abs/2403.07865)