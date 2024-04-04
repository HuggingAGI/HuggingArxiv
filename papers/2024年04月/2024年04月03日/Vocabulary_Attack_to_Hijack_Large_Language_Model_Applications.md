# 通过词汇攻击，大型语言模型的应用可能被劫持。

发布时间：2024年04月03日

`LLM应用` `信息安全` `对抗攻击
</example>`

> Vocabulary Attack to Hijack Large Language Model Applications

# 摘要

> 随着大型语言模型（LLMs）技术的飞速进步，它们的应用场景也在不断扩展。用户群体壮大的同时，也涌现出更多试图挑战这些系统的攻击者。他们试图让模型泄露敏感信息、散布虚假消息或展现不当行为。为此，攻击者通过插入分隔符或不断调整语句，直到达到他们的目的。我们采取了一种不同的策略，即从模型的词汇库中插入单词。通过另一个LLM的优化算法和嵌入技术，我们找到了合适的词汇。我们分别对Llama2和Flan-T5两大家族的热门开源LLM实施了目标劫持，以此验证我们的方法。我们得出两个重要发现：首先，我们的方法生成的指令隐蔽性强，难以被察觉。在许多攻击案例中，仅通过插入一个单词就能达到目的。其次，我们展示了即使使用与目标模型不同的模型，也能成功发起攻击。

> The fast advancements in Large Language Models (LLMs) are driving an increasing number of applications. Together with the growing number of users, we also see an increasing number of attackers who try to outsmart these systems. They want the model to reveal confidential information, specific false information, or offensive behavior. To this end, they manipulate their instructions for the LLM by inserting separators or rephrasing them systematically until they reach their goal. Our approach is different. It inserts words from the model vocabulary. We find these words using an optimization procedure and embeddings from another LLM (attacker LLM). We prove our approach by goal hijacking two popular open-source LLMs from the Llama2 and the Flan-T5 families, respectively. We present two main findings. First, our approach creates inconspicuous instructions and therefore it is hard to detect. For many attack cases, we find that even a single word insertion is sufficient. Second, we demonstrate that we can conduct our attack using a different model than the target model to conduct our attack with.

[Arxiv](https://arxiv.org/abs/2404.02637)