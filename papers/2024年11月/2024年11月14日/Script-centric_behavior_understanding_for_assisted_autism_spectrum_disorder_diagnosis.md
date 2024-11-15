# 以脚本为核心的行为理解，助力自闭症谱系障碍的诊断

发布时间：2024年11月14日

`LLM应用` `儿童健康`

> Script-centric behavior understanding for assisted autism spectrum disorder diagnosis

# 摘要

> 观察和分析儿童的社会行为对自闭症谱系障碍（ASD）的早期诊断极为关键。此项工作聚焦于借助计算机视觉技术和大型语言模型（LLM）来自动检测 ASD。现有的方法普遍依赖监督学习。然而，ASD 诊断数据集的稀缺以及诊断结果缺乏可解释性，严重限制了其在临床上的应用。为应对这些挑战，我们引入了一种基于以脚本为中心的行为理解的全新无监督方法。我们的流程把视频内容转化为描述人物行为的脚本，借助大型语言模型的泛化能力，以零样本或少样本的方式检测 ASD。具体来说，我们提出了用于多模态行为数据文本化的脚本转录模块和连接 LLM 的领域提示模块。我们的方法在诊断平均年龄 24 个月的儿童 ASD 时准确率达 92.00％，比监督学习方法的性能绝对高出 3.58％。大量实验证实了我们方法的有效性，并显示出其通过 LLM 推动 ASD 研究的潜力。

> Observing and analyzing children's social behaviors is crucial for the early diagnosis of Autism Spectrum Disorders (ASD). This work focuses on automatically detecting ASD using computer vision techniques and large language models (LLMs). Existing methods typically rely on supervised learning. However, the scarcity of ASD diagnostic datasets and the lack of interpretability in diagnostic results significantly limits its clinical application. To address these challenges, we introduce a novel unsupervised approach based on script-centric behavior understanding. Our pipeline converts video content into scripts that describe the behavior of characters, leveraging the generalizability of large language models to detect ASD in a zero-shot or few-shot manner. Specifically, we propose a scripts transcription module for multimodal behavior data textualization and a domain prompts module to bridge LLMs. Our method achieves an accuracy of 92.00\% in diagnosing ASD in children with an average age of 24 months, surpassing the performance of supervised learning methods by 3.58\% absolutely. Extensive experiments confirm the effectiveness of our approach and suggest its potential for advancing ASD research through LLMs.

[Arxiv](https://arxiv.org/abs/2411.09413)