# 您的大型语言模型（LLM）是否秘密地是互联网的世界模型？基于模型的 Web 代理规划

发布时间：2024年11月10日

`Agent` `自动化`

> Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents

# 摘要

> 语言代理在自动化基于网络的任务方面已展现出有前景的能力，尽管它们目前的反应式方法与人类相比仍表现不佳。虽然结合先进的规划算法，特别是树搜索方法，可以提高这些代理的性能，但由于诸如确认购买等不可逆转的操作，直接在实时网站上实施树搜索会带来重大的安全风险和实际限制。在本文中，我们引入了一种新颖的范式，用基于模型的规划增强语言代理，开创了将大型语言模型（LLM）作为复杂网络环境中的世界模型的创新用途。我们的方法，WebDreamer，基于这样一个关键的见解，即LLM 本身就编码了关于网站结构和功能的综合知识。具体来说，WebDreamer 使用 LLM 用自然语言描述来模拟每个候选动作的结果（例如，“如果我点击这个按钮会发生什么？”），然后评估这些想象的结果以确定每一步的最佳动作。在两个具有在线交互的代表性网络代理基准——VisualWebArena 和 Mind2Web-live 上的实证结果表明，WebDreamer 比反应式基线有显著的改进。通过确立 LLM 在网络环境中作为世界模型的可行性，这项工作为自动化网络交互的范式转变奠定了基础。更广泛地说，我们的发现为未来的研究开辟了令人兴奋的新途径，包括 1）专门为复杂动态环境中的世界建模优化 LLM，以及 2）针对语言代理的基于模型的推测性规划。

> Language agents have demonstrated promising capabilities in automating web-based tasks, though their current reactive approaches still underperform largely compared to humans. While incorporating advanced planning algorithms, particularly tree search methods, could enhance these agents' performance, implementing tree search directly on live websites poses significant safety risks and practical constraints due to irreversible actions such as confirming a purchase. In this paper, we introduce a novel paradigm that augments language agents with model-based planning, pioneering the innovative use of large language models (LLMs) as world models in complex web environments. Our method, WebDreamer, builds on the key insight that LLMs inherently encode comprehensive knowledge about website structures and functionalities. Specifically, WebDreamer uses LLMs to simulate outcomes for each candidate action (e.g., "what would happen if I click this button?") using natural language descriptions, and then evaluates these imagined outcomes to determine the optimal action at each step. Empirical results on two representative web agent benchmarks with online interaction -- VisualWebArena and Mind2Web-live -- demonstrate that WebDreamer achieves substantial improvements over reactive baselines. By establishing the viability of LLMs as world models in web environments, this work lays the groundwork for a paradigm shift in automated web interaction. More broadly, our findings open exciting new avenues for future research into 1) optimizing LLMs specifically for world modeling in complex, dynamic environments, and 2) model-based speculative planning for language agents.

[Arxiv](https://arxiv.org/abs/2411.06559)