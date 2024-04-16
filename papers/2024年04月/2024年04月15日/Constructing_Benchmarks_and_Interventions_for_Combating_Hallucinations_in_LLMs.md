# 为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。

发布时间：2024年04月15日

`LLM理论` `问答系统` `语言模型`

> Constructing Benchmarks and Interventions for Combating Hallucinations in LLMs

# 摘要

> 大型语言模型（LLMs）易产生幻觉，引起了业界对其检测与防范的广泛关注。最新研究尝试在生成过程中对模型进行干预，以减轻幻觉现象，采用了多种配置和启发式策略。但这些研究未能明确区分幻觉的不同成因。本研究首先提出了一种基于模型知识构建数据集的方法，针对闭卷和开卷问答场景中的检测与干预手段。接着，我们分析了干预措施的不同选择（如MLPs、注意力模块、残差流和特定头）的影响，以及干预的频率和强度。研究发现，干预效果因组件而异，部分组件甚至可能削弱语言建模的能力。最终，我们发现在幻觉发生前进行引导，比幻觉出现后再干预更为有效。相关代码已在 https://github.com/technion-cs-nlp/hallucination-mitigation 上发布。

> Large language models (LLMs) are susceptible to hallucination, which sparked a widespread effort to detect and prevent them. Recent work attempts to mitigate hallucinations by intervening in the model's computation during generation, using different setups and heuristics. Those works lack separation between different hallucination causes. In this work, we first introduce an approach for constructing datasets based on the model knowledge for detection and intervention methods in closed-book and open-book question-answering settings. We then characterize the effect of different choices for intervention, such as the intervened components (MLPs, attention block, residual stream, and specific heads), and how often and how strongly to intervene. We find that intervention success varies depending on the component, with some components being detrimental to language modeling capabilities. Finally, we find that interventions can benefit from pre-hallucination steering direction instead of post-hallucination. The code is available at https://github.com/technion-cs-nlp/hallucination-mitigation

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x1.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x2.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x3.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x4.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x5.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x6.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x7.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x8.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x9.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x10.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x11.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x12.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x13.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x14.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x15.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x16.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x17.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x18.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x19.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x20.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x21.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x22.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x23.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x24.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x25.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x26.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x27.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x28.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x29.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x30.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x31.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x32.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x33.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x34.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x35.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x36.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x37.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x38.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x39.png)

![为了对抗大型语言模型中的幻觉现象，我们正在构建一系列基准测试和干预策略。](../../../paper_images/2404.09971/x40.png)

[Arxiv](https://arxiv.org/abs/2404.09971)