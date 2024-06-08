# 贝叶斯进化：从文本分类到生成之旅

发布时间：2024年05月24日

`LLM理论

这篇论文探讨了大型语言模型（LLM）的对齐技术，特别是在模型复杂性增加和人类监督能力有限的情况下，如何通过弱监督模型来优化更强大模型的性能。研究提出了WeakS-to-Strong方法，并结合贝叶斯方法评估置信度，以及直接偏好优化策略，以提高模型的学习效率和可靠性。这些内容属于LLM理论范畴，因为它关注的是模型训练和优化的理论方法，而不是直接的应用或特定的Agent或RAG系统。` `人工智能` `文本生成`

> Bayesian WeakS-to-Strong from Text Classification to Generation

# 摘要

> 大型语言模型的发展引发了一个问题：随着模型日益复杂，人类的监督能力有限，对齐技术将如何进化？Weak-to-Strong 设想了一种情况，即通过弱监督模型来充分利用更强大的模型。本研究通过集成多个模拟人类意见差异的弱模型，将这一概念扩展为 WeakS-to-Strong，并采用贝叶斯方法评估置信度，以优化泛化过程。我们还探索了将 WeakS-to-Strong 应用于文本生成任务的新策略，并引入了直接偏好优化，以超越传统的教师强制框架，提升学生模型的学习效率。实验结果证实了这一方法在提升强学生模型可靠性方面的有效性，预示着超对齐技术的潜力。

> Advances in large language models raise the question of how alignment techniques will adapt as models become increasingly complex and humans will only be able to supervise them weakly. Weak-to-Strong mimics such a scenario where weak model supervision attempts to harness the full capabilities of a much stronger model. This work extends Weak-to-Strong to WeakS-to-Strong by exploring an ensemble of weak models which simulate the variability in human opinions. Confidence scores are estimated using a Bayesian approach to guide the WeakS-to-Strong generalization. Furthermore, we extend the application of WeakS-to-Strong from text classification tasks to text generation tasks where more advanced strategies are investigated for supervision. Moreover, direct preference optimization is applied to advance the student model's preference learning, beyond the basic learning framework of teacher forcing. Results demonstrate the effectiveness of the proposed approach for the reliability of a strong student model, showing potential for superalignment.

![贝叶斯进化：从文本分类到生成之旅](../../../paper_images/2406.03199/x1.png)

![贝叶斯进化：从文本分类到生成之旅](../../../paper_images/2406.03199/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03199)