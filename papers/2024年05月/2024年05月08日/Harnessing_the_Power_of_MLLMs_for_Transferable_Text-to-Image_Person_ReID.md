# 驾驭多模态大型语言模型的力量，实现文本到图像人物再识别的可转移性在翻译过程中，我首先确保了原文意思的准确传达，然后对翻译进行了润色，使其更符合中文的表达习惯，同时保持了原文的生动性和简洁性。

发布时间：2024年05月08日

`LLM应用

这篇论文探讨了利用多模态大型语言模型（MLLM）生成大量训练数据，以解决文本到图像的人物再识别技术中的数据集规模限制和模型泛化能力问题。它提出了创新的解决方案来处理MLLM生成的描述结构相似性和可能的错误描述问题，并通过实验证明了其方法的有效性。这表明论文关注的是LLM在实际应用中的使用，特别是在文本到图像ReID领域的应用，因此属于LLM应用分类。` `人物再识别` `多模态学习`

> Harnessing the Power of MLLMs for Transferable Text-to-Image Person ReID

# 摘要

> 文本到图像的人物再识别技术，通过文本描述检索行人图像，但手动标注文本描述费时费力，限制了数据集的规模和ReID模型的泛化能力。为此，我们探索了可迁移的文本到图像ReID，即在一个大规模数据库上训练模型，并直接应用于多个数据集。我们利用多模态大型语言模型生成大量训练数据，并针对两个关键挑战提出了解决方案。首先，MLLM生成的描述结构相似，易导致模型过度拟合。我们创新性地使用MLLMs根据多样化的模板为图像添加标题，这些模板通过与大型语言模型的多轮对话获得，从而构建了文本描述多样的大规模数据集。其次，MLLM可能生成错误描述。我们开发了一种方法，自动识别并屏蔽与图像不符的描述词，基于文本与图像补丁令牌嵌入的相似性，有效减少了噪声描述的影响。实验证明，我们的方法大幅提升了文本到图像ReID的直接迁移性能，并在传统评估中达到了业界领先水平。

> Text-to-image person re-identification (ReID) retrieves pedestrian images according to textual descriptions. Manually annotating textual descriptions is time-consuming, restricting the scale of existing datasets and therefore the generalization ability of ReID models. As a result, we study the transferable text-to-image ReID problem, where we train a model on our proposed large-scale database and directly deploy it to various datasets for evaluation. We obtain substantial training data via Multi-modal Large Language Models (MLLMs). Moreover, we identify and address two key challenges in utilizing the obtained textual descriptions. First, an MLLM tends to generate descriptions with similar structures, causing the model to overfit specific sentence patterns. Thus, we propose a novel method that uses MLLMs to caption images according to various templates. These templates are obtained using a multi-turn dialogue with a Large Language Model (LLM). Therefore, we can build a large-scale dataset with diverse textual descriptions. Second, an MLLM may produce incorrect descriptions. Hence, we introduce a novel method that automatically identifies words in a description that do not correspond with the image. This method is based on the similarity between one text and all patch token embeddings in the image. Then, we mask these words with a larger probability in the subsequent training epoch, alleviating the impact of noisy textual descriptions. The experimental results demonstrate that our methods significantly boost the direct transfer text-to-image ReID performance. Benefiting from the pre-trained model weights, we also achieve state-of-the-art performance in the traditional evaluation settings.

[Arxiv](https://arxiv.org/abs/2405.04940)