# SwiftSage：一款结合快思与慢想的生成智能体，专为复杂交互任务设计。

发布时间：2023年05月27日

`Agent` `人工智能` `软件开发`

> SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks

# 摘要

> 摘要：我们推出 SwiftSage，这一创新代理框架灵感源自人类认知的双过程理论，专为复杂交互推理任务的动作规划而设计。SwiftSage 融合了行为克隆与大型语言模型 (LLM) 提示的优势，旨在提升任务执行效率。框架核心包含两个模块：代表直觉快速思维的 Swift 模块和模拟深思熟虑过程的 Sage 模块。Swift 模块通过微调小型编码器-解码器 LM 来模仿专家代理的动作轨迹，而 Sage 模块则利用 GPT-4 等 LLM 进行细致的子目标规划与实现。我们设计了一种启发式整合策略，使两模块协同工作，大幅提升问题解决的效率与稳定性。在 ScienceWorld 基准测试的 30 项任务中，SwiftSage 的表现远超 SayCan、ReAct 及 Reflexion 等方法，充分证明了其在处理复杂交互任务中的卓越能力。

> 
Abstract:We introduce SwiftSage, a novel agent framework inspired by the dual-process theory of human cognition, designed to excel in action planning for complex interactive reasoning tasks. SwiftSage integrates the strengths of behavior cloning and prompting large language models (LLMs) to enhance task completion performance. The framework comprises two primary modules: the Swift module, representing fast and intuitive thinking, and the Sage module, emulating deliberate thought processes. The Swift module is a small encoder-decoder LM fine-tuned on the oracle agent's action trajectories, while the Sage module employs LLMs such as GPT-4 for subgoal planning and grounding. We develop a heuristic method to harmoniously integrate the two modules, resulting in a more efficient and robust problem-solving process. In 30 tasks from the ScienceWorld benchmark, SwiftSage significantly outperforms other methods such as SayCan, ReAct, and Reflexion, demonstrating its effectiveness in solving complex interactive tasks.
    

[Arxiv](https://arxiv.org//pdf/2305.17390)