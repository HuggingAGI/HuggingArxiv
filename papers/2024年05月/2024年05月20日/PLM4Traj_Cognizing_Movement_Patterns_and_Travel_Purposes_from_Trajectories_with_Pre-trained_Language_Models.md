# PLM4Traj：借助预训练语言模型，从轨迹数据中洞察移动模式与旅行目的

发布时间：2024年05月20日

`LLM应用

理由：这篇论文主要探讨了如何利用预训练语言模型（PLMs）来优化时空轨迹的学习方法，提出了PLM4Traj模型，这是一种专门针对轨迹数据进行优化的应用。论文的核心在于应用PLMs于特定的轨迹学习任务，而不是探讨LLM的理论基础或Agent的行为，也不是关于检索增强生成（RAG）的研究。因此，它最适合归类为“LLM应用”。` `时空数据挖掘`

> PLM4Traj: Cognizing Movement Patterns and Travel Purposes from Trajectories with Pre-trained Language Models

# 摘要

> 时空轨迹在时空数据挖掘中至关重要，但开发一种既能适应多任务又保持高精度的轨迹学习方法颇具挑战。这要求我们精准提取轨迹中的运动模式和旅行目的，但现有数据集的规模和质量限制了这一进程。幸运的是，预训练语言模型（PLMs）在处理大规模高质量数据集时表现出色，为轨迹学习提供了新思路。考虑到轨迹与句子的相似性，PLMs可能成为开发高效轨迹学习方法的关键。尽管如此，标准的PLMs并不擅长处理轨迹特有的时空特征，也无法有效提取运动模式和旅行目的。为此，我们提出了PLM4Traj模型，它巧妙地利用PLMs来优化轨迹建模。PLM4Traj不仅继承了PLMs的灵活性，还通过引入创新的轨迹语义嵌入器和轨迹提示，克服了原始PLMs的局限。前者使PLMs能处理并提取轨迹中的时空特征，后者则将这些特征融入模型，使其能灵活应对各种任务。实验结果证实，PLM4Traj在两个真实数据集和两个关键任务上均达到了预期效果。相关代码已公开在https://github.com/Zeru19/PLM4Traj。

> Spatio-temporal trajectories play a vital role in various spatio-temporal data mining tasks. Developing a versatile trajectory learning approach that can adapt to different tasks while ensuring high accuracy is crucial. This requires effectively extracting movement patterns and travel purposes embedded in trajectories. However, this task is challenging due to limitations in the size and quality of available trajectory datasets. On the other hand, pre-trained language models (PLMs) have shown great success in adapting to different tasks by training on large-scale, high-quality corpus datasets. Given the similarities between trajectories and sentences, there is potential in leveraging PLMs to enhance the development of a versatile and effective trajectory learning method. Nevertheless, vanilla PLMs are not tailored to handle the unique spatio-temporal features present in trajectories and lack the capability to extract movement patterns and travel purposes from them.
  To overcome these obstacles, we propose a model called PLM4Traj that effectively utilizes PLMs to model trajectories. PLM4Traj leverages the strengths of PLMs to create a versatile trajectory learning approach while addressing the limitations of vanilla PLMs in modeling trajectories. Firstly, PLM4Traj incorporates a novel trajectory semantic embedder that enables PLMs to process spatio-temporal features in trajectories and extract movement patterns and travel purposes from them. Secondly, PLM4Traj introduces a novel trajectory prompt that integrates movement patterns and travel purposes into PLMs, while also allowing the model to adapt to various tasks. Extensive experiments conducted on two real-world datasets and two representative tasks demonstrate that PLM4Traj successfully achieves its design goals. Codes are available at https://github.com/Zeru19/PLM4Traj.

[Arxiv](https://arxiv.org/abs/2405.12459)