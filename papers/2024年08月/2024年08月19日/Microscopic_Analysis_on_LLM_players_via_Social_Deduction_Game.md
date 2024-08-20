# 借助社交推理游戏，深入剖析 LLM 玩家的微观行为

发布时间：2024年08月19日

`LLM应用` `人工智能`

> Microscopic Analysis on LLM players via Social Deduction Game

# 摘要

> 近期研究利用大型语言模型（LLM）开发了社交推理游戏的自主玩家。在构建这些玩家时，细致的评估至关重要，但现有研究常忽略这一点。我们指出评估方法存在两个问题：一是游戏能力评估过于宏观，忽视了具体技能；二是错误分析缺乏系统性。为此，我们设计了SpyGame游戏，通过四个LLM的实验，从定量和定性角度深入分析其游戏行为。定量分析中，我们引入的八项指标有效提升了关键技能（如意图识别和伪装）的评估效果。定性分析则通过主题分析，揭示了影响游戏表现的四大类别，这些发现与定量分析相辅相成，共同提升了我们对LLM游戏能力的理解。

> Recent studies have begun developing autonomous game players for social deduction games using large language models (LLMs). When building LLM players, fine-grained evaluations are crucial for addressing weaknesses in game-playing abilities. However, existing studies have often overlooked such assessments. Specifically, we point out two issues with the evaluation methods employed. First, game-playing abilities have typically been assessed through game-level outcomes rather than specific event-level skills; Second, error analyses have lacked structured methodologies. To address these issues, we propose an approach utilizing a variant of the SpyFall game, named SpyGame. We conducted an experiment with four LLMs, analyzing their gameplay behavior in SpyGame both quantitatively and qualitatively. For the quantitative analysis, we introduced eight metrics to resolve the first issue, revealing that these metrics are more effective than existing ones for evaluating the two critical skills: intent identification and camouflage. In the qualitative analysis, we performed thematic analysis to resolve the second issue. This analysis identifies four major categories that affect gameplay of LLMs. Additionally, we demonstrate how these categories complement and support the findings from the quantitative analysis.

[Arxiv](https://arxiv.org/abs/2408.09946)