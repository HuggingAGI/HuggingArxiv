# EduAgent：在学习过程中应用的创造性学生代理

发布时间：2024年03月23日

`Agent` `网络教育` `人工智能`

> EduAgent: Generative Student Agents in Learning

# 摘要

> 在网络教育领域，模拟学生行为对于理解和应对来自不同背景学生的多样化学习动态至关重要。尽管基于深度学习的模拟模型需依赖大量训练数据，它们在教育领域的先验知识方面往往不足。大型语言模型（LLMs）由于其庞大的预训练语料库，可能蕴含了丰富的教育相关先验知识。但是，学生行为的多样性和动态性要求我们不能简单地直接利用LLMs来进行模拟，因为这在捕捉学生个体差异、学习行为和成果之间的细微联系方面既不稳定也不够精确。本研究通过引入一个细粒度的大规模数据集，并设计了EduAgent——一个创新的生成代理框架，它融合了认知科学的理论发现作为认知先验知识，引导LLMs首先分析不同学习行为之间的关联，然后进行模拟。我们的两项实验证明，EduAgent不仅能够模拟和预测真实学生的行为模式，还能在没有实际数据的情况下生成虚拟学生的现实学习行为。

> Student simulation in online education is important to address dynamic learning behaviors of students with diverse backgrounds. Existing simulation models based on deep learning usually need massive training data, lacking prior knowledge in educational contexts. Large language models (LLMs) may contain such prior knowledge since they are pre-trained from a large corpus. However, because student behaviors are dynamic and multifaceted with individual differences, directly prompting LLMs is not robust nor accurate enough to capture fine-grained interactions among diverse student personas, learning behaviors, and learning outcomes. This work tackles this problem by presenting a newly annotated fine-grained large-scale dataset and proposing EduAgent, a novel generative agent framework incorporating cognitive prior knowledge (i.e., theoretical findings revealed in cognitive science) to guide LLMs to first reason correlations among various behaviors and then make simulations. Our two experiments show that EduAgent could not only mimic and predict learning behaviors of real students but also generate realistic learning behaviors of virtual students without real data.

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x1.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x2.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x3.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x4.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/appendix_dataset2_distribution.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x5.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/appendix_gaze_simulation.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x6.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x7.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x8.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x9.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x10.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x11.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x12.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x13.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x14.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x15.png)

![EduAgent：在学习过程中应用的创造性学生代理](../../../paper_images/2404.07963/x16.png)

[Arxiv](https://arxiv.org/abs/2404.07963)