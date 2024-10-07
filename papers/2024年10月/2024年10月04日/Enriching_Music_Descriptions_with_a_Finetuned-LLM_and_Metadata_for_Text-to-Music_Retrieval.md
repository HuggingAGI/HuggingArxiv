# 借助微调的 LLM 和元数据，我们为音乐描述增添了更多色彩，从而提升了文本到音乐的检索效果。

发布时间：2024年10月04日

`LLM应用` `内容发现`

> Enriching Music Descriptions with a Finetuned-LLM and Metadata for Text-to-Music Retrieval

# 摘要

> 文本到音乐检索在音乐数据库的内容发现中至关重要。以往研究多聚焦于音乐音频与文本的联合嵌入，以精确匹配描述性查询。然而，用户还希望探索与喜爱曲目或艺术家相似的音乐。为此，本文提出了TTMR++模型，结合微调的大型语言模型生成的丰富文本描述和元数据，从多个数据集中获取种子文本。实验表明，TTMR++在处理多样化的音乐文本查询时，优于现有的最先进模型。

> Text-to-Music Retrieval, finding music based on a given natural language query, plays a pivotal role in content discovery within extensive music databases. To address this challenge, prior research has predominantly focused on a joint embedding of music audio and text, utilizing it to retrieve music tracks that exactly match descriptive queries related to musical attributes (i.e. genre, instrument) and contextual elements (i.e. mood, theme). However, users also articulate a need to explore music that shares similarities with their favorite tracks or artists, such as \textit{I need a similar track to Superstition by Stevie Wonder}. To address these concerns, this paper proposes an improved Text-to-Music Retrieval model, denoted as TTMR++, which utilizes rich text descriptions generated with a finetuned large language model and metadata. To accomplish this, we obtained various types of seed text from several existing music tag and caption datasets and a knowledge graph dataset of artists and tracks. The experimental results show the effectiveness of TTMR++ in comparison to state-of-the-art music-text joint embedding models through a comprehensive evaluation involving various musical text queries.

[Arxiv](https://arxiv.org/abs/2410.03264)