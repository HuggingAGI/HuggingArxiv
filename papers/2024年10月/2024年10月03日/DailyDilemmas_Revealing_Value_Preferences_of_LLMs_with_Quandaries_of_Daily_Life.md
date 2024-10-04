# DailyDilemmas：通过日常生活中的困境，揭示 LLM 的价值偏好

发布时间：2024年10月03日

`LLM应用` `伦理学` `人工智能`

> DailyDilemmas: Revealing Value Preferences of LLMs with Quandaries of Daily Life

# 摘要

> 随着我们越来越多地依赖大型语言模型（LLM）来指导日常决策，这些决策往往复杂且深受个人价值观和伦理标准的影响。为此，我们创建了DailyDilemmas数据集，包含1,360个日常道德困境，每个困境提供两种行动选项及涉及的各方和价值观。基于此，我们总结了一系列涵盖人际关系、职场和环境等日常话题的人类价值观。通过评估LLM在这些困境中的选择，我们发现LLM在自我表达与生存价值观上更倾向于前者，在关怀与忠诚之间更倾向于关怀。有趣的是，模型在真实性等核心价值观上存在显著差异，如Mixtral-8x7B模型倾向于忽略真实性，而GPT-4-turbo模型则更倾向于选择真实性。此外，我们还研究了OpenAI和Anthropic的最新指导原则，发现终端用户难以通过系统提示有效影响这些原则在复杂道德推理中的实际应用。

> As we increasingly seek guidance from LLMs for decision-making in daily life, many of these decisions are not clear-cut and depend significantly on the personal values and ethical standards of the users. We present DailyDilemmas, a dataset of 1,360 moral dilemmas encountered in everyday life. Each dilemma includes two possible actions and with each action, the affected parties and human values invoked. Based on these dilemmas, we consolidated a set of human values across everyday topics e.g., interpersonal relationships, workplace, and environmental issues. We evaluated LLMs on these dilemmas to determine what action they will take and the values represented by these actions. Then, we analyzed these values through the lens of five popular theories inspired by sociology, psychology and philosophy. These theories are: World Value Survey, Moral Foundation Theory, Maslow's Hierarchy of Needs, Aristotle's Virtues, and Plutchik Wheel of Emotion. We find that LLMs are most aligned with the self-expression over survival values in terms of World Value Survey, care over loyalty in Moral Foundation Theory. Interestingly, we find large preferences differences in models for some core values such as truthfulness e.g., Mixtral-8x7B model tends to neglect it by 9.7% while GPT-4-turbo model tends to select it by 9.4%. We also study the recent guidance released by OpenAI (ModelSpec), and Anthropic (Constitutional AI) to understand how their released principles reflect their actual value prioritization when facing nuanced moral reasoning in daily-life settings. We find that end users cannot effectively steer such prioritization using system prompts.

[Arxiv](https://arxiv.org/abs/2410.02683)