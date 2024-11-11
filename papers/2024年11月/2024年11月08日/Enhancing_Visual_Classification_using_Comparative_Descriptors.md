# 使用比较描述符增强视觉分类

发布时间：2024年11月08日

`LLM应用`

> Enhancing Visual Classification using Comparative Descriptors

# 摘要

> 视觉语言模型（VLMs），如 CLIP，在视觉分类任务中的性能通过利用来自大型语言模型（LLMs）（包括 GPT）的语义知识得到了增强。最近的研究表明，在零样本分类任务中，结合了额外线索、高级概念甚至随机字符的描述符通常比仅使用类别名称的描述符表现更好。在许多分类任务中，虽然 top-1 准确率可能相对较低，但 top-5 准确率往往显著更高。这种差距意味着大多数错误分类发生在少数几个相似的类别之间，突出了模型在区分细微差异的类别方面的困难。为了应对这一挑战，我们引入了比较描述符的新概念。这些描述符强调目标类别与其最相似类别相比的独特特征，增强了区分度。通过生成并将这些比较描述符集成到分类框架中，我们细化了语义焦点并提高了分类准确率。一个额外的过滤过程确保这些描述符在 CLIP 空间中更接近图像嵌入，进一步提高了性能。我们的方法通过解决类别间细微差异的特定挑战，在视觉分类任务中展示了更高的准确率和鲁棒性。

> The performance of vision-language models (VLMs), such as CLIP, in visual classification tasks, has been enhanced by leveraging semantic knowledge from large language models (LLMs), including GPT. Recent studies have shown that in zero-shot classification tasks, descriptors incorporating additional cues, high-level concepts, or even random characters often outperform those using only the category name. In many classification tasks, while the top-1 accuracy may be relatively low, the top-5 accuracy is often significantly higher. This gap implies that most misclassifications occur among a few similar classes, highlighting the model's difficulty in distinguishing between classes with subtle differences. To address this challenge, we introduce a novel concept of comparative descriptors. These descriptors emphasize the unique features of a target class against its most similar classes, enhancing differentiation. By generating and integrating these comparative descriptors into the classification framework, we refine the semantic focus and improve classification accuracy. An additional filtering process ensures that these descriptors are closer to the image embeddings in the CLIP space, further enhancing performance. Our approach demonstrates improved accuracy and robustness in visual classification tasks by addressing the specific challenge of subtle inter-class differences.

[Arxiv](https://arxiv.org/abs/2411.05357)