# 多模态兴趣点推荐系统

发布时间：2024年10月04日

`LLM应用`

> Multimodal Point-of-Interest Recommendation

# 摘要

> 大型语言模型已应用于推荐任务，如购物和阅读新闻。兴趣点推荐是基于多模态数据集的新兴领域。我们首先通过餐厅推荐来验证概念，基于用户的过往访问记录。选择餐厅时，用户会考虑类型、位置及菜品图片。我们利用LLaVA模型将图片转为文本，结合Foursquare和FoodX-251数据集，构建了伪餐厅签到数据集，并采用2023年提出的Recformer框架。结果显示，包含图片描述的半多模态模型表现更佳，这表明模型更贴近人类行为，我们的多模态推荐研究方向正确。

> Large Language Models are applied to recommendation tasks such as items to buy and news articles to read. Point of Interest is quite a new area to sequential recommendation based on language representations of multimodal datasets. As a first step to prove our concepts, we focused on restaurant recommendation based on each user's past visit history. When choosing a next restaurant to visit, a user would consider genre and location of the venue and, if available, pictures of dishes served there. We created a pseudo restaurant check-in history dataset from the Foursquare dataset and the FoodX-251 dataset by converting pictures into text descriptions with a multimodal model called LLaVA, and used a language-based sequential recommendation framework named Recformer proposed in 2023. A model trained on this semi-multimodal dataset has outperformed another model trained on the same dataset without picture descriptions. This suggests that this semi-multimodal model reflects actual human behaviours and that our path to a multimodal recommendation model is in the right direction.

[Arxiv](https://arxiv.org/abs/2410.03265)