# 提升基于 LLM 的自动驾驶系统，以抵御感知攻击

发布时间：2024年09月22日

`Agent` `自动驾驶` `汽车安全`

> Enhancing LLM-based Autonomous Driving Agents to Mitigate Perception Attacks

# 摘要

> 随着自动驾驶系统与大型语言模型 (LLM) 的结合越来越受到关注，我们发现这些系统在面对对象检测和跟踪 (ODT) 攻击时显得尤为脆弱。我们的测试显示，四款最新 LLM 代理在 ODT 攻击下，有 63.26% 的概率会崩溃或违反交通规则，主要原因包括误导性记忆模块、提示识别不一致性的局限性以及对地面真实感知数据的依赖。为此，我们推出了 Hudson，一个专为提升驾驶安全而设计的推理代理。Hudson 通过实时收集驾驶场景的感知数据和上下文信息，并将其转化为特定领域的语言 (DSL)，从而在感知攻击期间做出更安全的决策。同时，Hudson 还能将 DSL 转换为自然语言，并附带自定义攻击检测指令，以指导 LLM 在攻击期间做出安全控制决策。在实际测试中，Hudson 与 GPT-4、Llama 和 Gemma 等 LLM 结合，分别在 83.3%、63.6% 和 73.6% 的攻击中成功检测到威胁，并在 86.4%、73.9% 和 80% 的攻击中做出了安全控制决策。这些结果不仅展示了 LLM 在自动驾驶系统中的潜力，也证明了它们在检测和缓解 ODT 攻击方面的强大能力。

> There is a growing interest in integrating Large Language Models (LLMs) with autonomous driving (AD) systems. However, AD systems are vulnerable to attacks against their object detection and tracking (ODT) functions. Unfortunately, our evaluation of four recent LLM agents against ODT attacks shows that the attacks are 63.26% successful in causing them to crash or violate traffic rules due to (1) misleading memory modules that provide past experiences for decision making, (2) limitations of prompts in identifying inconsistencies, and (3) reliance on ground truth perception data.
  In this paper, we introduce Hudson, a driving reasoning agent that extends prior LLM-based driving systems to enable safer decision making during perception attacks while maintaining effectiveness under benign conditions. Hudson achieves this by first instrumenting the AD software to collect real-time perception results and contextual information from the driving scene. This data is then formalized into a domain-specific language (DSL). To guide the LLM in detecting and making safe control decisions during ODT attacks, Hudson translates the DSL into natural language, along with a list of custom attack detection instructions. Following query execution, Hudson analyzes the LLM's control decision to understand its causal reasoning process.
  We evaluate the effectiveness of Hudson using a proprietary LLM (GPT-4) and two open-source LLMs (Llama and Gemma) in various adversarial driving scenarios. GPT-4, Llama, and Gemma achieve, on average, an attack detection accuracy of 83. 3%, 63. 6%, and 73. 6%. Consequently, they make safe control decisions in 86.4%, 73.9%, and 80% of the attacks. Our results, following the growing interest in integrating LLMs into AD systems, highlight the strengths of LLMs and their potential to detect and mitigate ODT attacks.

[Arxiv](https://arxiv.org/abs/2409.14488)