# FineCops-Ref：细粒度组合指代表达理解的新数据集与任务

发布时间：2024年09月23日

`LLM应用` `人工智能` `计算机视觉`

> FineCops-Ref: A new Dataset and Task for Fine-Grained Compositional Referring Expression Comprehension

# 摘要

> 指称表达理解 (REC) 是评估语言与图像交互能力的关键任务，因此成为多模态大型语言模型 (MLLM) 的理想测试场。为此，我们创建了一个新的 REC 数据集，具备两大特色：一是难度可控，要求在对象、属性和多跳关系间进行多层次细粒度推理；二是包含通过精细编辑和生成创建的负文本与图像，考验模型在目标对象不可见时的正确拒绝能力，这一方面常被现有数据集忽视。我们利用此数据集对顶尖专家模型和 MLLM 进行了全面评估，发现接地性能仍有显著提升空间。我们期待，该数据集能激发新的视觉推理方法和跨模态交互策略，助力 MLLM 潜能的全面释放。代码与数据集已公开，详见 https://github.com/liujunzhuo/FineCops-Ref。

> Referring Expression Comprehension (REC) is a crucial cross-modal task that objectively evaluates the capabilities of language understanding, image comprehension, and language-to-image grounding. Consequently, it serves as an ideal testing ground for Multi-modal Large Language Models (MLLMs). In pursuit of this goal, we have established a new REC dataset characterized by two key features: Firstly, it is designed with controllable varying levels of difficulty, necessitating multi-level fine-grained reasoning across object categories, attributes, and multi-hop relationships. Secondly, it includes negative text and images created through fine-grained editing and generation based on existing data, thereby testing the model's ability to correctly reject scenarios where the target object is not visible in the image--an essential aspect often overlooked in existing datasets and approaches. Utilizing this high-quality dataset, we conducted comprehensive evaluations of both state-of-the-art specialist models and MLLMs. Our findings indicate that there remains a significant gap in achieving satisfactory grounding performance. We anticipate that our dataset will inspire new approaches to enhance visual reasoning and develop more advanced cross-modal interaction strategies, ultimately unlocking the full potential of MLLMs. Our code and the datasets are available at https://github.com/liujunzhuo/FineCops-Ref.

[Arxiv](https://arxiv.org/abs/2409.14750)