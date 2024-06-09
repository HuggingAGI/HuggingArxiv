# 对话搜索引擎中的排名操控策略

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了大型语言模型（LLM）在对话式搜索引擎中的应用，特别是在面对提示注入和越狱攻击时的表现和影响。研究集中在如何通过对抗性字符串影响LLM的安全性和质量目标，以及这些攻击如何改变搜索引擎对来源的排名顺序。因此，这篇论文属于LLM应用类别，因为它关注的是LLM在实际搜索引擎系统中的应用及其面临的挑战。` `搜索引擎` `网络安全`

> Ranking Manipulation for Conversational Search Engines

# 摘要

> 搜索引擎巨头正快速将大型语言模型（LLM）生成的内容融入用户查询响应中。这些对话式搜索引擎通过将网站文本载入LLM上下文进行摘要和解读来运作。最新研究揭示，LLM极易遭受越狱和提示注入攻击，这些攻击利用对抗性字符串破坏了LLM的安全性和质量目标。本研究深入探讨了提示注入如何影响对话式搜索引擎所引用来源的排名顺序。为此，我们精心挑选了真实世界消费者产品网站的数据集，并将对话式搜索排名问题定义为对抗性挑战。实验分析显示，在无对抗性注入的情况下，不同LLM在产品名称、文档内容及上下文位置的优先级上差异显著。我们进而提出了一种基于攻击树的越狱策略，有效提升了低排名产品的曝光率。这些攻击策略对顶尖对话式搜索引擎如perplexity.ai同样有效。鉴于网站所有者提升搜索排名的强烈经济动机，我们认为此问题定义对未来提升系统鲁棒性至关重要。

> Major search engine providers are rapidly incorporating Large Language Model (LLM)-generated content in response to user queries. These conversational search engines operate by loading retrieved website text into the LLM context for summarization and interpretation. Recent research demonstrates that LLMs are highly vulnerable to jailbreaking and prompt injection attacks, which disrupt the safety and quality goals of LLMs using adversarial strings. This work investigates the impact of prompt injections on the ranking order of sources referenced by conversational search engines. To this end, we introduce a focused dataset of real-world consumer product websites and formalize conversational search ranking as an adversarial problem. Experimentally, we analyze conversational search rankings in the absence of adversarial injections and show that different LLMs vary significantly in prioritizing product name, document content, and context position. We then present a tree-of-attacks-based jailbreaking technique which reliably promotes low-ranked products. Importantly, these attacks transfer effectively to state-of-the-art conversational search engines such as perplexity.ai. Given the strong financial incentive for website owners to boost their search ranking, we argue that our problem formulation is of critical importance for future robustness work.

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x1.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x2.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x3.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x4.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x5.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x6.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x7.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x8.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x9.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x10.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x11.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x12.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x13.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x14.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x15.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x16.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x17.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x18.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x19.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x20.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x21.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x22.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x23.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x24.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x25.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x26.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x27.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x28.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x29.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x30.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x31.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x32.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x33.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x34.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x35.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x36.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x37.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x38.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x39.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x40.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x41.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x42.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x43.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x44.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x45.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/smeg_clean.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/smeg_poisoned.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/1.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/2.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/3.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/1.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/2.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/3.png)

![对话搜索引擎中的排名操控策略](../../../paper_images/2406.03589/x46.png)

[Arxiv](https://arxiv.org/abs/2406.03589)