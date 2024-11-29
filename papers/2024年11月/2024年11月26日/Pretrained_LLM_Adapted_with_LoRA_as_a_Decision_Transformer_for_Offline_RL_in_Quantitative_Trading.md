# 将使用 LoRA 适配的预训练 LLM 用作定量交易中离线 RL 的决策转换器

发布时间：2024年11月26日

`LLM应用` `量化交易`

> Pretrained LLM Adapted with LoRA as a Decision Transformer for Offline RL in Quantitative Trading

# 摘要

> 使用强化学习（RL）来开发有效的量化交易策略颇具挑战，这是由于与实时金融市场在线互动会带来高风险。所以，借助历史市场数据且无需额外探索的离线 RL 就显得极为关键。但现有的离线 RL 方法常常难以捕捉金融时间序列里固有的复杂时间依赖关系，还可能过度拟合历史模式。为应对这些难题，我们引入了一个用预训练的 GPT-2 权重初始化并用低秩自适应（LoRA）微调的决策转换器（DT）。此架构借助预训练语言模型的泛化能力和 LoRA 的高效性，仅从历史数据中的专家轨迹就能学习有效的交易策略。我们的模型与已有的离线 RL 算法（如保守 Q 学习（CQL）、隐式 Q 学习（IQL）和行为克隆（BC））以及具有随机初始化的 GPT-2 权重和 LoRA 的基线决策转换器相比，表现出色。实证结果显示，我们的方法能有效地从专家轨迹中学习，并在某些交易场景中获取优越的回报，凸显了在离线 RL 中整合预训练语言模型和进行参数高效微调在量化交易中的有效性。我们实验的复制代码在 https://github.com/syyunn/finrl-dt 可公开获取。

> Developing effective quantitative trading strategies using reinforcement learning (RL) is challenging due to the high risks associated with online interaction with live financial markets. Consequently, offline RL, which leverages historical market data without additional exploration, becomes essential. However, existing offline RL methods often struggle to capture the complex temporal dependencies inherent in financial time series and may overfit to historical patterns. To address these challenges, we introduce a Decision Transformer (DT) initialized with pre-trained GPT-2 weights and fine-tuned using Low-Rank Adaptation (LoRA). This architecture leverages the generalization capabilities of pre-trained language models and the efficiency of LoRA to learn effective trading policies from expert trajectories solely from historical data. Our model performs competitively with established offline RL algorithms, including Conservative Q-Learning (CQL), Implicit Q-Learning (IQL), and Behavior Cloning (BC), as well as a baseline Decision Transformer with randomly initialized GPT-2 weights and LoRA. Empirical results demonstrate that our approach effectively learns from expert trajectories and secures superior rewards in certain trading scenarios, highlighting the effectiveness of integrating pre-trained language models and parameter-efficient fine-tuning in offline RL for quantitative trading. Replication code for our experiments is publicly available at https://github.com/syyunn/finrl-dt

[Arxiv](https://arxiv.org/abs/2411.17900)