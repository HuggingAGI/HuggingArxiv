# LLM-Cure：利用 LLM 分析竞争对手用户评论，助力功能优化

发布时间：2024年09月24日

`LLM应用` `移动应用` `市场分析`

> LLM-Cure: LLM-based Competitor User Review Analysis for Feature Enhancement

# 摘要

> 移动应用市场的迅猛发展要求不断创新和快速响应用户需求。用户满意度是移动应用成功的关键，开发者通常依赖用户评论来发现改进点。然而，海量评论使得手动分析变得困难，需要自动化解决方案。现有方法要么忽略与竞争对手的比较，要么无法提供改进建议。为此，我们提出了基于LLM的竞争性用户评论分析工具LLM-Cure，它能自动生成功能改进建议。LLM-Cure通过分析评论中的功能，并结合竞争对手的高评分评论，为特定应用提供定制化改进方案。我们在70个热门应用的百万条评论上测试了LLM-Cure，结果显示其在功能分配上显著优于现有方法，F1分数提升13%，召回率提升16%，精确度提升11%。此外，LLM-Cure还能有效解决用户投诉，其建议的实施率高达73%。

> The exponential growth of the mobile app market underscores the importance of constant innovation and rapid response to user demands. As user satisfaction is paramount to the success of a mobile application (app), developers typically rely on user reviews, which represent user feedback that includes ratings and comments to identify areas for improvement. However, the sheer volume of user reviews poses challenges in manual analysis, necessitating automated approaches. Existing automated approaches either analyze only the target apps reviews, neglecting the comparison of similar features to competitors or fail to provide suggestions for feature enhancement. To address these gaps, we propose a Large Language Model (LLM)-based Competitive User Review Analysis for Feature Enhancement) (LLM-Cure), an approach powered by LLMs to automatically generate suggestion s for mobile app feature improvements. More specifically, LLM-Cure identifies and categorizes features within reviews by applying LLMs. When provided with a complaint in a user review, LLM-Cure curates highly rated (4 and 5 stars) reviews in competing apps related to the complaint and proposes potential improvements tailored to the target application. We evaluate LLM-Cure on 1,056,739 reviews of 70 popular Android apps. Our evaluation demonstrates that LLM-Cure significantly outperforms the state-of-the-art approaches in assigning features to reviews by up to 13% in F1-score, up to 16% in recall and up to 11% in precision. Additionally, LLM-Cure demonstrates its capability to provide suggestions for resolving user complaints. We verify the suggestions using the release notes that reflect the changes of features in the target mobile app. LLM-Cure achieves a promising average of 73% of the implementation of the provided suggestions.

[Arxiv](https://arxiv.org/abs/2409.15724)