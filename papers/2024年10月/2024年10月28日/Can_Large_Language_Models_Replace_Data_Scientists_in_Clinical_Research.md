# 大型语言模型能在临床研究领域替代数据科学家吗？

发布时间：2024年10月28日

`LLM应用` `数据科学`

> Can Large Language Models Replace Data Scientists in Clinical Research?

# 摘要

> 数据科学在临床研究中至关重要，不过这需要具备编码和医学数据分析专长的专业人士。大型语言模型（LLMs）在助力医疗任务以及一般编码测试中表现抢眼，潜力巨大。然而，这些测试既未评估LLMs处理医学数据科学任务的能力，也未探究其在临床研究中的实际用途。为应对此状况，我们基于39项已发表的临床研究，开发了一个包含293项真实世界数据科学编码任务的数据集，涵盖128项Python任务和165项R任务。该数据集借助患者数据模拟了真实的临床研究场景。我们的发现显示，前沿的LLMs难以给出完美方案，常常不能遵循输入指令、理解目标数据以及遵循标准分析流程。所以，LLMs尚未做好完全自动化数据科学任务的准备。我们对先进的适配方法进行了基准测试，发现有两种特别有效：思维链提示，为数据分析提供了分步计划，使代码准确率提升60%；自我反思，让LLMs能够迭代优化代码，使准确率提高38%。基于这些发现，我们为医学专业人员打造了一个将LLMs融入数据科学工作流程的平台。在针对五位医生的用户研究中，我们发现尽管LLMs无法完全自动化编码任务，但显著简化了编程流程。我们发现他们提交的代码解决方案中80%源自LLM生成的代码，某些情况下重复使用率高达96%。我们的分析凸显了LLMs融入专家工作流程后提升临床研究中数据科学效率的潜力。

> Data science plays a critical role in clinical research, but it requires professionals with expertise in coding and medical data analysis. Large language models (LLMs) have shown great potential in supporting medical tasks and performing well in general coding tests. However, these tests do not assess LLMs' ability to handle data science tasks in medicine, nor do they explore their practical utility in clinical research. To address this, we developed a dataset consisting of 293 real-world data science coding tasks, based on 39 published clinical studies, covering 128 tasks in Python and 165 tasks in R. This dataset simulates realistic clinical research scenarios using patient data. Our findings reveal that cutting-edge LLMs struggle to generate perfect solutions, frequently failing to follow input instructions, understand target data, and adhere to standard analysis practices. Consequently, LLMs are not yet ready to fully automate data science tasks. We benchmarked advanced adaptation methods and found two to be particularly effective: chain-of-thought prompting, which provides a step-by-step plan for data analysis, which led to a 60% improvement in code accuracy; and self-reflection, enabling LLMs to iteratively refine their code, yielding a 38% accuracy improvement. Building on these insights, we developed a platform that integrates LLMs into the data science workflow for medical professionals. In a user study with five medical doctors, we found that while LLMs cannot fully automate coding tasks, they significantly streamline the programming process. We found that 80% of their submitted code solutions were incorporated from LLM-generated code, with up to 96% reuse in some cases. Our analysis highlights the potential of LLMs, when integrated into expert workflows, to enhance data science efficiency in clinical research.

[Arxiv](https://arxiv.org/abs/2410.21591)