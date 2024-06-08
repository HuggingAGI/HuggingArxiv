# XL-HeadTags：借助多模态检索增强，实现多语言新闻标题与标签的精准生成

发布时间：2024年06月06日

`LLM应用

这篇论文主要探讨了如何利用语言模型（LLM）来生成新闻文章的标题和实体标签，以帮助读者更有效地筛选和理解内容。研究中提出了一个多模态多语言检索器，并创建了一个包含20种语言的数据集来验证其性能。此外，还开发了一套多语言文本处理与评估工具，以提高跨语言研究的精确性和效率。这些应用层面的研究和工作，符合LLM应用的分类。` `新闻媒体` `多语言处理`

> XL-HeadTags: Leveraging Multimodal Retrieval Augmentation for the Multilingual Generation of News Headlines and Tags

# 摘要

> 每日海量新闻文章让读者眼花缭乱，标题与实体标签成为引导读者判断内容价值的关键。尽管标题生成研究已颇丰，但标签生成领域仍待开垦，它能为读者精准导航至心仪话题。为抓住读者眼球，简洁性至关重要，这要求我们优化内容筛选策略，从长文中提炼精华，引导语言模型精准发力。为此，我们提出利用文章中的图像与标题等辅助信息，捕捉关键句，并通过指令调整的多样性，为多语言新闻创作标题与标签。我们创建了涵盖20种语言的XL-HeadTags数据集，通过广泛验证，展示了我们即插即用的多模态多语言检索器的卓越性能。此外，我们还推出了一套多语言文本处理与评估工具，极大地推动了跨语言研究的精确与效率。

> Millions of news articles published online daily can overwhelm readers. Headlines and entity (topic) tags are essential for guiding readers to decide if the content is worth their time. While headline generation has been extensively studied, tag generation remains largely unexplored, yet it offers readers better access to topics of interest. The need for conciseness in capturing readers' attention necessitates improved content selection strategies for identifying salient and relevant segments within lengthy articles, thereby guiding language models effectively. To address this, we propose to leverage auxiliary information such as images and captions embedded in the articles to retrieve relevant sentences and utilize instruction tuning with variations to generate both headlines and tags for news articles in a multilingual context. To make use of the auxiliary information, we have compiled a dataset named XL-HeadTags, which includes 20 languages across 6 diverse language families. Through extensive evaluation, we demonstrate the effectiveness of our plug-and-play multimodal-multilingual retrievers for both tasks. Additionally, we have developed a suite of tools for processing and evaluating multilingual texts, significantly contributing to the research community by enabling more accurate and efficient analysis across languages.

[Arxiv](https://arxiv.org/abs/2406.03776)