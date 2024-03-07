# [一句老话“口风不紧，沉船千里”，巧妙地借用到战舰游戏中。通过运用语言信息指导的程序采样技术，我们在战舰游戏中提出了创新的提问策略。](https://arxiv.org/abs/2402.19471)

> Loose LIPS Sink Ships: Asking Questions in Battleship with Language-Informed Program Sampling

发布时间：2024年02月29日

> 面对有限的认知资源，人们如何巧妙地在浩瀚的假设空间中寻找到具有启发性的问题呢？我们在经典游戏《战舰》为背景的任务中探讨了这一挑战。通过引入“语言引导程序采样”（LIPS）模型，我们借助大型语言模型（LLMs）的力量，生成自然语言问题，将其转译成符号程序，并衡量其预期的信息获取效益。令人惊讶的是，即使在相当有限的资源预算内，这种简洁的蒙特卡洛优化策略也能模拟人类行为，在多种《战舰》棋局中提出富有洞察力的问题。与此相反，那些单纯依赖LLMs的基础方法在关联问题与棋盘状态时显得力不从心，其中甚至包括最新的GPT-4V，它在视觉相关性上并未比非视觉基准有所突破。这项研究生动展示了贝叶斯问题提问模型如何借力于语言的统计特性来捕获人类内在的思维模式，同时也揭示了纯粹依赖LLMs进行实际推理时存在的不足之处。

> Questions combine our mastery of language with our remarkable facility for reasoning about uncertainty. How do people navigate vast hypothesis spaces to pose informative questions given limited cognitive resources? We study these tradeoffs in a classic grounded question-asking task based on the board game Battleship. Our language-informed program sampling (LIPS) model uses large language models (LLMs) to generate natural language questions, translate them into symbolic programs, and evaluate their expected information gain. We find that with a surprisingly modest resource budget, this simple Monte Carlo optimization strategy yields informative questions that mirror human performance across varied Battleship board scenarios. In contrast, LLM-only baselines struggle to ground questions in the board state; notably, GPT-4V provides no improvement over non-visual baselines. Our results illustrate how Bayesian models of question-asking can leverage the statistics of language to capture human priors, while highlighting some shortcomings of pure LLMs as grounded reasoners.

`LLM应用`