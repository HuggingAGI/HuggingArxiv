# [在大规模视觉语言模型中探究艺术品阐释能力]

发布时间：2024年02月29日

`Agent`

> Artwork Explanation in Large-scale Vision Language Models

> 大型视觉-语言模型（LVLMs）能依据图像与指示输出文字，展现了其高超的文本生成与理解技能。但关于LVLMs如何理解并运用解释图像所必需的知识，特别是各类知识间的复杂联系，以及如何将这些认知融入解释的过程，尚未得到充分阐释。为此，我们创新性地提出了“艺术作品解释生成”任务，并配备相应的评测数据集及量化评估指标，以深入探讨LVLMs对艺术知识的理解和应用程度。该任务立足于一个假设，即LVLMs应该具备一定的艺术作品预存知识，因为艺术作品通常是公众广泛认识且具有丰富文献记载的对象。任务内容包括两大部分：从艺术作品的图像和标题出发生成解释，以及仅依靠图像生成解释，借此检验LVLMs的语言型知识和视觉型知识。此外，我们还提供了一个专门训练LVLMs学习融合艺术知识进行解释的数据集。研究揭示，LVLMs不仅在融合语言与视觉信息时面临挑战，而且在单纯依赖图像获取知识的能力上显示出更显著的局限性。此数据集（ExpArt，意为“解释艺术作品”）已在https://huggingface.co/datasets/naist-nlp/ExpArt网站开放获取。

> Large-scale vision-language models (LVLMs) output text from images and instructions, demonstrating advanced capabilities in text generation and comprehension. However, it has not been clarified to what extent LVLMs understand the knowledge necessary for explaining images, the complex relationships between various pieces of knowledge, and how they integrate these understandings into their explanations. To address this issue, we propose a new task: the artwork explanation generation task, along with its evaluation dataset and metric for quantitatively assessing the understanding and utilization of knowledge about artworks. This task is apt for image description based on the premise that LVLMs are expected to have pre-existing knowledge of artworks, which are often subjects of wide recognition and documented information. It consists of two parts: generating explanations from both images and titles of artworks, and generating explanations using only images, thus evaluating the LVLMs' language-based and vision-based knowledge. Alongside, we release a training dataset for LVLMs to learn explanations that incorporate knowledge about artworks. Our findings indicate that LVLMs not only struggle with integrating language and visual information but also exhibit a more pronounced limitation in acquiring knowledge from images alone. The datasets (ExpArt=Explain Artworks) are available at https://huggingface.co/datasets/naist-nlp/ExpArt.

[Arxiv](https://arxiv.org/abs/2403.00068)