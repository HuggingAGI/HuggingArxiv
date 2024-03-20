# 本研究针对生成式搜索引擎，探讨其在面对具有挑战性的对抗性事实问题时的鲁棒性表现。

发布时间：2024年02月25日

`Agent` `搜索引擎` `信息安全`

> Evaluating Robustness of Generative Search Engine on Adversarial Factual Questions

> 生成式搜索引擎有望革新线上信息检索方式，但由现有LLMs支撑的引擎生成的回答并非始终精准可靠。而强化检索式生成技术则加大了安全顾虑，因为攻击者可能通过巧妙操控表述中的弱点避开整个系统。为此，我们建议在真实且高风险环境中测试生成式搜索引擎的抗干扰能力，此时攻击者仅有黑盒系统访问权限，尝试诱使模型给出错误答案。我们通过对Bing Chat、PerplexityAI和YouChat等各类生成式搜索引擎进行全面且多样的查询测试，有力展示了对抗性事实问题诱发错误回复的有效性。同时，相较于没有检索功能的LLMs，强化检索式生成模型对事实性错误更加敏感。这些研究结果揭示了这类系统的潜在安全隐患，着重强调了在应用前必须进行严谨评估的重要性。

> Generative search engines have the potential to transform how people seek information online, but generated responses from existing large language models (LLMs)-backed generative search engines may not always be accurate. Nonetheless, retrieval-augmented generation exacerbates safety concerns, since adversaries may successfully evade the entire system by subtly manipulating the most vulnerable part of a claim. To this end, we propose evaluating the robustness of generative search engines in the realistic and high-risk setting, where adversaries have only black-box system access and seek to deceive the model into returning incorrect responses. Through a comprehensive human evaluation of various generative search engines, such as Bing Chat, PerplexityAI, and YouChat across diverse queries, we demonstrate the effectiveness of adversarial factual questions in inducing incorrect responses. Moreover, retrieval-augmented generation exhibits a higher susceptibility to factual errors compared to LLMs without retrieval. These findings highlight the potential security risks of these systems and emphasize the need for rigorous evaluation before deployment.

[Arxiv](https://arxiv.org/abs/2403.12077)