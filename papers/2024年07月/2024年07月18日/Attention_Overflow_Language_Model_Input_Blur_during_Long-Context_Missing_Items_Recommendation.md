# 长上下文推荐中，语言模型面临“注意力溢出”问题，导致输入信息模糊，影响缺失项的准确推荐。

发布时间：2024年07月18日

`LLM应用` `电影推荐` `人工智能`

> Attention Overflow: Language Model Input Blur during Long-Context Missing Items Recommendation

# 摘要

> LLM 能从提示列表中推荐缺失项，适用于列表补全或基于用户历史的推荐。但当列表过长（约 100 项）时，模型会重复推荐已有的项目，这种现象我们称之为“注意力溢出”。我们在合成问题和真实电影推荐场景中测试了这一现象。虽然迭代方法能减轻问题，但其成本随重复率上升，影响模型从长输入中创新的能力。

> Large language models (LLMs) can suggest missing elements from items listed in a prompt, which can be used for list completion or recommendations based on users' history. However, their performance degrades when presented with too many items, as they start to suggest items already included in the input list. This occurs at around 100 items for mid-2024 flagship LLMs. We evaluate this phenomenon on both synthetic problems (e.g., finding missing numbers in a given range of shuffled integers) and realistic movie recommendation scenarios. We refer to this issue as \textit{attention overflow}, as preventing repetition requires attending to all items simultaneously. Although iterative loops can mitigate this problem, their costs increase with the repetition rate, affecting the language models' ability to derive novelty from lengthy inputs.

[Arxiv](https://arxiv.org/abs/2407.13481)