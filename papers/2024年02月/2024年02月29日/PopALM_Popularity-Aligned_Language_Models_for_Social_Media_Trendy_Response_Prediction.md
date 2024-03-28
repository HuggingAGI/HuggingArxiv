# PopALM 是一款针对社交媒体趋势回应预测设计的流行度匹配语言模型，它致力于通过结合流行度信息提升对社交媒体热点话题响应预测的准确性。

发布时间：2024年02月29日

`Agent`

> PopALM: Popularity-Aligned Language Models for Social Media Trendy Response Prediction

# 摘要

> 面对社交媒体平台上每日涌现的海量事件，我们致力于研究趋势响应预测技术，旨在自动生成针对各类事件的高赞用户回复。不同于以往忽视回应流行度的做法，我们创新提出流行度对齐语言模型（PopALM），借助强化学习有效区分受众更广泛的热门回应。考虑到用户点赞数据的噪声标签问题，我们巧妙地在近端策略优化（PPO）框架内融入课程学习策略，引导模型优先掌握关键样例，实现由简至繁的高效训练。实验证明，在我们构建的大规模微博趋势响应预测数据集上，PopALM成功助力提升先进语言模型的表现力。

> Social media platforms are daily exhibiting millions of events. To preliminarily predict the mainstream public reaction to these events, we study trendy response prediction to automatically generate top-liked user replies to social media events. While previous works focus on generating responses without factoring in popularity, we propose Popularity-Aligned Language Models (PopALM) to distinguish responses liked by a larger audience through reinforcement learning. Recognizing the noisy labels from user "likes", we tailor-make curriculum learning in proximal policy optimization (PPO) to help models capture the essential samples for easy-to-hard training. In experiments, we build a large-scale Weibo dataset for trendy response prediction, and its results show that PopALM can help boost the performance of advanced language models.

[Arxiv](https://arxiv.org/abs/2402.18950)