# 训练语言模型以模仿学生的错误认知可能导致回归的副作用。

发布时间：2024年04月23日

`LLM应用` `个性化教育` `人工智能伦理`

> Regressive Side Effects of Training Language Models to Mimic Student Misconceptions

# 摘要

> 本研究深入探讨了在个性化教育领域，训练大型语言模型（LLMs）模拟学生错误观念可能带来的负面后果。研究发现，LLMs在更精确地模仿学生误解的同时，其事实准确性和推理能力却受到了影响。通过在学生-导师对话数据集上训练LLM预测学生回答，实验结果显示模型在多个标准数据集上的表现有所下滑，包括评估模型回答真实性的TruthfulQA和ARC推理挑战。此外，用于幻觉检测的HaluEval Dial数据集和基于记忆的任务数据集MemoTrap的准确率也有所下降。为了缓解这些问题，研究引入了“幻觉标记”方法，该方法在训练过程中添加在学生回答的开头，指导模型在模仿学生误解和提供准确事实之间进行切换。尽管这种方法在所有数据集上都取得了显著提升，但仍未能使LLMs恢复到其原始性能水平，这表明还需在这一领域进行更深入的研究。本文为LLMs在学生建模应用中的讨论增添了新视角，强调了在个性化教育与事实准确性之间寻求平衡的重要性。

> This paper presents a novel exploration into the regressive side effects of training Large Language Models (LLMs) to mimic student misconceptions for personalized education. We highlight the problem that as LLMs are trained to more accurately mimic student misconceptions, there is a compromise in the factual integrity and reasoning ability of the models. Our work involved training an LLM on a student-tutor dialogue dataset to predict student responses. The results demonstrated a decrease in the model's performance across multiple benchmark datasets, including the ARC reasoning challenge and TruthfulQA, which evaluates the truthfulness of model's generated responses. Furthermore, the HaluEval Dial dataset, used for hallucination detection, and MemoTrap, a memory-based task dataset, also reported a decline in the model accuracy. To combat these side effects, we introduced a "hallucination token" technique. This token, appended at the beginning of each student response during training, instructs the model to switch between mimicking student misconceptions and providing factually accurate responses. Despite the significant improvement across all datasets, the technique does not completely restore the LLM's baseline performance, indicating the need for further research in this area. This paper contributes to the ongoing discussion on the use of LLMs for student modeling, emphasizing the need for a balance between personalized education and factual accuracy.

[Arxiv](https://arxiv.org/abs/2404.15156)