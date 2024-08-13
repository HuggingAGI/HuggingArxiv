# 借助大型语言模型，我们致力于提升钓鱼网站检测的精准度与解释的透明度。

发布时间：2024年08月10日

`LLM应用` `网络安全` `浏览器扩展`

> Utilizing Large Language Models to Optimize the Detection and Explainability of Phishing Websites

# 摘要

> 本文介绍 PhishLang，一款开源轻量级 LLM，专为通过网站上下文分析检测钓鱼网站设计。不同于依赖静态特征的传统模型和计算密集的深度学习模型，PhishLang 利用 LLM 的高级语言处理能力，学习钓鱼攻击的细粒度特征。它在最少数据预处理下运行，性能媲美顶尖深度学习工具，且速度更快、资源消耗更少。在 3.5 个月测试中，PhishLang 成功识别约 26K 钓鱼 URL，其中许多未被主流黑名单检测到，显示其辅助当前检测的潜力。我们还评估了其对抗现实攻击的能力，并开发六个补丁增强其鲁棒性。此外，PhishLang 与 GPT-3.5 Turbo 集成，实现“可解释黑名单”，为用户提供网站被标记为钓鱼的特征上下文信息。最后，我们开源了 PhishLang 框架，并开发了基于 Chromium 的浏览器扩展和 URL 扫描网站，为终端用户提供可解释的警告。

> In this paper, we introduce PhishLang, an open-source, lightweight Large Language Model (LLM) specifically designed for phishing website detection through contextual analysis of the website. Unlike traditional heuristic or machine learning models that rely on static features and struggle to adapt to new threats and deep learning models that are computationally intensive, our model utilizes the advanced language processing capabilities of LLMs to learn granular features that are characteristic of phishing attacks. Furthermore, PhishLang operates with minimal data preprocessing and offers performance comparable to leading deep learning tools, while being significantly faster and less resource-intensive. Over a 3.5-month testing period, PhishLang successfully identified approximately 26K phishing URLs, many of which were undetected by popular antiphishing blocklists, thus demonstrating its potential to aid current detection measures. We also evaluate PhishLang against several realistic adversarial attacks and develop six patches that make it very robust against such threats. Furthermore, we integrate PhishLang with GPT-3.5 Turbo to create \textit{explainable blocklisting} - warnings that provide users with contextual information about different features that led to a website being marked as phishing. Finally, we have open-sourced the PhishLang framework and developed a Chromium-based browser extension and URL scanner website, which implement explainable warnings for end-users.

[Arxiv](https://arxiv.org/abs/2408.05667)