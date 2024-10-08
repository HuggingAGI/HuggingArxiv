# 借助任务过载，实现对大型语言模型的可扩展越狱攻击

发布时间：2024年10月05日

`LLM应用` `网络安全` `人工智能`

> Harnessing Task Overload for Scalable Jailbreak Attacks on Large Language Models

# 摘要

> 大型语言模型 (LLM) 仍易受 jailbreak 攻击，这些攻击能绕过其安全机制。现有攻击方法固定或专为特定模型设计，无法灵活调整攻击强度，这在攻击不同大小的模型时至关重要。我们提出了一种新颖的可扩展 jailbreak 攻击，通过占用 LLM 的计算资源来预先阻止其安全策略的激活。我们的方法涉及在呈现目标指令前，让 LLM 参与资源密集型的初步任务——字符映射查找和解码过程。通过饱和模型的处理能力，我们在处理后续指令时阻止了安全协议的激活。对最先进的 LLM 进行的广泛实验表明，我们的方法在不需梯度访问、手动提示工程的情况下，成功绕过安全措施的成功率很高。我们验证了我们的方法提供了一种可扩展的攻击，量化了攻击强度并适应不同模型规模的最佳强度。我们表明，LLM 的安全策略可能更容易受到资源限制的影响。我们的发现揭示了当前 LLM 安全设计中的一个关键漏洞，强调了需要更强大的防御策略来应对资源密集型条件。

> Large Language Models (LLMs) remain vulnerable to jailbreak attacks that bypass their safety mechanisms. Existing attack methods are fixed or specifically tailored for certain models and cannot flexibly adjust attack strength, which is critical for generalization when attacking models of various sizes. We introduce a novel scalable jailbreak attack that preempts the activation of an LLM's safety policies by occupying its computational resources. Our method involves engaging the LLM in a resource-intensive preliminary task - a Character Map lookup and decoding process - before presenting the target instruction. By saturating the model's processing capacity, we prevent the activation of safety protocols when processing the subsequent instruction. Extensive experiments on state-of-the-art LLMs demonstrate that our method achieves a high success rate in bypassing safety measures without requiring gradient access, manual prompt engineering. We verified our approach offers a scalable attack that quantifies attack strength and adapts to different model scales at the optimal strength. We shows safety policies of LLMs might be more susceptible to resource constraints. Our findings reveal a critical vulnerability in current LLM safety designs, highlighting the need for more robust defense strategies that account for resource-intense condition.

[Arxiv](https://arxiv.org/abs/2410.04190)