# TeachTune：通过模拟学生，评估教学代理在多样化学生档案中的表现

发布时间：2024年10月05日

`Agent` `人工智能`

> TeachTune: Reviewing Pedagogical Agents Against Diverse Student Profiles with Simulated Students

# 摘要

> 大型语言模型 (LLM) 助力教育者打造个性化的教学对话代理 (PCA)。考虑到学生知识背景和动机各异，教育者需评估 PCA 的适应性。现有评估方法（如直接对话和基准测试）要么耗时费力，要么仅限于单轮互动。我们推出 TeachTune，教育者可创建模拟学生，通过观察 PCA 与模拟学生间的自动化对话来评估 PCA。我们的技术流程利用 LLM 模拟学生，展现不同知识水平和特征，助力教育者探索多样对话模式。该流程能在 5% 和 10% 的误差范围内，生成与输入知识和动机高度匹配的模拟学生。三十位科学教师参与跨学科研究，使用 TeachTune 后，任务负担减轻，学生档案覆盖率显著提升。

> Large language models (LLMs) can empower educators to build pedagogical conversational agents (PCAs) customized for their students. As students have different prior knowledge and motivation levels, educators must evaluate the adaptivity of their PCAs to diverse students. Existing chatbot evaluation methods (e.g., direct chat and benchmarks) are either manually intensive for multiple iterations or limited to testing only single-turn interactions. We present TeachTune, where educators can create simulated students and review PCAs by observing automated chats between PCAs and simulated students. Our technical pipeline instructs an LLM-based student to simulate prescribed knowledge levels and characteristics, helping educators explore diverse conversation patterns. Our pipeline could produce simulated students whose behaviors correlate highly to their input knowledge and motivation levels within 5% and 10% accuracy gaps. Thirty science teachers designed PCAs in a between-subjects study, and using TeachTune resulted in a lower task load and higher student profile coverage over a baseline.

[Arxiv](https://arxiv.org/abs/2410.04078)