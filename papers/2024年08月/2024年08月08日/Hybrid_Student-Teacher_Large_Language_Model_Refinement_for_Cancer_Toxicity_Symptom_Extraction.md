# 癌症毒性症状提取：混合学生-教师大型语言模型的精炼方法

发布时间：2024年08月08日

`RAG` `人工智能`

> Hybrid Student-Teacher Large Language Model Refinement for Cancer Toxicity Symptom Extraction

# 摘要

> 大型语言模型（LLM）在临床症状提取领域展现出显著潜力，但其应用在医疗场景中受到隐私顾虑、计算资源限制及运营成本的制约。本研究探索了一种创新的迭代优化方法，专注于癌症毒性症状提取任务中的紧凑型LLM。我们构建了一个学生-教师模型体系，其中Zephyr-7b-beta和Phi3-mini-128扮演学生角色，而GPT-4o则担任教师，通过动态调整提示优化、检索增强生成（RAG）及微调策略来提升性能。实验针对包含12种放疗后毒性症状的294份临床记录进行，结果显示该方法成效显著。特别是RAG策略，大幅提升了Zephyr-7b-beta和Phi3-mini-128的平均准确率，分别从0.32跃升至0.73，以及从0.40增至0.87。在测试阶段，两模型在各症状识别准确率上均实现了约0.20的提升，且成本远低于GPT-4o，分别为其45分之一和79分之一。这些发现强调了迭代优化技术在增强紧凑型LLM临床应用能力方面的重要性，为医疗领域在性能、成本与隐私保护之间寻求平衡提供了新思路。

> Large Language Models (LLMs) offer significant potential for clinical symptom extraction, but their deployment in healthcare settings is constrained by privacy concerns, computational limitations, and operational costs. This study investigates the optimization of compact LLMs for cancer toxicity symptom extraction using a novel iterative refinement approach. We employ a student-teacher architecture, utilizing Zephyr-7b-beta and Phi3-mini-128 as student models and GPT-4o as the teacher, to dynamically select between prompt refinement, Retrieval-Augmented Generation (RAG), and fine-tuning strategies. Our experiments on 294 clinical notes covering 12 post-radiotherapy toxicity symptoms demonstrate the effectiveness of this approach. The RAG method proved most efficient, improving average accuracy scores from 0.32 to 0.73 for Zephyr-7b-beta and from 0.40 to 0.87 for Phi3-mini-128 during refinement. In the test set, both models showed an approximate 0.20 increase in accuracy across symptoms. Notably, this improvement was achieved at a cost 45 times lower than GPT-4o for Zephyr and 79 times lower for Phi-3. These results highlight the potential of iterative refinement techniques in enhancing the capabilities of compact LLMs for clinical applications, offering a balance between performance, cost-effectiveness, and privacy preservation in healthcare settings.

[Arxiv](https://arxiv.org/abs/2408.04775)