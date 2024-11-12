# 在文本到图像合成中用于无训练语义绑定的令牌合并

发布时间：2024年11月11日

`LLM应用` `图像生成` `语义绑定`

> Token Merging for Training-Free Semantic Binding in Text-to-Image Synthesis

# 摘要

> 尽管文本到图像（T2I）模型展现出了显著的生成能力，但它们经常无法在输入提示中准确地绑定语义相关的对象或属性；这一挑战被称为语义绑定。之前的方法要么涉及对整个 T2I 模型进行密集的微调，要么要求用户或大型语言模型指定生成布局，增加了复杂性。在本文中，我们将语义绑定定义为将给定对象与其属性相关联的任务，称为属性绑定，或将其与其他相关子对象链接，称为对象绑定。我们引入了一种名为令牌合并（ToMe）的新方法，通过将相关令牌聚合为单个复合令牌来增强语义绑定。这确保了对象、其属性和子对象都共享相同的交叉注意力图。此外，为了解决具有复杂文本提示的主要对象之间的潜在混淆，我们提出了结束令牌替换作为补充策略。为了在确定布局的 T2I 生成的初始阶段进一步完善我们的方法，我们引入了两个辅助损失，即熵损失和语义绑定损失，以迭代更新复合令牌以提高生成的完整性。我们进行了广泛的实验来验证 ToMe 的有效性，并将其与 T2I-CompBench 上的各种现有方法以及我们提出的 GPT-4o 对象绑定基准进行了比较。我们的方法在涉及多个对象和属性的复杂场景中特别有效，而之前的方法往往无法解决。代码将在 url{https://github.com/hutaihang/ToMe} 上公开可用。

> Although text-to-image (T2I) models exhibit remarkable generation capabilities, they frequently fail to accurately bind semantically related objects or attributes in the input prompts; a challenge termed semantic binding. Previous approaches either involve intensive fine-tuning of the entire T2I model or require users or large language models to specify generation layouts, adding complexity. In this paper, we define semantic binding as the task of associating a given object with its attribute, termed attribute binding, or linking it to other related sub-objects, referred to as object binding. We introduce a novel method called Token Merging (ToMe), which enhances semantic binding by aggregating relevant tokens into a single composite token. This ensures that the object, its attributes and sub-objects all share the same cross-attention map. Additionally, to address potential confusion among main objects with complex textual prompts, we propose end token substitution as a complementary strategy. To further refine our approach in the initial stages of T2I generation, where layouts are determined, we incorporate two auxiliary losses, an entropy loss and a semantic binding loss, to iteratively update the composite token to improve the generation integrity. We conducted extensive experiments to validate the effectiveness of ToMe, comparing it against various existing methods on the T2I-CompBench and our proposed GPT-4o object binding benchmark. Our method is particularly effective in complex scenarios that involve multiple objects and attributes, which previous methods often fail to address. The code will be publicly available at \url{https://github.com/hutaihang/ToMe}.

[Arxiv](https://arxiv.org/abs/2411.07132)