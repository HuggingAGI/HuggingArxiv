# 探索更稳健的检索增强语言模型：揭秘不完美检索的深远影响

发布时间：2024年10月19日

`RAG` `人工智能`

> Toward Robust RALMs: Revealing the Impact of Imperfect Retrieval on Retrieval-Augmented Language Models

# 摘要

> 检索增强语言模型 (RALM) 因其高效生成准确答案的能力而备受瞩目。然而，由于依赖不完美的检索器或知识源，RALM 容易受到信息不完美的影响。我们发现了三种常见场景——无法回答、对抗性和冲突性——在这些场景中，检索到的文档集可能误导 RALM。我们首次全面评估了 RALM 在这些复杂场景中的表现。为系统评估其对抗性鲁棒性，我们提出了基于生成模型的对抗性攻击 (GenADV) 和新的鲁棒性度量 (RAD)。研究发现，RALM 常无法识别文档集的不可答性或矛盾性，导致幻觉。此外，对抗性因素的加入显著削弱了 RALM 的性能，特别是在对抗性与不可答性重叠时，模型更加脆弱。我们的研究为提升 RALM 的鲁棒性指明了方向，为构建更强大的模型奠定了基础。

> Retrieval Augmented Language Models (RALMs) have gained significant attention for their ability to generate accurate answer and improve efficiency. However, RALMs are inherently vulnerable to imperfect information due to their reliance on the imperfect retriever or knowledge source. We identify three common scenarios-unanswerable, adversarial, conflicting-where retrieved document sets can confuse RALM with plausible real-world examples. We present the first comprehensive investigation to assess how well RALMs detect and handle such problematic scenarios. Among these scenarios, to systematically examine adversarial robustness we propose a new adversarial attack method, Generative model-based ADVersarial attack (GenADV) and a novel metric Robustness under Additional Document (RAD). Our findings reveal that RALMs often fail to identify the unanswerability or contradiction of a document set, which frequently leads to hallucinations. Moreover, we show the addition of an adversary significantly degrades RALM's performance, with the model becoming even more vulnerable when the two scenarios overlap (adversarial+unanswerable). Our research identifies critical areas for assessing and enhancing the robustness of RALMs, laying the foundation for the development of more robust models.

[Arxiv](https://arxiv.org/abs/2410.15107)