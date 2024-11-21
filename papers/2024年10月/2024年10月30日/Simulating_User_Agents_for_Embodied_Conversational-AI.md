# 对具身会话式 AI 的用户代理进行模拟

发布时间：2024年10月30日

`Agent` `机器人` `人工智能`

> Simulating User Agents for Embodied Conversational-AI

# 摘要

> 设计用于协助用户完成任务的具身智能体，得参与自然语言交互、解读指令、执行动作并有效交流以解决问题。然而，收集大规模、多样化的情境化人机对话数据集来训练和评估这类智能体，既费钱又费力还耗时。为应对此挑战，我们提议构建基于大型语言模型（LLM）的用户智能体，它能在虚拟环境中与具身智能体交互时模拟用户行为。给定一个用户目标（比如做早餐），在每个时间步，用户智能体可能会观察“机器人动作或说话”，从而干预机器人或回答问题。这样的用户智能体有助于提升具身对话数据集生成的扩展性和效率，对增强和评估机器人的交互及任务完成能力，以及利用人工智能反馈的强化学习研究至关重要。我们通过将其模拟的对话与 TEACh 数据集作对比，来评估用户智能体生成类人行为的能力。我们开展了三个实验：零样本提示来预测对话行为、少样本提示以及在 TEACh 训练子集上进行微调。结果显示，基于 LLM 的用户智能体在模仿人类说话行为方面，零样本提示的 F 测度达 42%，少样本提示达 43.4%。通过微调，决定何时说话的性能保持稳定，而决定说什么的性能从 51.1%提升至 62.5%。这些发现表明了所提方法在通过自然语言交流评估和提高机器人任务完成效果方面的可行性。

> Embodied agents designed to assist users with tasks must engage in natural language interactions, interpret instructions, execute actions, and communicate effectively to resolve issues. However, collecting large-scale, diverse datasets of situated human-robot dialogues to train and evaluate such agents is expensive, labor-intensive, and time-consuming. To address this challenge, we propose building a large language model (LLM)-based user agent that can simulate user behavior during interactions with an embodied agent in a virtual environment. Given a user goal (e.g., make breakfast), at each time step, the user agent may observe" the robot actions or speak" to either intervene with the robot or answer questions. Such a user agent assists in improving the scalability and efficiency of embodied dialogues dataset generation and is critical for enhancing and evaluating the robot's interaction and task completion ability, as well as for research in reinforcement learning using AI feedback. We evaluate our user agent's ability to generate human-like behaviors by comparing its simulated dialogues with the TEACh dataset. We perform three experiments: zero-shot prompting to predict dialogue acts, few-shot prompting, and fine-tuning on the TEACh training subset. Results show the LLM-based user agent achieves an F-measure of 42% with zero-shot prompting and 43.4% with few-shot prompting in mimicking human speaking behavior. Through fine-tuning, performance in deciding when to speak remained stable, while deciding what to say improved from 51.1% to 62.5%. These findings showcase the feasibility of the proposed approach for assessing and enhancing the effectiveness of robot task completion through natural language communication.

[Arxiv](https://arxiv.org/abs/2410.23535)