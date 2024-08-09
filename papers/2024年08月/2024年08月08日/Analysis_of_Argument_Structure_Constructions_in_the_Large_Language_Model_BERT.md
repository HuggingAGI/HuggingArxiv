# 探究 BERT 模型中的论点结构构造

发布时间：2024年08月08日

`LLM理论` `语言处理` `神经科学`

> Analysis of Argument Structure Constructions in the Large Language Model BERT

# 摘要

> 本研究深入探讨了BERT如何处理和表示论元结构构造（ASCs），并扩展了以往基于LSTM的分析。我们采用了一个包含2000个句子、涵盖四种ASC类型的数据集，详细分析了BERT在12层中的词嵌入。通过MDS和t-SNE的可视化技术以及广义判别值（GDV）量化的聚类方法，我们揭示了BERT在不同层次上的处理特性。前馈分类器（探针）从嵌入中准确预测构造类别，显示出从第2层开始超过90%的准确性，揭示了潜在的构造信息。注意力权重的Fisher判别比（FDR）分析进一步确认了OBJ词在区分ASCs中的关键作用，以及VERB和DET词的重要性。本研究不仅强调了BERT对语言构造的分层处理，还突显了其与LSTM的差异。未来研究将结合神经影像数据，深入探索ASC处理的神经基础，进一步揭示神经语言模型在模拟人脑语言处理方面的潜力，为理解语言的计算和神经机制提供新的视角。

> This study investigates how BERT processes and represents Argument Structure Constructions (ASCs), extending previous LSTM analyses. Using a dataset of 2000 sentences across four ASC types (transitive, ditransitive, caused-motion, resultative), we analyzed BERT's token embeddings across 12 layers. Visualizations with MDS and t-SNE and clustering quantified by Generalized Discrimination Value (GDV) were used. Feedforward classifiers (probes) predicted construction categories from embeddings. CLS token embeddings clustered best in layers 2-4, decreased in intermediate layers, and slightly increased in final layers. DET and SUBJ embeddings showed consistent clustering in intermediate layers, VERB embeddings increased in clustering from layer 1 to 12, and OBJ embeddings peaked in layer 10. Probe accuracies indicated low construction information in layer 1, with over 90 percent accuracy from layer 2 onward, revealing latent construction information beyond GDV clustering. Fisher Discriminant Ratio (FDR) analysis of attention weights showed OBJ tokens were crucial for differentiating ASCs, followed by VERB and DET tokens. SUBJ, CLS, and SEP tokens had insignificant FDR scores. This study highlights BERT's layered processing of linguistic constructions and its differences from LSTMs. Future research will compare these findings with neuroimaging data to understand the neural correlates of ASC processing. This research underscores neural language models' potential to mirror linguistic processing in the human brain, offering insights into the computational and neural mechanisms underlying language understanding.

[Arxiv](https://arxiv.org/abs/2408.04270)