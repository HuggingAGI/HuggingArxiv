# [SNIFFER是一款专注于可解释性离群信息检测的多模态大型语言模型，能够有效识别和解析上下文缺失情况下的错误信息。](https://arxiv.org/abs/2403.03170)

发布时间：2024年03月05日

`LLM应用`

> SNIFFER: Multimodal Large Language Model for Explainable Out-of-Context Misinformation Detection

> 错误信息因高风险而成为普遍的社会问题，其中，将真实图片与虚构文本搭配使用的“脱离语境”手法尤为便捷且高效。现有技术虽重视图像与文本是否相符，却难以给出令人信服的判断依据以揭露错误信息。多模态大型语言模型（MLLMs）虽然蕴含丰富知识并具备视觉推理和自动生成解释的能力，但在捕捉和理解细微的跨模态差异时仍有欠缺。为此，我们创新研发了名为SNIFFER的新型多模态大模型，专门针对脱离语境错误信息检测与解释。SNIFFER借助两阶段指令调优，在InstructBLIP平台上精炼模型对通用物体与新闻实体概念的对应关系，并进一步运用由GPT-4生成的针对OOC场景的独特指令数据优化模型识别力。经由外接工具和检索技术强化后，SNIFFER不仅能够探测图文间的矛盾之处，还能借由外部知识进行情境核实。实验结果显示，SNIFFER相较于原始MLLM性能提升超过40%，在检测精准度上更是超越目前最先进的方法。此外，SNIFFER所提供的解释经过量化评估和人工验证，不仅精确，而且极具说服力。

> Misinformation is a prevalent societal issue due to its potential high risks. Out-of-context (OOC) misinformation, where authentic images are repurposed with false text, is one of the easiest and most effective ways to mislead audiences. Current methods focus on assessing image-text consistency but lack convincing explanations for their judgments, which is essential for debunking misinformation. While Multimodal Large Language Models (MLLMs) have rich knowledge and innate capability for visual reasoning and explanation generation, they still lack sophistication in understanding and discovering the subtle crossmodal differences. In this paper, we introduce SNIFFER, a novel multimodal large language model specifically engineered for OOC misinformation detection and explanation. SNIFFER employs two-stage instruction tuning on InstructBLIP. The first stage refines the model's concept alignment of generic objects with news-domain entities and the second stage leverages language-only GPT-4 generated OOC-specific instruction data to fine-tune the model's discriminatory powers. Enhanced by external tools and retrieval, SNIFFER not only detects inconsistencies between text and image but also utilizes external knowledge for contextual verification. Our experiments show that SNIFFER surpasses the original MLLM by over 40% and outperforms state-of-the-art methods in detection accuracy. SNIFFER also provides accurate and persuasive explanations as validated by quantitative and human evaluations.

[Arxiv](https://arxiv.org/abs/2403.03170)