# 利用 ChatGPT 自动解析场景，提取用例组件的深入分析

发布时间：2024年08月06日

`LLM应用` `软件开发` `移动应用`

> An Analysis of Automated Use Case Component Extraction from Scenarios using ChatGPT

# 摘要

> 在移动应用开发的初期，由于资源有限，开发者往往更专注于开发和发布，而需求获取活动如访谈则相对次要。随着市场竞争加剧，应用需求也不断变化。当开发公司开始标准化流程时，需求记录和分析变得重要。我们提出了一种利用大型语言模型从用户编写的使用场景中提取用例组件的低成本方法。通过优化提示以包含领域知识，我们提高了提取用例组件的精确度和质量。

> Mobile applications (apps) are often developed by only a small number of developers with limited resources, especially in the early years of the app's development. In this setting, many requirements acquisition activities, such as interviews, are challenging or lower priority than development and release activities. Moreover, in this early period, requirements are frequently changing as mobile apps evolve to compete in the marketplace. As app development companies move to standardize their development processes, however, they will shift to documenting and analyzing requirements. One low-cost source of requirements post-deployment are user-authored scenarios describing how they interact with an app. We propose a method for extracting use case components from user-authored scenarios using large language models (LLMs). The method consists of a series of prompts that were developed to improve precision and recall on a ground truth dataset of 50 scenarios independently labeled with UC components. Our results reveal that LLMs require additional domain knowledge to extract UC components, and that refining prompts to include this knowledge improves the quality of the extracted UC components.

[Arxiv](https://arxiv.org/abs/2408.03395)