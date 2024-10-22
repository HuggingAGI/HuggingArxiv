# 结合大型语言模型与跨受试者训练，评估 P300 拼写器的性能表现。

发布时间：2024年10月19日

`LLM应用` `脑机接口`

> Evaluation Of P300 Speller Performance Using Large Language Models Along With Cross-Subject Training

# 摘要

> 肌萎缩侧索硬化症 (ALS) 是一种进行性神经肌肉退行性疾病，发病几年内严重限制了患者的沟通能力，导致生活质量显著下降。P300 拼写器脑机接口 (BCI) 通过利用受试者对图形用户界面 (GUI) 上字符网格中传统高亮字符的 EEG 反应，提供了一种替代的沟通媒介。本研究通过解决多受试者分类器训练中的关键限制，并结合先进的语言模型来优化刺激呈现和单词预测，从而提高沟通效率。此外，生成预训练变压器 (GPT2)、BERT 和 BART 等先进的大型语言模型，以及 Dijkstra 算法，被用于优化刺激并根据拼写历史提供单词完成选项。通过基于从受试者随机抽样的 EEG 数据进行广泛的模拟，我们展示了在包含罕见和词汇外 (OOV) 单词的打字段落中显著的速度提升，提升的程度因所使用的语言模型而异。通过这种字符级接口优化获得的收益约为 10%，而 GPT2 用于多词预测提供了约 40% 的收益。特别是，一些大型语言模型达到了本研究中建立的理论性能极限的 10% 以内。此外，在受试者内部和跨受试者中，都探索了训练技术，并显示速度提升在这两种情况下都有效。

> Amyotrophic lateral sclerosis (ALS), a progressive neuromuscular degenerative disease, severely restricts patient communication capacity within a few years of onset, resulting in a significant deterioration of quality of life. The P300 speller brain computer interface (BCI) offers an alternative communication medium by leveraging a subject's EEG response to characters traditionally highlighted on a character grid on a graphical user interface (GUI). A recurring theme in P300-based research is enhancing performance to enable faster subject interaction. This study builds on that theme by addressing key limitations, particularly in the training of multi-subject classifiers, and by integrating advanced language models to optimize stimuli presentation and word prediction, thereby improving communication efficiency. Furthermore, various advanced large language models such as Generative Pre-Trained Transformer (GPT2), BERT, and BART, alongside Dijkstra's algorithm, are utilized to optimize stimuli and provide word completion choices based on the spelling history. In addition, a multi-layered smoothing approach is applied to allow for out-of-vocabulary (OOV) words. By conducting extensive simulations based on randomly sampled EEG data from subjects, we show substantial speed improvements in typing passages that include rare and out-of-vocabulary (OOV) words, with the extent of improvement varying depending on the language model utilized. The gains through such character-level interface optimizations are approximately 10%, and GPT2 for multi-word prediction provides gains of around 40%. In particular, some large language models achieve performance levels within 10% of the theoretical performance limits established in this study. In addition, both within and across subjects, training techniques are explored, and speed improvements are shown to hold in both cases.

[Arxiv](https://arxiv.org/abs/2410.15161)