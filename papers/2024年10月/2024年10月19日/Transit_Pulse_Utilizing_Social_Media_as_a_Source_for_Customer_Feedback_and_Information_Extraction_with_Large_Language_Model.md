# Transit Pulse：借助社交媒体，结合大型语言模型，获取客户反馈与信息提取。

发布时间：2024年10月19日

`LLM应用` `公共交通` `社交媒体分析`

> Transit Pulse: Utilizing Social Media as a Source for Customer Feedback and Information Extraction with Large Language Model

# 摘要

> 每天，公共交通用户在社交媒体上分享的帖子中蕴含着提升服务质量的关键见解。这些信息帮助交通机构迅速发现问题。解析这些帖子的主题和情感，是推动服务进步的关键。然而，海量的信息让手动分析变得不切实际，而传统NLP技术如TF-IDF在处理复杂情感时显得力不从心。传统情感分析方法在整合主题和情感前先分离它们，往往忽视了两者间的互动，这不仅增加了分类难度，还降低了分析效率。为此，我们提出了一种新方法，利用大型语言模型（如Llama 3）进行无预设主题的简化分析，并结合检索增强生成（RAG）技术，将外部知识融入信息提取过程。通过与传统NLP方法的对比实验，我们验证了该方法在真实交通系统数据上的有效性。实验结果表明，LLM在公共交通领域社交媒体数据分析中具有巨大潜力，能够提供更丰富的信息，助力交通机构更迅速、更精准地响应。

> Users of the transit system flood social networks daily with messages that contain valuable insights crucial for improving service quality. These posts help transit agencies quickly identify emerging issues. Parsing topics and sentiments is key to gaining comprehensive insights to foster service excellence. However, the volume of messages makes manual analysis impractical, and standard NLP techniques like Term Frequency-Inverse Document Frequency (TF-IDF) fall short in nuanced interpretation. Traditional sentiment analysis separates topics and sentiments before integrating them, often missing the interaction between them. This incremental approach complicates classification and reduces analytical productivity. To address these challenges, we propose a novel approach to extracting and analyzing transit-related information, including sentiment and sarcasm detection, identification of unusual system problems, and location data from social media. Our method employs Large Language Models (LLM), specifically Llama 3, for a streamlined analysis free from pre-established topic labels. To enhance the model's domain-specific knowledge, we utilize Retrieval-Augmented Generation (RAG), integrating external knowledge sources into the information extraction pipeline. We validated our method through extensive experiments comparing its performance with traditional NLP approaches on user tweet data from the real world transit system. Our results demonstrate the potential of LLMs to transform social media data analysis in the public transit domain, providing actionable insights and enhancing transit agencies' responsiveness by extracting a broader range of information.

[Arxiv](https://arxiv.org/abs/2410.15016)