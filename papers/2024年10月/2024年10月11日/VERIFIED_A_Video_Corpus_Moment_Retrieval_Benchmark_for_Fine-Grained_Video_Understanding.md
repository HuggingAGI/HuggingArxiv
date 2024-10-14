# VERIFIED：细粒度视频理解的视频帧检索基准

发布时间：2024年10月11日

`LLM应用` `视频分析` `数据标注`

> VERIFIED: A Video Corpus Moment Retrieval Benchmark for Fine-Grained Video Understanding

# 摘要

> 现有的VCMR方法在粗粒度理解上受限，难以应对细粒度查询的精确时刻定位。为此，我们提出了一个更具挑战性的细粒度VCMR基准，要求模型从众多候选中精准定位最佳匹配时刻。为提升数据集构建效率与标注质量，我们设计了VERIFIED，一个自动化的视频-文本标注流水线，生成具有可靠细粒度统计与动态信息的标题。通过结合大型语言模型与多模态模型，我们生成了多样化的细粒度标题，并利用细粒度感知噪声评估器过滤不准确标注。最终，我们构建了包含Charades-FIG、DiDeMo-FIG和ActivityNet-FIG的高质量细粒度VCMR基准，评估显示现有模型在细粒度视频理解上仍有巨大提升空间。代码与数据集已公开，详见\href{https://github.com/hlchen23/VERIFIED}{https://github.com/hlchen23/VERIFIED}。

> Existing Video Corpus Moment Retrieval (VCMR) is limited to coarse-grained understanding, which hinders precise video moment localization when given fine-grained queries. In this paper, we propose a more challenging fine-grained VCMR benchmark requiring methods to localize the best-matched moment from the corpus with other partially matched candidates. To improve the dataset construction efficiency and guarantee high-quality data annotations, we propose VERIFIED, an automatic \underline{V}id\underline{E}o-text annotation pipeline to generate captions with \underline{R}el\underline{I}able \underline{FI}n\underline{E}-grained statics and \underline{D}ynamics. Specifically, we resort to large language models (LLM) and large multimodal models (LMM) with our proposed Statics and Dynamics Enhanced Captioning modules to generate diverse fine-grained captions for each video. To filter out the inaccurate annotations caused by the LLM hallucination, we propose a Fine-Granularity Aware Noise Evaluator where we fine-tune a video foundation model with disturbed hard-negatives augmented contrastive and matching losses. With VERIFIED, we construct a more challenging fine-grained VCMR benchmark containing Charades-FIG, DiDeMo-FIG, and ActivityNet-FIG which demonstrate a high level of annotation quality. We evaluate several state-of-the-art VCMR models on the proposed dataset, revealing that there is still significant scope for fine-grained video understanding in VCMR. Code and Datasets are in \href{https://github.com/hlchen23/VERIFIED}{https://github.com/hlchen23/VERIFIED}.

[Arxiv](https://arxiv.org/abs/2410.08593)