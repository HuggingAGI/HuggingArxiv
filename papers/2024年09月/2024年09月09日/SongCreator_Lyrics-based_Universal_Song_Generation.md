# SongCreator：以歌词为基础，实现通用歌曲生成

发布时间：2024年09月09日

`LLM应用` `人工智能`

> SongCreator: Lyrics-based Universal Song Generation

# 摘要

> 音乐是人类文化的重要组成部分，体现了人类的智慧和创造力，其中歌曲是不可或缺的一部分。尽管之前的研究已经探索了歌曲生成的各个方面，如歌唱声音、声乐构成和乐器编排等，但根据给定的歌词生成带有声乐和伴奏的歌曲仍然是一个重大挑战，阻碍了音乐生成模型在现实世界中的应用。为此，我们提出了SongCreator，一个旨在解决这一挑战的歌曲生成系统。该系统采用了一个精心设计的双序列语言模型（DSLM），用于捕捉歌曲生成中的声乐和伴奏信息，并引入了一个额外的注意力掩码策略，使模型能够理解、生成和编辑歌曲，适用于各种与歌曲相关的生成任务。实验结果显示，SongCreator在所有八个任务中均达到了最先进或具有竞争力的表现，特别是在歌词到歌曲和歌词到声乐方面，显著超越了以往的工作。此外，它还能通过不同的提示独立控制生成歌曲中声乐和伴奏的声学条件，展示了其广泛的应用潜力。我们的样本可在https://songcreator.github.io/获取。

> Music is an integral part of human culture, embodying human intelligence and creativity, of which songs compose an essential part. While various aspects of song generation have been explored by previous works, such as singing voice, vocal composition and instrumental arrangement, etc., generating songs with both vocals and accompaniment given lyrics remains a significant challenge, hindering the application of music generation models in the real world. In this light, we propose SongCreator, a song-generation system designed to tackle this challenge. The model features two novel designs: a meticulously designed dual-sequence language model (DSLM) to capture the information of vocals and accompaniment for song generation, and an additional attention mask strategy for DSLM, which allows our model to understand, generate and edit songs, making it suitable for various song-related generation tasks. Extensive experiments demonstrate the effectiveness of SongCreator by achieving state-of-the-art or competitive performances on all eight tasks. Notably, it surpasses previous works by a large margin in lyrics-to-song and lyrics-to-vocals. Additionally, it is able to independently control the acoustic conditions of the vocals and accompaniment in the generated song through different prompts, exhibiting its potential applicability. Our samples are available at https://songcreator.github.io/.

[Arxiv](https://arxiv.org/abs/2409.06029)