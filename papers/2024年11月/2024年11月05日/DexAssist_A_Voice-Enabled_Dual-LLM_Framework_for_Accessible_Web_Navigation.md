# DexAssist：一个支持语音的双 LLM 框架，用于实现无障碍网页导航

发布时间：2024年11月05日

`LLM应用` `电子商务`

> DexAssist: A Voice-Enabled Dual-LLM Framework for Accessible Web Navigation

# 摘要

> 患有精细运动障碍（如帕金森病、脑瘫或运用障碍等所致）的人群，在与传统计算机界面交互时面临着巨大挑战。过往，脚本自动化虽提供了一定帮助，但其解决方案往往过于僵化且针对特定任务，难以满足用户的多元需求。大型语言模型（LLMs）的出现带来了更灵活的方式，能够解读自然语言指令以驾驭复杂的用户界面。然而，当下的LLMs常常误解用户意图，且当用户指令与文档对象模型（DOM）中的特定措辞不匹配时，没有备用措施。本研究推出了Dexterity Assist（DexAssist），这一双LLM系统旨在提升自动化用户界面控制的可靠性。两个LLM迭代运作以保障任务成功执行：Navigator LLM依据用户输入生成操作，而Support LLM评估这些操作的成效，并依据DOM内容提供持续反馈。我们的框架在Support LLM的首轮迭代中，整体准确率提升了约36个百分点，凸显了其在实时纠错方面的有效性。本文的主要贡献在于设计了一种新颖的基于双LLM的无障碍系统、实现了该系统，并通过3个电子商务网站进行了初步评估。最后，我们强调了通过优化计算时间和微调来拓展此框架的潜力。

> Individuals with fine motor impairments, such as those caused by conditions like Parkinson's disease, cerebral palsy, or dyspraxia, face significant challenges in interacting with traditional computer interfaces. Historically, scripted automation has offered some assistance, but these solutions are often too rigid and task-specific, failing to adapt to the diverse needs of users. The advent of Large Language Models (LLMs) promised a more flexible approach, capable of interpreting natural language commands to navigate complex user interfaces. However, current LLMs often misinterpret user intent and have no fallback measures when user instructions do not directly align with the specific wording used in the Document Object Model (DOM). This research presents Dexterity Assist (DexAssist), a dual-LLM system designed to improve the reliability of automated user interface control. Both LLMs work iteratively to ensure successful task execution: the Navigator LLM generates actions based on user input, while the Support LLM assesses the success of these actions and provides continuous feedback based on the DOM content. Our framework displays an increase of ~36 percentage points in overall accuracy within the first iteration of the Support LLM, highlighting its effectiveness in resolving errors in real-time. The main contributions of this paper are the design of a novel dual LLM-based accessibility system, its implementation, and its initial evaluation using 3 e-commerce websites. We conclude by underscoring the potential to build on this framework by optimizing computation time and fine-tuning.

[Arxiv](https://arxiv.org/abs/2411.12214)