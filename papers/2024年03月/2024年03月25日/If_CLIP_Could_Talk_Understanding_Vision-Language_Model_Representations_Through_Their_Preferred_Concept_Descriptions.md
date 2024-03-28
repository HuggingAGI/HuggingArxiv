# 设想 CLIP 能言，我们通过探究其倾向使用的概念描述方式，以深入理解视觉-语言模型的内在表征机制。（注：由于原句较短且生动活泼，直译已经相对简洁优雅，因此步骤2在保持原意的基础上稍作调整，使其更符合中文阅读习惯。）

发布时间：2024年03月25日

`Agent` `视觉模型`

> If CLIP Could Talk: Understanding Vision-Language Model Representations Through Their Preferred Concept Descriptions

# 摘要

> 近期研究表明，人们常认为VLM的表现基础是形状等视觉属性，但VLM如何优先处理这些信息以构建概念表征尚不明晰。为此，我们创新性地提出了一种名为“提取与探索”（EX2）的方法，用于挖掘对VLM至关重要的文本特征。该方法运用强化学习技术，让大型语言模型适应VLM的喜好，生成能够体现VLM关键特征的描述。然后，通过对这些描述进行深入审查，识别出构成VLM表征的关键特征。研究发现，虽然某些看似无关紧要的描述（如“点击放大CONCEPT图片”）并无实际帮助，但却在VLM表征中占据重要地位。更为关键的是，在具有信息价值的描述中，VLM在表现视觉概念时大量依赖非视觉属性，如生物的栖息地。同时，我们还发现不同的VLM在构建表征时对各类属性的重视程度各有不同。综上所述，我们揭示了VLM并非仅仅将图像与场景描述一一对应，非视觉甚至无关描述实际上对其表征有着显著影响。

> Recent works often assume that Vision-Language Model (VLM) representations are based on visual attributes like shape. However, it is unclear to what extent VLMs prioritize this information to represent concepts. We propose Extract and Explore (EX2), a novel approach to characterize important textual features for VLMs. EX2 uses reinforcement learning to align a large language model with VLM preferences and generates descriptions that incorporate the important features for the VLM. Then, we inspect the descriptions to identify the features that contribute to VLM representations. We find that spurious descriptions have a major role in VLM representations despite providing no helpful information, e.g., Click to enlarge photo of CONCEPT. More importantly, among informative descriptions, VLMs rely significantly on non-visual attributes like habitat to represent visual concepts. Also, our analysis reveals that different VLMs prioritize different attributes in their representations. Overall, we show that VLMs do not simply match images to scene descriptions and that non-visual or even spurious descriptions significantly influence their representations.

[Arxiv](https://arxiv.org/abs/2403.16442)