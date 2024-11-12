# 大型语言模型中事实信息的持续记忆

发布时间：2024年11月11日

`LLM应用` `语言模型` `记忆研究`

> Continual Memorization of Factoids in Large Language Models

# 摘要

> 大型语言模型可以通过预训练吸收大量知识，但预训练对于获取长尾或专业事实效率低下。因此，针对反映世界变化的专业或新知识进行微调已变得流行，尽管这有破坏模型原始能力的风险。我们在持续记忆的背景下研究这种脆弱性，其中模型在一小部分长尾事实（事实关联）上进行训练，并且必须在后续在其他数据集上的多个训练阶段后保留这些事实。通过大量实验，我们表明大型语言模型在广泛的后续任务中存在遗忘，简单的重放技术不能完全防止遗忘，特别是当事实数据集在后期阶段进行训练时。我们认为有两种方法可以减轻遗忘：1）在模型学习事实时保护记忆过程，或 2）减少后期训练的干扰。基于这种见解，我们开发了一种有效的缓解策略：REMIX（随机和通用数据混合）。REMIX 通过在每个阶段混合从预训练语料库中采样的通用数据甚至随机生成的单词序列来防止遗忘，尽管与第一阶段记忆的事实无关。REMIX 可以从严重遗忘中恢复性能，通常优于能够访问第一阶段事实的基于重放的方法。然后，我们分析了 REMIX 如何改变学习过程，并发现成功防止遗忘与一种模式相关：模型比平常更早地将事实存储在层中，并使存储这些事实的层集多样化。REMIX 的有效性引发了对记忆和遗忘潜在动态的进一步研究，为未来的研究开辟了令人兴奋的可能性。

> Large language models can absorb a massive amount of knowledge through pretraining, but pretraining is inefficient for acquiring long-tailed or specialized facts. Therefore, fine-tuning on specialized or new knowledge that reflects changes in the world has become popular, though it risks disrupting the model's original capabilities. We study this fragility in the context of continual memorization, where the model is trained on a small set of long-tail factoids (factual associations) and must retain these factoids after multiple stages of subsequent training on other datasets. Through extensive experiments, we show that LLMs suffer from forgetting across a wide range of subsequent tasks, and simple replay techniques do not fully prevent forgetting, especially when the factoid datasets are trained in the later stages. We posit that there are two ways to alleviate forgetting: 1) protect the memorization process as the model learns the factoids, or 2) reduce interference from training in later stages. With this insight, we develop an effective mitigation strategy: REMIX (Random and Generic Data Mixing). REMIX prevents forgetting by mixing generic data sampled from pretraining corpora or even randomly generated word sequences during each stage, despite being unrelated to the memorized factoids in the first stage. REMIX can recover performance from severe forgetting, often outperforming replay-based methods that have access to the factoids from the first stage. We then analyze how REMIX alters the learning process and find that successful forgetting prevention is associated with a pattern: the model stores factoids in earlier layers than usual and diversifies the set of layers that store these factoids. The efficacy of REMIX invites further investigation into the underlying dynamics of memorization and forgetting, opening exciting possibilities for future research.

[Arxiv](https://arxiv.org/abs/2411.07175)