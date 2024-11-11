# 通过弹出窗口攻击视觉语言计算机代理

发布时间：2024年11月04日

`Agent` `计算机` `网络安全`

> Attacking Vision-Language Computer Agents via Pop-ups

# 摘要

> 由大型视觉和语言模型（VLM）驱动的自主代理在完成日常计算机任务方面已显示出巨大潜力，例如浏览网页预订旅行和操作桌面软件，这需要代理理解这些界面。尽管此类视觉输入在代理应用中变得更加集成，但围绕它们存在哪些类型的风险和攻击仍不清楚。在这项工作中，我们证明 VLM 代理很容易受到一组精心设计的对抗性弹出窗口的攻击，人类用户通常会识别并忽略这些弹出窗口。这种干扰导致代理点击这些弹出窗口，而不是像往常一样执行任务。将这些弹出窗口集成到现有的代理测试环境（如 OSWorld 和 VisualWebArena）中，平均攻击成功率（代理点击弹出窗口的频率）为 86％，任务成功率降低 47％。诸如要求代理忽略弹出窗口或包含广告通知等基本防御技术对攻击无效。

> Autonomous agents powered by large vision and language models (VLM) have demonstrated significant potential in completing daily computer tasks, such as browsing the web to book travel and operating desktop software, which requires agents to understand these interfaces. Despite such visual inputs becoming more integrated into agentic applications, what types of risks and attacks exist around them still remain unclear. In this work, we demonstrate that VLM agents can be easily attacked by a set of carefully designed adversarial pop-ups, which human users would typically recognize and ignore. This distraction leads agents to click these pop-ups instead of performing the tasks as usual. Integrating these pop-ups into existing agent testing environments like OSWorld and VisualWebArena leads to an attack success rate (the frequency of the agent clicking the pop-ups) of 86% on average and decreases the task success rate by 47%. Basic defense techniques such as asking the agent to ignore pop-ups or including an advertisement notice, are ineffective against the attack.

[Arxiv](https://arxiv.org/abs/2411.02391)