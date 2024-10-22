# 探索大型语言模型中的因果关系

发布时间：2024年10月20日

`LLM理论` `人工智能` `机器学习`

> Causality for Large Language Models

# 摘要

> 人工智能的最新突破引领了范式转变，数十亿或数万亿参数的 LLM 在海量数据集上训练，横扫语言任务。然而，尽管成绩斐然，LLM 仍依赖概率建模，常捕捉语言模式和社会刻板印象中的虚假关联，而非实体与事件间的真正因果。这使其易受人口偏见、社会刻板印象及幻觉等问题困扰。这些挑战呼唤将因果融入 LLM，超越相关驱动，打造更可靠、合伦理的 AI 系统。现有研究多聚焦于提示工程激活 LLM 因果知识或开发基准评估其因果推理，多需人工干预激活预训练模型。如何将因果嵌入 LLM 训练，构建更通用智能模型，仍待探索。近期研究揭示，LLM 如因果鹦鹉，能背诵因果知识却未真正理解应用。提示方法仍限于人工干预改进。本调查探索因果如何贯穿 LLM 生命周期各阶段——从令牌嵌入、基础模型训练至微调、对齐、推理、评估——铺就通往更可解释、可靠、因果感知模型的道路。同时，我们勾勒六大未来方向，推进 LLM 发展，强化因果推理，应对当前局限。

> Recent breakthroughs in artificial intelligence have driven a paradigm shift, where large language models (LLMs) with billions or trillions of parameters are trained on vast datasets, achieving unprecedented success across a series of language tasks. However, despite these successes, LLMs still rely on probabilistic modeling, which often captures spurious correlations rooted in linguistic patterns and social stereotypes, rather than the true causal relationships between entities and events. This limitation renders LLMs vulnerable to issues such as demographic biases, social stereotypes, and LLM hallucinations. These challenges highlight the urgent need to integrate causality into LLMs, moving beyond correlation-driven paradigms to build more reliable and ethically aligned AI systems.
  While many existing surveys and studies focus on utilizing prompt engineering to activate LLMs for causal knowledge or developing benchmarks to assess their causal reasoning abilities, most of these efforts rely on human intervention to activate pre-trained models. How to embed causality into the training process of LLMs and build more general and intelligent models remains unexplored. Recent research highlights that LLMs function as causal parrots, capable of reciting causal knowledge without truly understanding or applying it. These prompt-based methods are still limited to human interventional improvements. This survey aims to address this gap by exploring how causality can enhance LLMs at every stage of their lifecycle-from token embedding learning and foundation model training to fine-tuning, alignment, inference, and evaluation-paving the way for more interpretable, reliable, and causally-informed models. Additionally, we further outline six promising future directions to advance LLM development, enhance their causal reasoning capabilities, and address the current limitations these models face.

[Arxiv](https://arxiv.org/abs/2410.15319)