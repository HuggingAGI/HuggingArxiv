# 本研究致力于评估生成式搜索引擎在应对具有挑战性的对抗性事实问题时的稳定性和可靠性。

发布时间：2024年02月25日

`LLM应用` `搜索引擎` `人工智能安全`

> Evaluating Robustness of Generative Search Engine on Adversarial Factual Questions

# 摘要

> 生成式搜索引擎有望革新线上信息获取方式，但当前由LLMs支持的引擎生成的答案并不总能确保准确性。尤其是当对手利用检索增强生成技术，通过微调声明中的弱点就可能完全规避整个系统时，安全问题更为突出。因此，我们提议在贴近实战且高风险场景下检验生成式搜索引擎的稳健性，此时对手仅能黑盒操作系统，目标是欺骗模型输出错误答案。通过对诸如Bing Chat、PerplexityAI和YouChat等多款生成式搜索引擎的广泛查询进行全面人工评估，我们揭示了对抗性事实问题在引导模型产生错误回复方面的显著效果。而且，相较于不带检索功能的LLMs，检索增强型生成对于事实性错误更显脆弱。这些发现凸显此类系统的潜在安全风险，并着重强调在应用前必须进行严谨评估。

> Generative search engines have the potential to transform how people seek information online, but generated responses from existing large language models (LLMs)-backed generative search engines may not always be accurate. Nonetheless, retrieval-augmented generation exacerbates safety concerns, since adversaries may successfully evade the entire system by subtly manipulating the most vulnerable part of a claim. To this end, we propose evaluating the robustness of generative search engines in the realistic and high-risk setting, where adversaries have only black-box system access and seek to deceive the model into returning incorrect responses. Through a comprehensive human evaluation of various generative search engines, such as Bing Chat, PerplexityAI, and YouChat across diverse queries, we demonstrate the effectiveness of adversarial factual questions in inducing incorrect responses. Moreover, retrieval-augmented generation exhibits a higher susceptibility to factual errors compared to LLMs without retrieval. These findings highlight the potential security risks of these systems and emphasize the need for rigorous evaluation before deployment.

[Arxiv](https://arxiv.org/abs/2403.12077)