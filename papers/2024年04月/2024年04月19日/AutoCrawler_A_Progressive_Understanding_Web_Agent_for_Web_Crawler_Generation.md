# AutoCrawler：一种渐进式理解的网络代理，专为网络爬虫的生成而设计。

发布时间：2024年04月19日

`分类：Agent` `网络自动化` `网页爬虫`

> AutoCrawler: A Progressive Understanding Web Agent for Web Crawler Generation

# 摘要

> 网络自动化技术通过模拟常规网络行为，自动化执行复杂网络操作，以此提升工作效率并降低手工操作的必要性。面对新网站，传统包装器等方法因适应性与扩展性不足而受限。与此同时，由大型语言模型（LLMs）驱动的生成代理在开放环境下的表现和可复用性亦不尽人意。本研究提出了一种针对垂直信息网页的爬虫生成任务，并引入了结合LLMs与爬虫的新范式，以助爬虫更高效地适应多变的网络环境。我们设计了AutoCrawler，这是一个分两阶段的框架，它利用HTML的层级结构实现渐进式理解。通过自顶向下和回溯操作，AutoCrawler能够从错误中学习，不断优化HTML结构，以提升动作生成的准确性。我们在多个LLMs上进行了广泛的实验，验证了该框架的有效性。本文的相关资源可在 \url{https://github.com/EZ-hwh/AutoCrawler} 获取。

> Web automation is a significant technique that accomplishes complicated web tasks by automating common web actions, enhancing operational efficiency, and reducing the need for manual intervention. Traditional methods, such as wrappers, suffer from limited adaptability and scalability when faced with a new website. On the other hand, generative agents empowered by large language models (LLMs) exhibit poor performance and reusability in open-world scenarios. In this work, we introduce a crawler generation task for vertical information web pages and the paradigm of combining LLMs with crawlers, which helps crawlers handle diverse and changing web environments more efficiently. We propose AutoCrawler, a two-stage framework that leverages the hierarchical structure of HTML for progressive understanding. Through top-down and step-back operations, AutoCrawler can learn from erroneous actions and continuously prune HTML for better action generation. We conduct comprehensive experiments with multiple LLMs and demonstrate the effectiveness of our framework. Resources of this paper can be found at \url{https://github.com/EZ-hwh/AutoCrawler}

![AutoCrawler：一种渐进式理解的网络代理，专为网络爬虫的生成而设计。](../../../paper_images/2404.12753/x1.png)

![AutoCrawler：一种渐进式理解的网络代理，专为网络爬虫的生成而设计。](../../../paper_images/2404.12753/x2.png)

[Arxiv](https://arxiv.org/abs/2404.12753)