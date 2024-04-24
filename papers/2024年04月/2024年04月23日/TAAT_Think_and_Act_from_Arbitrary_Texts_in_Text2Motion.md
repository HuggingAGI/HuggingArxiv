# TAAT：在 Text2Motion 技术中，任意文本触发思考与行动

发布时间：2024年04月23日

`分类：LLM应用` `计算机视觉`

> TAAT: Think and Act from Arbitrary Texts in Text2Motion

# 摘要

> Text2Motion 致力于根据文本描述生成人体动作。目前的数据集通常假设文本中包含动作标签，如“行走”、“弯腰”和“拾起”，但这种设定在现实应用中并不实用。本研究以更符合实际的假设为基础，即文本内容不受限制。具体而言，这些任意文本既包括由动作标签构成的动作描述（如“一个人行走并弯腰拾物”），也包括没有明确动作标签的场景描述（如“一个人发现前方地上有他的钱包”）。为解决现实场景与现有数据集之间的差异，我们对 HumanML3D 数据集中的动作文本进行了扩展，增加了更多场景文本，创建了新的 HumanML3D++ 数据集，涵盖了任意文本。在这个充满挑战的新数据集上，我们不仅对现有的顶尖方法进行了评估，还提出了一个创新的两阶段框架：首先利用大型语言模型（LLM）从任意文本中提取动作标签，然后基于这些标签生成动作。我们在多种应用场景下进行了广泛的实验，以验证所提框架在现有和新数据集上的有效性。实验结果表明，在现实条件下进行 Text2Motion 任务极具挑战性，这为未来研究方向提供了新的启示。我们将公开我们的数据集和相关代码。

> Text2Motion aims to generate human motions from texts. Existing datasets rely on the assumption that texts include action labels (such as "walk, bend, and pick up"), which is not flexible for practical scenarios. This paper redefines this problem with a more realistic assumption that the texts are arbitrary. Specifically, arbitrary texts include existing action texts composed of action labels (e.g., A person walks and bends to pick up something), and introduce scene texts without explicit action labels (e.g., A person notices his wallet on the ground ahead).
  To bridge the gaps between this realistic setting and existing datasets, we expand the action texts on the HumanML3D dataset to more scene texts, thereby creating a new HumanML3D++ dataset including arbitrary texts. In this challenging dataset, we benchmark existing state-of-the-art methods and propose a novel two-stage framework to extract action labels from arbitrary texts by the Large Language Model (LLM) and then generate motions from action labels. Extensive experiments are conducted under different application scenarios to validate the effectiveness of the proposed framework on existing and proposed datasets. The results indicate that Text2Motion in this realistic setting is very challenging, fostering new research in this practical direction. Our dataset and code will be released.

[Arxiv](https://arxiv.org/abs/2404.14745)