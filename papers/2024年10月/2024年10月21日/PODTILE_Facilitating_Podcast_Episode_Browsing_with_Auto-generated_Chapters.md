# PODTILE：借助自动生成的章节，轻松浏览播客剧集

发布时间：2024年10月21日

`LLM应用`

> PODTILE: Facilitating Podcast Episode Browsing with Auto-generated Chapters

# 摘要

> 听众在享受长篇播客时，常因难以把握整体结构和找到关键部分而感到困扰。一个巧妙的解决办法是将节目细分为章节，每个章节都有明确的标题和时间戳。然而，Spotify平台上多数播客尚未提供这些章节，因此自动化生成章节显得尤为重要。这一任务面临两大挑战：一是播客内容结构松散，讨论自发且过渡微妙；二是转录文本冗长，平均长达16,000个标记，需高效处理以保留上下文。为此，我们推出了PODTILE，一款专为对话数据设计的微调变换器，能同时生成章节过渡和标题。为确保上下文完整，输入文本还融入了全局信息，如节目标题、描述及前章标题。评估显示，PODTILE在ROUGE评分上超越最强基线11%。此外，我们发现自动生成的章节不仅方便听众，还为冷门播客增添了吸引力。最后，实证表明，章节标题能显著提升搜索任务中的检索效果。

> Listeners of long-form talk-audio content, such as podcast episodes, often find it challenging to understand the overall structure and locate relevant sections. A practical solution is to divide episodes into chapters--semantically coherent segments labeled with titles and timestamps. Since most episodes on our platform at Spotify currently lack creator-provided chapters, automating the creation of chapters is essential. Scaling the chapterization of podcast episodes presents unique challenges. First, episodes tend to be less structured than written texts, featuring spontaneous discussions with nuanced transitions. Second, the transcripts are usually lengthy, averaging about 16,000 tokens, which necessitates efficient processing that can preserve context. To address these challenges, we introduce PODTILE, a fine-tuned encoder-decoder transformer to segment conversational data. The model simultaneously generates chapter transitions and titles for the input transcript. To preserve context, each input text is augmented with global context, including the episode's title, description, and previous chapter titles. In our intrinsic evaluation, PODTILE achieved an 11% improvement in ROUGE score over the strongest baseline. Additionally, we provide insights into the practical benefits of auto-generated chapters for listeners navigating episode content. Our findings indicate that auto-generated chapters serve as a useful tool for engaging with less popular podcasts. Finally, we present empirical evidence that using chapter titles can enhance effectiveness of sparse retrieval in search tasks.

[Arxiv](https://arxiv.org/abs/2410.16148)