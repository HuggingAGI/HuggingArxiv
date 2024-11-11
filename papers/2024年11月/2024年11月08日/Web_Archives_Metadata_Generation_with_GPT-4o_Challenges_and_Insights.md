# 使用 GPT-4o 生成网络档案元数据：挑战与见解

发布时间：2024年11月08日

`LLM应用` `网络档案` `元数据`

> Web Archives Metadata Generation with GPT-4o: Challenges and Insights

# 摘要

> 当前，由于依赖人力，网络档案的元数据创建既耗时又昂贵。本文探讨了在新加坡网络档案中使用 gpt-4o 进行元数据生成，重点关注可扩展性、效率和成本效益。我们使用数据缩减技术处理了 112 个网络档案（WARC）文件，元数据生成成本显著降低了 99.9%。通过提示工程，我们生成了标题和摘要，并使用莱文斯坦距离和 BERTScore 进行了内在评估，还通过人类编目员使用 McNemar 检验进行了外在评估。结果表明，虽然我们的方法显著节省了成本并提高了效率，但人工策划的元数据在质量上仍具优势。该研究确定了关键挑战，包括内容不准确、幻觉和翻译问题，表明大型语言模型（LLMs）应作为人类编目员的补充而非替代品。未来的工作将侧重于优化提示、改进内容过滤，并通过试验较小的模型解决隐私问题。这项研究推进了 LLMs 在网络存档中的整合，为其当前能力提供了有价值的见解，并为未来的改进指明了方向。代码可在 https://github.com/masamune-prog/warc2summary 上获取，以供面临类似挑战的机构进一步开发和使用。

> Current metadata creation for web archives is time consuming and costly due to reliance on human effort. This paper explores the use of gpt-4o for metadata generation within the Web Archive Singapore, focusing on scalability, efficiency, and cost effectiveness. We processed 112 Web ARChive (WARC) files using data reduction techniques, achieving a notable 99.9% reduction in metadata generation costs. By prompt engineering, we generated titles and abstracts, which were evaluated both intrinsically using Levenshtein Distance and BERTScore, and extrinsically with human cataloguers using McNemar's test. Results indicate that while our method offers significant cost savings and efficiency gains, human curated metadata maintains an edge in quality. The study identifies key challenges including content inaccuracies, hallucinations, and translation issues, suggesting that Large Language Models (LLMs) should serve as complements rather than replacements for human cataloguers. Future work will focus on refining prompts, improving content filtering, and addressing privacy concerns through experimentation with smaller models. This research advances the integration of LLMs in web archiving, offering valuable insights into their current capabilities and outlining directions for future enhancements. The code is available at https://github.com/masamune-prog/warc2summary for further development and use by institutions facing similar challenges.

[Arxiv](https://arxiv.org/abs/2411.05409)