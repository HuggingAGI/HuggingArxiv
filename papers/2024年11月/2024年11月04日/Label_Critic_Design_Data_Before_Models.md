# 标签评论家：在模型之前设计数据

发布时间：2024年11月04日

`LLM应用` `人工智能`

> Label Critic: Design Data Before Models

# 摘要

> 随着医疗数据集迅速扩大，对不同身体结构创建详细注释变得越来越昂贵和耗时。我们认为要求放射科医生创建详细注释是不必要的负担，并且预先存在的人工智能模型在很大程度上可以使这个过程自动化。遵循不要杀鸡用牛刀的精神，我们发现，放射科医生不必从头开始创建注释，而只需在最佳人工智能标签有错误时审查和编辑错误。为了在多个人工智能标签中获得最佳人工智能标签，我们开发了一种名为 Label Critic 的自动工具，它可以通过不懈的成对比较来评估标签质量。大量实验表明，当与我们开发的图像提示对结合使用时，在自然图像和文本上训练的预先存在的大型视觉语言模型（LVLM）在成对比较中选择最佳标签时达到 96.5％的准确率，无需额外的微调。通过将手动注释任务（每次扫描 30 - 60 分钟）转换为自动比较任务（每次扫描 15 秒），我们有效地将放射科医生所需的人工工作量减少了一个数量级。当最佳人工智能标签足够准确（取决于身体结构为 81％）时，它们将直接被用作数据集的黄金标准注释，质量较低的人工智能标签将自动被丢弃。当没有可供比较的替代方案时，Label Critic 还可以以 71.8％的准确率检查单个人工智能标签的标签质量，如果估计质量低（取决于身体结构为 19％），则提示放射科医生进行审查和编辑。

> As medical datasets rapidly expand, creating detailed annotations of different body structures becomes increasingly expensive and time-consuming. We consider that requesting radiologists to create detailed annotations is unnecessarily burdensome and that pre-existing AI models can largely automate this process. Following the spirit don't use a sledgehammer on a nut, we find that, rather than creating annotations from scratch, radiologists only have to review and edit errors if the Best-AI Labels have mistakes. To obtain the Best-AI Labels among multiple AI Labels, we developed an automatic tool, called Label Critic, that can assess label quality through tireless pairwise comparisons. Extensive experiments demonstrate that, when incorporated with our developed Image-Prompt pairs, pre-existing Large Vision-Language Models (LVLM), trained on natural images and texts, achieve 96.5% accuracy when choosing the best label in a pair-wise comparison, without extra fine-tuning. By transforming the manual annotation task (30-60 min/scan) into an automatic comparison task (15 sec/scan), we effectively reduce the manual efforts required from radiologists by an order of magnitude. When the Best-AI Labels are sufficiently accurate (81% depending on body structures), they will be directly adopted as the gold-standard annotations for the dataset, with lower-quality AI Labels automatically discarded. Label Critic can also check the label quality of a single AI Label with 71.8% accuracy when no alternatives are available for comparison, prompting radiologists to review and edit if the estimated quality is low (19% depending on body structures).

[Arxiv](https://arxiv.org/abs/2411.02753)