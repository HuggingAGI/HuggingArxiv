# LLMStinger：使用经过 RL 微调的 LLM 来破解 LLM

发布时间：2024年11月13日

`LLM应用` `网络安全` `人工智能`

> LLMStinger: Jailbreaking LLMs using RL fine-tuned LLMs

# 摘要

> 我们引入 LLMStinger，这是一种新颖的方法，利用大型语言模型（LLMs）自动为越狱攻击生成对抗性后缀。与传统方法不同，传统方法需要复杂的提示工程或白盒访问，LLMStinger 使用强化学习（RL）循环来微调攻击者的 LLM，根据来自 HarmBench 基准的有害问题的现有攻击生成新的后缀。我们的方法显著优于现有的红队方法（我们与 15 种最新方法进行了比较），在 LLaMA2-7B-chat 上的攻击成功率（ASR）提高了 +57.2％，在 Claude 2 上的 ASR 提高了 +50.3％，这两个模型都以其广泛的安全措施而闻名。此外，我们在 GPT-3.5 上实现了 94.97％的 ASR，在 Gemma-2B-it 上实现了 99.4％的 ASR，展示了 LLMStinger 在开源和闭源模型中的稳健性和适应性。

> We introduce LLMStinger, a novel approach that leverages Large Language Models (LLMs) to automatically generate adversarial suffixes for jailbreak attacks. Unlike traditional methods, which require complex prompt engineering or white-box access, LLMStinger uses a reinforcement learning (RL) loop to fine-tune an attacker LLM, generating new suffixes based on existing attacks for harmful questions from the HarmBench benchmark. Our method significantly outperforms existing red-teaming approaches (we compared against 15 of the latest methods), achieving a +57.2% improvement in Attack Success Rate (ASR) on LLaMA2-7B-chat and a +50.3% ASR increase on Claude 2, both models known for their extensive safety measures. Additionally, we achieved a 94.97% ASR on GPT-3.5 and 99.4% on Gemma-2B-it, demonstrating the robustness and adaptability of LLMStinger across open and closed-source models.

[Arxiv](https://arxiv.org/abs/2411.08862)