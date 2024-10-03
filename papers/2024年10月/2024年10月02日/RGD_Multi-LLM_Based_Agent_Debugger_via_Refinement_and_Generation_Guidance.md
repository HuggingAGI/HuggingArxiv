# RGD：基于多 LLM 的代理调试器，通过精炼与生成指导实现优化

发布时间：2024年10月02日

`LLM应用` `软件开发` `人工智能`

> RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance

# 摘要

> 大型语言模型 (LLM) 在代码生成方面潜力巨大，但确保代码准确性仍需大量测试和验证。尽管 LLM 能根据描述生成代码，但其准确性在复杂任务中仍有限。为解决这一问题，我们提出了优化与引导调试 (RGD) 框架，通过多 LLM 代理协作，将代码生成分解为多个步骤，实现迭代优化。实验显示，RGD 在 HumanEval 和 MBPP 数据集上分别提升了 9.8% 和 16.2%，显著提升了 LLM 的代码生成能力。

> Large Language Models (LLMs) have shown incredible potential in code generation tasks, and recent research in prompt engineering have enhanced LLMs' understanding of textual information. However, ensuring the accuracy of generated code often requires extensive testing and validation by programmers. While LLMs can typically generate code based on task descriptions, their accuracy remains limited, especially for complex tasks that require a deeper understanding of both the problem statement and the code generation process. This limitation is primarily due to the LLMs' need to simultaneously comprehend text and generate syntactically and semantically correct code, without having the capability to automatically refine the code. In real-world software development, programmers rarely produce flawless code in a single attempt based on the task description alone, they rely on iterative feedback and debugging to refine their programs. Inspired by this process, we introduce a novel architecture of LLM-based agents for code generation and automatic debugging: Refinement and Guidance Debugging (RGD). The RGD framework is a multi-LLM-based agent debugger that leverages three distinct LLM agents-Guide Agent, Debug Agent, and Feedback Agent. RGD decomposes the code generation task into multiple steps, ensuring a clearer workflow and enabling iterative code refinement based on self-reflection and feedback. Experimental results demonstrate that RGD exhibits remarkable code generation capabilities, achieving state-of-the-art performance with a 9.8% improvement on the HumanEval dataset and a 16.2% improvement on the MBPP dataset compared to the state-of-the-art approaches and traditional direct prompting approaches. We highlight the effectiveness of the RGD framework in enhancing LLMs' ability to generate and refine code autonomously.

[Arxiv](https://arxiv.org/abs/2410.01242)