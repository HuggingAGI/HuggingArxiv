# 我们能否在 LLM 中进一步激发推理能力？通过批评者引导的规划与检索增强，解决复杂任务。

发布时间：2024年10月02日

`LLM应用` `人工智能`

> Can We Further Elicit Reasoning in LLMs? Critic-Guided Planning with Retrieval-Augmentation for Solving Challenging Tasks

# 摘要

> 最先进的 LLM 虽然问题解决能力出色，但在复杂推理和事实准确性上仍有不足。现有方法通过思维链和 RAG 将复杂问题简化，并通过检索提升事实准确性，但在竞争性编程和数学等高难度任务中常因推理错误和无关知识检索而失效。为此，我们提出了 CR-Planner，一个利用微调批评模型通过规划指导推理和检索的新框架。CR-Planner 通过迭代选择和执行子目标解决问题，首先由子目标批评模型指导识别最有希望的子目标，然后由执行批评模型评估选择最佳输出。这一过程结合检索信息和批评模型，使 CR-Planner 能有效导航至最终答案。我们采用蒙特卡洛树搜索系统探索动作序列及其长期影响，并在竞争性编程、定理驱动数学推理等高难度任务中验证了 CR-Planner，实验结果显示其显著优于基线，证明了其在解决复杂问题上的有效性。

> State-of-the-art large language models (LLMs) exhibit impressive problem-solving capabilities but may struggle with complex reasoning and factual correctness. Existing methods harness the strengths of chain-of-thought and retrieval-augmented generation (RAG) to decompose a complex problem into simpler steps and apply retrieval to improve factual correctness. These methods work well on straightforward reasoning tasks but often falter on challenging tasks such as competitive programming and mathematics, due to frequent reasoning errors and irrelevant knowledge retrieval. To address this, we introduce Critic-guided planning with Retrieval-augmentation, CR-Planner, a novel framework that leverages fine-tuned critic models to guide both reasoning and retrieval processes through planning. CR-Planner solves a problem by iteratively selecting and executing sub-goals. Initially, it identifies the most promising sub-goal from reasoning, query generation, and retrieval, guided by rewards given by a critic model named sub-goal critic. It then executes this sub-goal through sampling and selecting the optimal output based on evaluations from another critic model named execution critic. This iterative process, informed by retrieved information and critic models, enables CR-Planner to effectively navigate the solution space towards the final answer. We employ Monte Carlo Tree Search to collect the data for training the critic models, allowing for a systematic exploration of action sequences and their long-term impacts. We validate CR-Planner on challenging domain-knowledge-intensive and reasoning-heavy tasks, including competitive programming, theorem-driven math reasoning, and complex domain retrieval problems. Our experiments demonstrate that CR-Planner significantly outperforms baselines, highlighting its effectiveness in addressing challenging problems by improving both reasoning and retrieval.

[Arxiv](https://arxiv.org/abs/2410.01428)