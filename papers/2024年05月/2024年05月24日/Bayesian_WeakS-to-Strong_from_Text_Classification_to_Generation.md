# 从文本分类到生成：贝叶斯弱至强之路

发布时间：2024年05月24日

`Agent

理由：这篇论文探讨了如何利用弱模型监督来激发更强大模型的潜能，并引入了模拟人类意见多样性的弱模型。这种方法涉及到模型的自我改进和对齐技术，这些都是Agent研究领域的关键概念。论文中提到的从弱到强的泛化过程、贝叶斯方法评估置信度、直接偏好优化等，都是为了增强模型的自主性和适应性，这与Agent的研究方向相符。此外，论文中提到的监督方法的扩展和学生模型的进步，也体现了Agent在自我学习和适应环境方面的能力。因此，这篇论文更适合归类于Agent。` `人工智能` `模型训练`

> Bayesian WeakS-to-Strong from Text Classification to Generation

# 摘要

> 随着大型语言模型的复杂性增加，人类监督变得愈发薄弱，我们不禁思考：对齐技术将如何适应这一变化？本研究通过模拟“弱至强”监督场景，探索了如何利用弱模型监督来激发更强大模型的潜能。我们引入了一组弱模型，模拟人类意见的多样性，并采用贝叶斯方法评估置信度，以指导从弱到强的泛化过程。此外，我们将这一策略从文本分类扩展至文本生成领域，并探索了更为先进的监督方法。通过直接偏好优化，我们进一步推动了学生模型在偏好学习上的进步。实验结果证实，这一方法有效提升了强学生模型的可靠性，预示着超对齐技术的广阔前景。

> Advances in large language models raise the question of how alignment techniques will adapt as models become increasingly complex and humans will only be able to supervise them weakly. Weak-to-Strong mimics such a scenario where weak model supervision attempts to harness the full capabilities of a much stronger model. This work extends Weak-to-Strong to WeakS-to-Strong by exploring an ensemble of weak models which simulate the variability in human opinions. Confidence scores are estimated using a Bayesian approach to guide the WeakS-to-Strong generalization. Furthermore, we extend the application of WeakS-to-Strong from text classification tasks to text generation tasks where more advanced strategies are investigated for supervision. Moreover, direct preference optimization is applied to advance the student model's preference learning, beyond the basic learning framework of teacher forcing. Results demonstrate the effectiveness of the proposed approach for the reliability of a strong student model, showing potential for superalignment.

![从文本分类到生成：贝叶斯弱至强之路](../../../paper_images/2406.03199/x1.png)

![从文本分类到生成：贝叶斯弱至强之路](../../../paper_images/2406.03199/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03199)