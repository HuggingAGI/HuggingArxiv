# EVQAScore：高效的视频问答数据评估

发布时间：2024年11月11日

`LLM应用` `数据评估`

> EVQAScore: Efficient Video Question Answering Data Evaluation

# 摘要

> 视频问答（QA）是视频理解中的核心任务。评估用于训练视频大型语言模型（VideoLLMs）的视频 QA 和视频字幕数据质量是一项关键挑战。尽管已经提出了各种评估视频字幕质量的方法，但仍然缺乏专门用于视频 QA 的评估方法。为了解决这一差距，我们引入了 EVQAScore，这是一种无参考的方法，利用关键字提取来评估视频字幕和视频 QA 数据质量。此外，我们还结合了帧采样和重新缩放技术，以提高我们评估的效率和鲁棒性，这使我们的分数能够评估极长视频的质量。我们的方法在视频字幕评估的 VATEX-EVAL 基准上实现了最先进（SOTA）的性能（肯德尔相关性为 32.8，斯皮尔曼相关性为 42.3，分别比之前的方法 PAC-S++ 高 4.7 和 5.9）。此外，通过使用 EVQAScore 进行数据选择，我们仅使用原始数据量的 12.5％就取得了 SOTA 结果，优于之前的 SOTA 方法 PAC-S 和 100％的数据。

> Video question-answering (QA) is a core task in video understanding. Evaluating the quality of video QA and video caption data quality for training video large language models (VideoLLMs) is an essential challenge. Although various methods have been proposed for assessing video caption quality, there remains a lack of dedicated evaluation methods for Video QA. To address this gap, we introduce EVQAScore, a reference-free method that leverages keyword extraction to assess both video caption and video QA data quality. Additionally, we incorporate frame sampling and rescaling techniques to enhance the efficiency and robustness of our evaluation, this enables our score to evaluate the quality of extremely long videos. Our approach achieves state-of-the-art (SOTA) performance (32.8 for Kendall correlation and 42.3 for Spearman correlation, 4.7 and 5.9 higher than the previous method PAC-S++) on the VATEX-EVAL benchmark for video caption evaluation. Furthermore, by using EVQAScore for data selection, we achieved SOTA results with only 12.5\% of the original data volume, outperforming the previous SOTA method PAC-S and 100\% of data.

[Arxiv](https://arxiv.org/abs/2411.06908)