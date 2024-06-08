# QROA：针对LLMs的黑盒查询-响应优化攻击

发布时间：2024年06月04日

`Agent

理由：这篇论文主要探讨了一种针对大型语言模型（LLMs）的新型攻击策略——查询-响应优化攻击（QROA）。这种攻击通过黑盒查询交互方式，利用恶意指令中的优化触发器来操纵LLMs生成有害内容。研究的重点在于如何通过外部交互（即Agent的行为）来影响LLMs的行为，而不是深入探讨LLMs的理论或内部机制。因此，这种研究更符合Agent的分类，因为它关注的是外部实体如何影响和操纵LLMs的行为。` `人工智能`

> QROA: A Black-Box Query-Response Optimization Attack on LLMs

# 摘要

> 近期，大型语言模型（LLMs）备受瞩目，但其被操纵后可能生成有害内容的能力令人担忧。本研究提出了一种名为查询-响应优化攻击（QROA）的新策略，通过黑盒查询交互方式巧妙利用LLMs。QROA在恶意指令中嵌入优化触发器，诱导LLM产生有害内容，无需触及模型内部信息，仅依赖标准查询-响应接口。借鉴深度Q学习和贪婪坐标下降算法，该方法迭代优化令牌，以最大化特定奖励函数。我们在Vicuna、Falcon及Mistral等LLMs上验证了QROA的有效性，攻击成功率高达80%以上。此外，面对专为抵御越狱攻击而微调的Llama2-chat，即使使用次优初始触发种子，QROA也展现了良好的攻击效果。此研究揭示了利用黑盒优化技术对公共领域LLMs实施越狱攻击的可行性，为LLMs的安全性评估提供了更全面的视角。

> Large Language Models (LLMs) have surged in popularity in recent months, yet they possess concerning capabilities for generating harmful content when manipulated. This study introduces the Query-Response Optimization Attack (QROA), an optimization-based strategy designed to exploit LLMs through a black-box, query-only interaction. QROA adds an optimized trigger to a malicious instruction to compel the LLM to generate harmful content. Unlike previous approaches, QROA does not require access to the model's logit information or any other internal data and operates solely through the standard query-response interface of LLMs. Inspired by deep Q-learning and Greedy coordinate descent, the method iteratively updates tokens to maximize a designed reward function. We tested our method on various LLMs such as Vicuna, Falcon, and Mistral, achieving an Attack Success Rate (ASR) over 80\%. We also tested the model against Llama2-chat, the fine-tuned version of Llama2 designed to resist Jailbreak attacks, achieving good ASR with a suboptimal initial trigger seed. This study demonstrates the feasibility of generating jailbreak attacks against deployed LLMs in the public domain using black-box optimization methods, enabling more comprehensive safety testing of LLMs.

[Arxiv](https://arxiv.org/abs/2406.02044)