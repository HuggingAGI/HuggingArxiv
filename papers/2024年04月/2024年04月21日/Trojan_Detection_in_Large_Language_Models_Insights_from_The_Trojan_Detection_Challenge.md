# 探索大型语言模型中的特洛伊木马识别：特洛伊木马检测挑战赛的深刻见解。

发布时间：2024年04月21日

`LLM应用` `网络安全` `人工智能`

> Trojan Detection in Large Language Models: Insights from The Trojan Detection Challenge

# 摘要

> 大型语言模型（LLMs）在众多领域展现了卓越性能，但其对特洛伊木马或后门攻击的易感性也带来了严重的安全隐患。本文回顾了2023年特洛伊木马检测竞赛（TDC2023），该竞赛集中探讨了如何识别和评估针对LLMs的特洛伊木马攻击。研究中，我们深入分析了区分有意与无意触发器的难点，以及在现实世界情境下逆向工程特洛伊木马的实际操作性。通过对比多种特洛伊木马检测技术，我们发现要达到高召回率比实现高逆向工程攻击成功率（REASR）更为困难。竞赛中脱颖而出的顶尖方法，其召回率大约为0.16，这与随机抽样句子的简单基线方法相当。这一发现引发了关于仅凭有害目标信息，模型中特洛伊木马的可探测性和可恢复性的疑问。尽管问题尚未完全解决，但竞赛已经为特洛伊木马检测的可行性和优化LLM输入提示的技术提供了有益的见解。非预期触发器的存在及其与预期触发器的区分难度，凸显了对LLMs鲁棒性和可解释性进行更深入研究的必要。TDC2023不仅为LLMs特洛伊木马检测的挑战和机遇提供了深刻见解，还为未来确保其在现实世界应用中的安全性和可靠性的研究奠定了坚实基础。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in various domains, but their vulnerability to trojan or backdoor attacks poses significant security risks. This paper explores the challenges and insights gained from the Trojan Detection Competition 2023 (TDC2023), which focused on identifying and evaluating trojan attacks on LLMs. We investigate the difficulty of distinguishing between intended and unintended triggers, as well as the feasibility of reverse engineering trojans in real-world scenarios. Our comparative analysis of various trojan detection methods reveals that achieving high Recall scores is significantly more challenging than obtaining high Reverse-Engineering Attack Success Rate (REASR) scores. The top-performing methods in the competition achieved Recall scores around 0.16, comparable to a simple baseline of randomly sampling sentences from a distribution similar to the given training prefixes. This finding raises questions about the detectability and recoverability of trojans inserted into the model, given only the harmful targets. Despite the inability to fully solve the problem, the competition has led to interesting observations about the viability of trojan detection and improved techniques for optimizing LLM input prompts. The phenomenon of unintended triggers and the difficulty in distinguishing them from intended triggers highlights the need for further research into the robustness and interpretability of LLMs. The TDC2023 has provided valuable insights into the challenges and opportunities associated with trojan detection in LLMs, laying the groundwork for future research in this area to ensure their safety and reliability in real-world applications.

[Arxiv](https://arxiv.org/abs/2404.13660)