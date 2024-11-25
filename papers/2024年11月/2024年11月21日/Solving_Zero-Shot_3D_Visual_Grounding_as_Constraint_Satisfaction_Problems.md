# 将零样本 3D 视觉基础问题当作约束满足问题来解决

发布时间：2024年11月21日

`LLM应用` `3D 视觉` `计算机视觉`

> Solving Zero-Shot 3D Visual Grounding as Constraint Satisfaction Problems

# 摘要

> 3D 视觉基础（3DVG）旨在凭借自然语言描述在 3D 场景中定位对象。有监督的方法准确性不错，可词汇封闭且语言理解能力有限。零样本方法多借助大型语言模型（LLMs）处理自然语言描述，不过推理速度慢。为解决这些问题，在本研究中，我们提出一种零样本方法，将 3DVG 任务重新定义为约束满足问题（CSP），其中变量和约束分别代表对象及其空间关系。这能对所有相关对象进行全局推理，得出目标对象和锚定对象的定位结果。此外，我们通过仅少量额外的编码工作处理基于否定和计数的查询，展现了框架的灵活性。我们的系统——约束满足视觉基础（CSVG），仅使用开源的 LLMs 在公共数据集 ScanRefer 和 Nr3D 上进行了广泛评估。结果显示 CSVG 有效，定位精度优越，在 ScanRefer 和 Nr3D 数据集上分别比当前最先进的零样本 3DVG 方法提高了 +7.0％（Acc@0.5 分数）和 +11.2％。我们系统的代码在 https://github.com/sunsleaf/CSVG 公开。

> 3D visual grounding (3DVG) aims to locate objects in a 3D scene with natural language descriptions. Supervised methods have achieved decent accuracy, but have a closed vocabulary and limited language understanding ability. Zero-shot methods mostly utilize large language models (LLMs) to handle natural language descriptions, yet suffer from slow inference speed. To address these problems, in this work, we propose a zero-shot method that reformulates the 3DVG task as a Constraint Satisfaction Problem (CSP), where the variables and constraints represent objects and their spatial relations, respectively. This allows a global reasoning of all relevant objects, producing grounding results of both the target and anchor objects. Moreover, we demonstrate the flexibility of our framework by handling negation- and counting-based queries with only minor extra coding efforts. Our system, Constraint Satisfaction Visual Grounding (CSVG), has been extensively evaluated on the public datasets ScanRefer and Nr3D datasets using only open-source LLMs. Results show the effectiveness of CSVG and superior grounding accuracy over current state-of-the-art zero-shot 3DVG methods with improvements of $+7.0\%$ (Acc@0.5 score) and $+11.2\%$ on the ScanRefer and Nr3D datasets, respectively. The code of our system is publicly available at https://github.com/sunsleaf/CSVG.

[Arxiv](https://arxiv.org/abs/2411.14594)