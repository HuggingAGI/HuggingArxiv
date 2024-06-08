# 贝叶斯进化：从文本分类到生成之旅

发布时间：2024年05月24日

`Agent

这篇论文探讨了大型语言模型（LLM）的监督问题，特别是在模型复杂性增加的情况下，如何通过弱模型监督来充分利用更强大模型的潜能。研究中使用了模拟人类意见多样性的弱模型集合，并采用贝叶斯方法评估置信度，以指导监督过程。此外，研究还将这一策略从文本分类扩展到文本生成任务，并研究了更高级的监督方法。这些内容涉及到模型的自主监督和决策过程，因此更适合归类为Agent。` `人工智能` `机器学习`

> Bayesian WeakS-to-Strong from Text Classification to Generation

# 摘要

> 大型语言模型的进步，引发了一个问题：随着模型日益复杂，人类的监督能力有限，对齐技术该如何适应？本研究模拟了“弱到强”的场景，即通过弱模型监督来充分利用更强大模型的潜能。我们进一步探索了“弱S到强”，通过一组模拟人类意见多样性的弱模型集合，并采用贝叶斯方法评估置信度，以指导这一过程。此外，我们将这一策略从文本分类扩展至文本生成任务，并研究了更高级的监督方法。同时，通过直接偏好优化，我们推动了学生模型在偏好学习上的进步。实验结果证实了这一方法的有效性，为实现超对齐提供了可能。

> Advances in large language models raise the question of how alignment techniques will adapt as models become increasingly complex and humans will only be able to supervise them weakly. Weak-to-Strong mimics such a scenario where weak model supervision attempts to harness the full capabilities of a much stronger model. This work extends Weak-to-Strong to WeakS-to-Strong by exploring an ensemble of weak models which simulate the variability in human opinions. Confidence scores are estimated using a Bayesian approach to guide the WeakS-to-Strong generalization. Furthermore, we extend the application of WeakS-to-Strong from text classification tasks to text generation tasks where more advanced strategies are investigated for supervision. Moreover, direct preference optimization is applied to advance the student model's preference learning, beyond the basic learning framework of teacher forcing. Results demonstrate the effectiveness of the proposed approach for the reliability of a strong student model, showing potential for superalignment.

![贝叶斯进化：从文本分类到生成之旅](../../../paper_images/2406.03199/x1.png)

![贝叶斯进化：从文本分类到生成之旅](../../../paper_images/2406.03199/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03199)