# JailbreakLens：从表示与电路的视角阐释越狱机制

发布时间：2024年11月17日

`LLM应用` `语言模型` `安全机制`

> JailbreakLens: Interpreting Jailbreak Mechanism in the Lens of Representation and Circuit

# 摘要

> 尽管大型语言模型（LLMs）在各类任务中表现卓越，但它们易受越狱攻击，即精心设计对抗性提示来绕过安全机制并引发异常响应。虽说越狱攻击常见，可对其内在机制的理解仍有限。近期研究通过分析越狱提示在其潜在空间引发的表征变化，或识别促成攻击成功的关键神经元，解释了LLMs的典型越狱行为（如模型拒绝响应的程度）。然而，这些研究既未探索多样的越狱模式，也未从电路故障到表征变化给出精细解释，在揭示越狱机制上存在很大空缺。本文中，我们提出JailbreakLens这一解释框架，从表征（揭示越狱如何改变模型的危害感知）和电路（通过识别导致漏洞的关键电路来揭示欺骗成因）视角剖析越狱机制，追踪其在整个响应生成过程中的演变。接着，我们在七种越狱策略下对四个主流LLMs的越狱行为展开深入评估。评估发现，越狱提示放大了强化肯定响应的组件，同时抑制产生拒绝的组件。尽管此操作将模型表征转向安全集群以欺骗LLM，致使其提供详细响应而非拒绝，但仍会产生异常激活，这在电路分析中能被察觉。

> Despite the outstanding performance of Large language models (LLMs) in diverse tasks, they are vulnerable to jailbreak attacks, wherein adversarial prompts are crafted to bypass their security mechanisms and elicit unexpected responses.Although jailbreak attacks are prevalent, the understanding of their underlying mechanisms remains limited. Recent studies have explain typical jailbreaking behavior (e.g., the degree to which the model refuses to respond) of LLMs by analyzing the representation shifts in their latent space caused by jailbreak prompts or identifying key neurons that contribute to the success of these attacks. However, these studies neither explore diverse jailbreak patterns nor provide a fine-grained explanation from the failure of circuit to the changes of representational, leaving significant gaps in uncovering the jailbreak mechanism. In this paper, we propose JailbreakLens, an interpretation framework that analyzes jailbreak mechanisms from both representation (which reveals how jailbreaks alter the model's harmfulness perception) and circuit perspectives (which uncovers the causes of these deceptions by identifying key circuits contributing to the vulnerability), tracking their evolution throughout the entire response generation process. We then conduct an in-depth evaluation of jailbreak behavior on four mainstream LLMs under seven jailbreak strategies. Our evaluation finds that jailbreak prompts amplify components that reinforce affirmative responses while suppressing those that produce refusal. Although this manipulation shifts model representations toward safe clusters to deceive the LLM, leading it to provide detailed responses instead of refusals, it still produce abnormal activation which can be caught in the circuit analysis.

[Arxiv](https://arxiv.org/abs/2411.11114)