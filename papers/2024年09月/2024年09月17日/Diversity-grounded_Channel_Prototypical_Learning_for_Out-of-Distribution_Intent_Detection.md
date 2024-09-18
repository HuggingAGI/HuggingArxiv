# 基于多样性的通道原型学习，助力分布外意图检测

发布时间：2024年09月17日

`LLM应用` `人工智能` `对话系统`

> Diversity-grounded Channel Prototypical Learning for Out-of-Distribution Intent Detection

# 摘要

> 在任务导向的对话系统中，意图检测机制需应对现实场景中的格式错误语句。本研究提出了一种新的LLM微调框架，通过语义匹配原型，提升ID意图分类和OOD意图检测。我们利用LLM的独特表示，采用多样性提示微调构建ID类语义原型。在ID与OOD类语义相近的挑战性环境中，我们的框架表现优异，尤其在少样本ID分类和近OOD检测任务中。实验结果显示，我们的方法超越了现有微调技术。

> In the realm of task-oriented dialogue systems, a robust intent detection mechanism must effectively handle malformed utterances encountered in real-world scenarios. This study presents a novel fine-tuning framework for large language models (LLMs) aimed at enhancing in-distribution (ID) intent classification and out-of-distribution (OOD) intent detection, which utilizes semantic matching with prototypes derived from ID class names. By harnessing the highly distinguishable representations of LLMs, we construct semantic prototypes for each ID class using a diversity-grounded prompt tuning approach. We rigorously test our framework in a challenging OOD context, where ID and OOD classes are semantically close yet distinct, referred to as \emph{near} OOD detection. For a thorough assessment, we benchmark our method against the prevalent fine-tuning approaches. The experimental findings reveal that our method demonstrates superior performance in both few-shot ID intent classification and near-OOD intent detection tasks.

[Arxiv](https://arxiv.org/abs/2409.11114)