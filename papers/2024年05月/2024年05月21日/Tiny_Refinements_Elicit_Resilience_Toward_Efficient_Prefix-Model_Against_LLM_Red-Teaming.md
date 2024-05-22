# 细微调整，韧性倍增：探索高效前缀模型，抵御大型语言模型红队挑战

发布时间：2024年05月21日

`Agent

这篇论文主要介绍了一种基于大型语言模型（LLM）的“哨兵”模型，该模型通过添加额外的前缀令牌来重构输入提示，以降低LLM的响应毒性。论文中提到的“多代理集中批评的价值头共享机制”和“交错训练策略”表明，这是一种涉及多个代理（Agent）的复杂互动和优化策略。因此，这篇论文更适合归类于Agent，因为它主要关注的是如何通过代理机制来提升LLM的安全性和鲁棒性。` `人工智能安全`

> Tiny Refinements Elicit Resilience: Toward Efficient Prefix-Model Against LLM Red-Teaming

# 摘要

> 随着针对大型语言模型的红队策略日益增多，关于提升LLM防御策略安全性和鲁棒性的文献不足问题愈发凸显。本文提出的基于LLM的“哨兵”模型，作为一种即插即用的前缀模块，通过添加不到30个额外令牌重构输入提示，有效降低了目标LLM的响应毒性。该模型巧妙解决了微调大型模型时的参数效率和访问限制问题。我们采用交错训练策略，利用近端策略优化动态调整红队与哨兵模型，并引入多代理集中批评的价值头共享机制，以协调代理间的复杂互动。广泛实验涵盖文本到文本及文本到图像任务，证明了我们的方法在减少有毒输出上的有效性，即便面对如Llama-2、GPT-3.5和Stable-Diffusion等大型模型，也展现了我们框架在提升各类应用安全性和鲁棒性上的巨大潜力。

> With the proliferation of red-teaming strategies for Large Language Models (LLMs), the deficiency in the literature about improving the safety and robustness of LLM defense strategies is becoming increasingly pronounced. This paper introduces the LLM-based \textbf{sentinel} model as a plug-and-play prefix module designed to reconstruct the input prompt with just a few ($<30$) additional tokens, effectively reducing toxicity in responses from target LLMs. The sentinel model naturally overcomes the \textit{parameter inefficiency} and \textit{limited model accessibility} for fine-tuning large target models. We employ an interleaved training regimen using Proximal Policy Optimization (PPO) to optimize both red team and sentinel models dynamically, incorporating a value head-sharing mechanism inspired by the multi-agent centralized critic to manage the complex interplay between agents. Our extensive experiments across text-to-text and text-to-image demonstrate the effectiveness of our approach in mitigating toxic outputs, even when dealing with larger models like \texttt{Llama-2}, \texttt{GPT-3.5} and \texttt{Stable-Diffusion}, highlighting the potential of our framework in enhancing safety and robustness in various applications.

[Arxiv](https://arxiv.org/abs/2405.12604)