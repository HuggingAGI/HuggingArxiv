# 利用大型视觉-语言模型，我们致力于假新闻的检测与操纵行为的推理。

发布时间：2024年07月02日

`LLM应用` `信息安全`

> Fake News Detection and Manipulation Reasoning via Large Vision-Language Models

# 摘要

> 随着媒体操纵的泛滥，假新闻已成为信息安全的一大隐患。学术界对假新闻检测的关注日益增加。传统模型虽在真伪分类上表现优异，但基于新闻内容推理伪造细节的能力尚待挖掘。此外，因缺乏外部知识，现有方法在处理事实相关新闻时的表现存疑，其实际应用效果不明。为此，我们提出“操纵推理”这一新课题，旨在通过新闻内容揭示操纵行为。为此，我们创建了以人为本、事实关联为核心的假新闻基准（HFFN），并详细标注。HFFN涵盖四个现实领域，通过三种操纵手法生成假新闻样本。我们还设计了多模态新闻检测与推理模型（M-DRUM），不仅能判断新闻真伪，还能分析潜在操纵。在特征提取上，我们采用交叉注意力机制，从多模态输入中提炼精细特征。推理方面，则依托大型视觉语言模型（LVLM）进行事实推理。通过两阶段训练框架，我们有效提升了模型的识别与推理能力。实验证明，M-DRUM在假新闻检测领域超越了现有顶尖模型，包括GPT-4和LLaVA。

> Fake news becomes a growing threat to information security and public opinion with the rapid sprawl of media manipulation. Therefore, fake news detection attracts widespread attention from academic community. Traditional fake news detection models demonstrate remarkable performance on authenticity binary classification but their ability to reason detailed faked traces based on the news content remains under-explored. Furthermore, due to the lack of external knowledge, the performance of existing methods on fact-related news is questionable, leaving their practical implementation unclear. In this paper, we propose a new multi-media research topic, namely manipulation reasoning. Manipulation reasoning aims to reason manipulations based on news content. To support the research, we introduce a benchmark for fake news detection and manipulation reasoning, referred to as Human-centric and Fact-related Fake News (HFFN). The benchmark highlights the centrality of human and the high factual relevance, with detailed manual annotations. HFFN encompasses four realistic domains with fake news samples generated through three manipulation approaches. Moreover, a Multi-modal news Detection and Reasoning langUage Model (M-DRUM) is presented not only to judge on the authenticity of multi-modal news, but also raise analytical reasoning about potential manipulations. On the feature extraction level, a cross-attention mechanism is employed to extract fine-grained fusion features from multi-modal inputs. On the reasoning level, a large vision-language model (LVLM) serves as the backbone to facilitate fact-related reasoning. A two-stage training framework is deployed to better activate the capacity of identification and reasoning. Comprehensive experiments demonstrate that our model outperforms state-of-the-art (SOTA) fake news detection models and powerful LVLMs like GPT-4 and LLaVA.

[Arxiv](https://arxiv.org/abs/2407.02042)