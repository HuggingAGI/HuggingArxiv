# [KIWI 数据集，专为解答研究问题而设计，提供了丰富的知识密集型写作指导。](https://arxiv.org/abs/2403.03866)

发布时间：2024年03月06日

`LLM应用`

> KIWI: A Dataset of Knowledge-Intensive Writing Instructions for Answering Research Questions

> 现今，适应用户指令的LLMs作为对话式助手广泛应用。本研究聚焦于一项愈发普遍的任务——辅助撰写长篇回答。为了检验当前LLMs对此任务的胜任程度，我们创建了一个名为KIWI的数据集，内含科学领域内的知识密集型写作指导。面对一个研究问题、初期的机器生成答案及一系列相关文献，专业标注员会逐轮给出修正和优化答案的指令。我们通过与三种尖端LLMs的234场互动交流，积累了1,260个互动回合，每回合包含了用户的指令、模型回应及其人工评估结果。深入分析这些反馈后，我们发现所有模型均在整合新信息至已有答案和精准无误地编辑上遇到挑战。另外，模型在判断自身输出是否有效遵从用户指令的能力上也显露出不足，准确率至少比人类共识低10个百分点。这些发现提示我们，KIWI数据集将是一个衡量进步和提升LLMs在处理知识密集型写作任务时的指令执行性能的重要工具。

> Large language models (LLMs) adapted to follow user instructions are now widely deployed as conversational agents. In this work, we examine one increasingly common instruction-following task: providing writing assistance to compose a long-form answer. To evaluate the capabilities of current LLMs on this task, we construct KIWI, a dataset of knowledge-intensive writing instructions in the scientific domain. Given a research question, an initial model-generated answer and a set of relevant papers, an expert annotator iteratively issues instructions for the model to revise and improve its answer. We collect 1,260 interaction turns from 234 interaction sessions with three state-of-the-art LLMs. Each turn includes a user instruction, a model response, and a human evaluation of the model response. Through a detailed analysis of the collected responses, we find that all models struggle to incorporate new information into an existing answer, and to perform precise and unambiguous edits. Further, we find that models struggle to judge whether their outputs successfully followed user instructions, with accuracy at least 10 points short of human agreement. Our findings indicate that KIWI will be a valuable resource to measure progress and improve LLMs' instruction-following capabilities for knowledge intensive writing tasks.

[Arxiv](https://arxiv.org/abs/2403.03866)