# VideoOrion：将视频中对象的动态进行标记化处理

发布时间：2024年11月25日

`LLM应用` `语言模型`

> VideoOrion: Tokenizing Object Dynamics in Videos

# 摘要

> 我们推出了 VideoOrion 这一视频大型语言模型（Video-LLM），它能清晰捕捉视频中的关键语义信息，即整个视频中对象的时空动态。VideoOrion 借助专家视觉模型，通过检测-分割-跟踪流程提取对象动态，并通过聚合时空对象特征将其编码为一组对象标记。我们的方法攻克了 Video-LLM 长期存在的难题，即如何把高维视频数据高效压缩成语言模型能理解的语义标记。相比之前通过对原始视频下采样或用重采样器聚合视觉标记的方法，这些方法会造成信息丢失和语义混乱，VideoOrion 不但提供了更自然高效的途径来获取紧凑、清晰的语义表示，还能以极低的计算成本对视频内容进行明确的对象建模。而且，引入的对象标记让 VideoOrion 能够轻松完成基于视频的引用任务。实验结果显示，VideoOrion 能够学会充分利用对象标记，在一般视频问答和基于视频的引用基准测试中都取得了出色的成绩。

> We present VideoOrion, a Video Large Language Model (Video-LLM) that explicitly captures the key semantic information in videos--the spatial-temporal dynamics of objects throughout the videos. VideoOrion employs expert vision models to extract object dynamics through a detect-segment-track pipeline, encoding them into a set of object tokens by aggregating spatial-temporal object features. Our method addresses the persistent challenge in Video-LLMs of efficiently compressing high-dimensional video data into semantic tokens that are comprehensible to LLMs. Compared to prior methods which resort to downsampling the original video or aggregating visual tokens using resamplers, leading to information loss and entangled semantics, VideoOrion not only offers a more natural and efficient way to derive compact, disentangled semantic representations but also enables explicit object modeling of video content with minimal computational cost. Moreover, the introduced object tokens naturally allow VideoOrion to accomplish video-based referring tasks. Experimental results show that VideoOrion can learn to make good use of the object tokens, and achieves competitive results on both general video question answering and video-based referring benchmarks.

[Arxiv](https://arxiv.org/abs/2411.16156)