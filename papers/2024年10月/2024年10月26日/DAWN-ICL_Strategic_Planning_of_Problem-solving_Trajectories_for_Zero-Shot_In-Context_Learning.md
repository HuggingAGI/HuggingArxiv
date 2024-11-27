# DAWN-ICL：针对零样本上下文学习的问题解决轨迹的战略规划

发布时间：2024年10月26日

`LLM应用` `机器学习`

> DAWN-ICL: Strategic Planning of Problem-solving Trajectories for Zero-Shot In-Context Learning

# 摘要

> 零样本上下文学习（ZS-ICL）意在无需人工标注的示范就能开展上下文学习（ICL）。多数 ZS-ICL 方法借助大型语言模型（LLMs）生成（输入，标签）对作为伪示范，并凭借历史伪示范来助力解决当下问题。它们假定问题源自相同任务，且以随机次序进行遍历。但在现实场景中，问题往往来自不同任务，仅有少量属于相同任务。这种随机遍历顺序或许会产生不可靠的伪示范，进而导致错误累积。为应对此问题，我们将 ZS-ICL 重新定义为一个规划问题，并提出了一种示范感知的蒙特卡罗树搜索（MCTS）方法（DAWN-ICL），该方法利用 MCTS 为 ZS-ICL 策略性规划问题解决路径。另外，为达成有效且高效的 Q 值估计，我们提出了一种新颖的示范感知 Q 值函数，并用于强化 MCTS 中的选择阶段，加快扩展和模拟阶段。大量实验表明 DAWN-ICL 在域内和跨域场景中的有效性和高效性，它甚至比使用人工标注标签的 ICL 表现更优。代码可在 https://github.com/RUCAIBox/MCTS4ZSICL 获取。

> Zero-shot in-context learning (ZS-ICL) aims to conduct in-context learning (ICL) without using human-annotated demonstrations. Most ZS-ICL methods use large language models (LLMs) to generate (input, label) pairs as pseudo-demonstrations and leverage historical pseudo-demonstrations to help solve the current problem. They assume that problems are from the same task and traverse them in a random order. However, in real-world scenarios, problems usually come from diverse tasks, and only a few belong to the same task. The random traversing order may generate unreliable pseudo-demonstrations and lead to error accumulation. To address this problem, we reformulate ZS-ICL as a planning problem and propose a Demonstration-aware Monte Carlo Tree Search (MCTS) approach (DAWN-ICL), which leverages MCTS to strategically plan the problem-solving trajectories for ZS-ICL. In addition, to achieve effective and efficient Q value estimation, we propose a novel demonstration-aware Q-value function and use it to enhance the selection phase and accelerate the expansion and simulation phases in MCTS. Extensive experiments demonstrate the effectiveness and efficiency of DAWN-ICL on in-domain and cross-domain scenarios, and it even outperforms ICL using human-annotated labels. The code is available at https://github.com/RUCAIBox/MCTS4ZSICL.

[Arxiv](https://arxiv.org/abs/2410.20215)