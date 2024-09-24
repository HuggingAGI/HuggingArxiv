# 提升基于 LLM 的自动驾驶系统，以抵御感知攻击

发布时间：2024年09月22日

`Agent` `自动驾驶` `网络安全`

> Enhancing LLM-based Autonomous Driving Agents to Mitigate Perception Attacks

# 摘要

> 随着大型语言模型 (LLM) 与自动驾驶 (AD) 系统的结合越来越受到关注，AD 系统对对象检测和跟踪 (ODT) 功能的攻击也变得脆弱。不幸的是，我们的评估显示，四种最新的 LLM 代理在 ODT 攻击下，由于误导性记忆模块、提示识别不一致性的局限性以及依赖地面真实感知数据，导致崩溃或违反交通规则的成功率高达 63.26%。为此，我们推出了 Hudson，一个驾驶推理代理，它不仅扩展了基于 LLM 的驾驶系统，还在感知攻击期间实现了更安全的决策，同时在良性条件下保持高效。Hudson 通过收集实时感知结果和驾驶场景的上下文信息，将其形式化为特定领域的语言 (DSL)，并转换为自然语言，附带自定义攻击检测指令，指导 LLM 在 ODT 攻击期间做出安全决策。在对抗性驾驶场景中，我们使用 GPT-4、Llama 和 Gemma 评估了 Hudson 的有效性。结果显示，GPT-4、Llama 和 Gemma 的平均攻击检测准确率分别为 83.3%、63.6% 和 73.6%，并在 86.4%、73.9% 和 80% 的攻击中做出了安全的控制决策。这不仅突显了 LLM 的优势，也展示了其在检测和缓解 ODT 攻击方面的巨大潜力。

> There is a growing interest in integrating Large Language Models (LLMs) with autonomous driving (AD) systems. However, AD systems are vulnerable to attacks against their object detection and tracking (ODT) functions. Unfortunately, our evaluation of four recent LLM agents against ODT attacks shows that the attacks are 63.26% successful in causing them to crash or violate traffic rules due to (1) misleading memory modules that provide past experiences for decision making, (2) limitations of prompts in identifying inconsistencies, and (3) reliance on ground truth perception data.
  In this paper, we introduce Hudson, a driving reasoning agent that extends prior LLM-based driving systems to enable safer decision making during perception attacks while maintaining effectiveness under benign conditions. Hudson achieves this by first instrumenting the AD software to collect real-time perception results and contextual information from the driving scene. This data is then formalized into a domain-specific language (DSL). To guide the LLM in detecting and making safe control decisions during ODT attacks, Hudson translates the DSL into natural language, along with a list of custom attack detection instructions. Following query execution, Hudson analyzes the LLM's control decision to understand its causal reasoning process.
  We evaluate the effectiveness of Hudson using a proprietary LLM (GPT-4) and two open-source LLMs (Llama and Gemma) in various adversarial driving scenarios. GPT-4, Llama, and Gemma achieve, on average, an attack detection accuracy of 83. 3%, 63. 6%, and 73. 6%. Consequently, they make safe control decisions in 86.4%, 73.9%, and 80% of the attacks. Our results, following the growing interest in integrating LLMs into AD systems, highlight the strengths of LLMs and their potential to detect and mitigate ODT attacks.

[Arxiv](https://arxiv.org/abs/2409.14488)