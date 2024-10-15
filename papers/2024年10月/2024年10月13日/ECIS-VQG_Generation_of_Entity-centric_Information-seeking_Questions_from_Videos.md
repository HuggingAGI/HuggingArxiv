# ECIS-VQG：视频中实体导向的信息探索问题生成

发布时间：2024年10月13日

`LLM应用` `视频分析` `问答系统`

> ECIS-VQG: Generation of Entity-centric Information-seeking Questions from Videos

# 摘要

> 以往研究多聚焦于从视频中生成关于常见物体和属性的问题，而非以实体为中心。我们则专注于生成以实体为中心的信息寻求问题，这有助于视频学习、推荐相关问题、视频聊天机器人及事实核查。我们解决了三大挑战：识别关键信息、关联实体、利用多模态信号。目前尚无大规模相关数据集，现有数据集多关注电视节目、电影或人类活动，缺乏实体相关问题。为此，我们创建了包含411个视频和2265个手动注释问题的YouTube视频数据集VideoQuestions。我们还设计了结合Transformer、丰富上下文信号及交叉熵与对比损失函数的模型，以促进实体中心问题的生成。实验结果显示，我们的方法在BLEU、ROUGE、CIDEr和METEOR指标上分别达到71.3、78.6、7.31和81.9，证明了其实际应用价值。代码和数据集已公开，详见https://github.com/thePhukan/ECIS-VQG。

> Previous studies on question generation from videos have mostly focused on generating questions about common objects and attributes and hence are not entity-centric. In this work, we focus on the generation of entity-centric information-seeking questions from videos. Such a system could be useful for video-based learning, recommending ``People Also Ask'' questions, video-based chatbots, and fact-checking. Our work addresses three key challenges: identifying question-worthy information, linking it to entities, and effectively utilizing multimodal signals. Further, to the best of our knowledge, there does not exist a large-scale dataset for this task. Most video question generation datasets are on TV shows, movies, or human activities or lack entity-centric information-seeking questions. Hence, we contribute a diverse dataset of YouTube videos, VideoQuestions, consisting of 411 videos with 2265 manually annotated questions. We further propose a model architecture combining Transformers, rich context signals (titles, transcripts, captions, embeddings), and a combination of cross-entropy and contrastive loss function to encourage entity-centric question generation. Our best method yields BLEU, ROUGE, CIDEr, and METEOR scores of 71.3, 78.6, 7.31, and 81.9, respectively, demonstrating practical usability. We make the code and dataset publicly available. https://github.com/thePhukan/ECIS-VQG

[Arxiv](https://arxiv.org/abs/2410.09776)