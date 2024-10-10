# 通过情景谜题，我们不仅能评估，还能激发 LLMs 的横向思维，实现“弱评估，强激发”的效果。

发布时间：2024年10月09日

`LLM应用` `人工智能`

> Weak-eval-Strong: Evaluating and Eliciting Lateral Thinking of LLMs with Situation Puzzles

# 摘要

> 尽管 NLP 的进步显著提升了 LLM 在垂直思考任务中的表现，但其横向思维能力仍未被充分探索且难以衡量。为此，我们推出了 SPLAT，一个利用情景谜题评估和激发 LLM 横向思维的基准。SPLAT 包含 975 个分级谜题，采用多轮玩家-裁判框架，模拟互动游戏，减少对强大评估模型的依赖。实验显示，WizardLM-2 等模型在问答和情景准确性上与人类判断高度一致，超过 80% 的一致性。此外，将 SPLAT 的数据和推理过程应用于其他横向思维基准，如 RiddleSense 和 BrainTeaser，性能显著提升。这表明 SPLAT 有效评估和激发了 LLM 的横向思维能力。代码链接：https://github.com/chenqi008/LateralThinking。

> While advancements in NLP have significantly improved the performance of Large Language Models (LLMs) on tasks requiring vertical thinking, their lateral thinking capabilities remain under-explored and challenging to measure due to the complexity of assessing creative thought processes and the scarcity of relevant data. To address these challenges, we introduce SPLAT, a benchmark leveraging Situation Puzzles to evaluate and elicit LAteral Thinking of LLMs. This benchmark, containing 975 graded situation puzzles across three difficulty levels, employs a new multi-turn player-judge framework instead of the traditional model-based evaluation, which often necessitates a stronger evaluation model. This framework simulates an interactive game where the model (player) asks the evaluation model (judge) questions about an incomplete story to infer the full scenario. The judge answers based on a detailed reference scenario or evaluates if the player's predictions align with the reference one. This approach lessens dependence on more robust evaluation models, enabling the assessment of state-of-the-art LLMs. The experiments demonstrate that a robust evaluation model, such as WizardLM-2, closely matches human judgements in both intermediate question-answering and final scenario accuracy, achieving over 80% agreement-similar to the agreement levels among humans. Furthermore, applying data and reasoning processes from our benchmark to other lateral thinking-related benchmarks, e.g., RiddleSense and BrainTeaser, leads to performance enhancements. This suggests that our benchmark effectively evaluates and elicits the lateral thinking abilities of LLMs. Code is available at: https://github.com/chenqi008/LateralThinking.

[Arxiv](https://arxiv.org/abs/2410.06733)