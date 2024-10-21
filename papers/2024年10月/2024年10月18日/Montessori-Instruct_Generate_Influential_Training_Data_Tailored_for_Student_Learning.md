# 蒙特梭利教学法：定制化生成助力学生学习的优质训练数据

发布时间：2024年10月18日

`LLM应用` `人工智能`

> Montessori-Instruct: Generate Influential Training Data Tailored for Student Learning

# 摘要

> 合成数据虽广泛用于训练大型语言模型，但其生成特性难免引入噪声和误导信息。为此，我们提出 Montessori-Instruct 框架，定制教师模型数据合成能力以适应学生模型学习过程。通过分析合成数据对学生的局部影响，我们表征其学习偏好，并利用直接偏好优化 (DPO) 训练教师模型生成符合学生偏好的数据。实验显示，Montessori-Instruct 在 Alpaca Eval 和 MT-Bench 上分别比标准方法提升 18.35% 和 46.24%，甚至超越了 GPT-4o 合成的数据。进一步分析表明，教师模型生成更具影响力的数据有助于学生学习，局部数据影响能更准确地反映学生偏好，且 Montessori-Instruct 在不同学生模型中表现稳健。相关代码和数据已开源，详见 https://github.com/cxcscmu/Montessori-Instruct。

> Synthetic data has been widely used to train large language models, but their generative nature inevitably introduces noisy, non-informative, and misleading learning signals. In this paper, we propose Montessori-Instruct, a novel data synthesis framework that tailors the data synthesis ability of the teacher language model toward the student language model's learning process. Specifically, we utilize local data influence of synthetic training data points on students to characterize students' learning preferences. Then, we train the teacher model with Direct Preference Optimization (DPO) to generate synthetic data tailored toward student learning preferences. Experiments with Llama3-8B-Instruct (teacher) and Llama3-8B (student) on Alpaca Eval and MT-Bench demonstrate that Montessori-Instruct significantly outperforms standard synthesis methods by 18.35\% and 46.24\% relatively. Our method also beats data synthesized by a stronger teacher model, GPT-4o. Further analysis confirms the benefits of teacher's learning to generate more influential training data in the student's improved learning, the advantages of local data influence in accurately measuring student preferences, and the robustness of Montessori-Instruct across different student models. Our code and data are open-sourced at https://github.com/cxcscmu/Montessori-Instruct.

[Arxiv](https://arxiv.org/abs/2410.14208)