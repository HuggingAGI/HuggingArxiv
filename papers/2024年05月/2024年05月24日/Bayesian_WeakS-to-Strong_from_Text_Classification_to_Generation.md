# 从文本分类到生成：贝叶斯弱至强策略

发布时间：2024年05月24日

`Agent

理由：这篇论文主要探讨了如何通过集成多个弱模型来模拟人类意见的多样性，并采用贝叶斯方法评估置信度，以指导从弱到强的泛化过程。这种方法涉及到构建和调整模型以更好地适应和模拟人类监督，这属于Agent领域的研究，即如何设计和优化智能体（Agent）以更好地理解和执行任务。此外，论文中提到的“学生模型”和“教师强制框架”等概念，也是Agent研究中常见的术语，用于描述模型之间的学习和指导关系。因此，这篇论文更适合归类于Agent。` `人工智能` `机器学习`

> Bayesian WeakS-to-Strong from Text Classification to Generation

# 摘要

> 随着大型语言模型日益复杂，人类监督变得薄弱，我们面临一个挑战：如何调整对齐技术以适应这一变化。本研究提出了WeakS-to-Strong方法，通过集成多个弱模型来模拟人类意见的多样性，并采用贝叶斯方法评估置信度，以指导从弱到强的泛化过程。此外，我们将这一方法从文本分类扩展到文本生成领域，探索了更高级的监督策略。通过直接偏好优化，我们进一步提升了学生模型在偏好学习上的表现，超越了传统的教师强制框架。实验结果证实了该方法在提升强大学生模型可靠性方面的有效性，预示着超对齐的可能性。

> Advances in large language models raise the question of how alignment techniques will adapt as models become increasingly complex and humans will only be able to supervise them weakly. Weak-to-Strong mimics such a scenario where weak model supervision attempts to harness the full capabilities of a much stronger model. This work extends Weak-to-Strong to WeakS-to-Strong by exploring an ensemble of weak models which simulate the variability in human opinions. Confidence scores are estimated using a Bayesian approach to guide the WeakS-to-Strong generalization. Furthermore, we extend the application of WeakS-to-Strong from text classification tasks to text generation tasks where more advanced strategies are investigated for supervision. Moreover, direct preference optimization is applied to advance the student model's preference learning, beyond the basic learning framework of teacher forcing. Results demonstrate the effectiveness of the proposed approach for the reliability of a strong student model, showing potential for superalignment.

![从文本分类到生成：贝叶斯弱至强策略](../../../paper_images/2406.03199/x1.png)

![从文本分类到生成：贝叶斯弱至强策略](../../../paper_images/2406.03199/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03199)