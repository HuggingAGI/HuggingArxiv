# 借助动量效应，提升越狱攻击的威力

发布时间：2024年05月02日

`分类：LLM应用` `网络安全` `机器学习`

> Boosting Jailbreak Attack with Momentum

# 摘要

> 大型语言模型（LLMs）在众多任务上取得了令人瞩目的成就，但它们对对抗性攻击的脆弱性依旧，尤其是广为人知的“越狱”攻击。最近，贪婪坐标梯度（GCG）攻击通过梯度启发式和贪婪搜索的结合，有效利用了这一弱点。然而，该攻击的效率问题成为了攻击流程中的一个瓶颈。为了克服这一局限，本文提出了一种新的思考方式，通过优化方法生成对抗性提示，以稳定优化过程并从前几次迭代中获得更多启发。具体而言，我们提出了**动量加速 G** rady **C** oordinate **G** radient（**M** AC）攻击，它在梯度启发式中加入了动量因子。实验结果显示，MAC 在对齐语言模型的梯度攻击中实现了显著的性能提升。相关代码已在 https://github.com/weizeming/momentum-attack-llm 上发布。

> Large Language Models (LLMs) have achieved remarkable success across diverse tasks, yet they remain vulnerable to adversarial attacks, notably the well-documented \textit{jailbreak} attack. Recently, the Greedy Coordinate Gradient (GCG) attack has demonstrated efficacy in exploiting this vulnerability by optimizing adversarial prompts through a combination of gradient heuristics and greedy search. However, the efficiency of this attack has become a bottleneck in the attacking process. To mitigate this limitation, in this paper we rethink the generation of adversarial prompts through an optimization lens, aiming to stabilize the optimization process and harness more heuristic insights from previous iterations. Specifically, we introduce the \textbf{M}omentum \textbf{A}ccelerated G\textbf{C}G (\textbf{MAC}) attack, which incorporates a momentum term into the gradient heuristic. Experimental results showcase the notable enhancement achieved by MAP in gradient-based attacks on aligned language models. Our code is available at https://github.com/weizeming/momentum-attack-llm.

[Arxiv](https://arxiv.org/abs/2405.01229)