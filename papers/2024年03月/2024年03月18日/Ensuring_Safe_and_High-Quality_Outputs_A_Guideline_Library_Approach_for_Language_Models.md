# 为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。

发布时间：2024年03月18日

`LLM应用` `人工智能安全`

> Ensuring Safe and High-Quality Outputs: A Guideline Library Approach for Language Models

> LLMs虽然强大但也有生成偏见内容、涉及隐私问题等风险。目前，一种应对策略是采用基于原则的集成方法，然而由于手工编写规则的模糊性以及未经安全训练模型对风险感知的局限性，这种方法遇到了难题。为此，我们提出了“Guide-Align”两步走方案。第一步，借助于一个专门针对安全训练的模型来识别潜在风险并针对各类输入制定具体指南，构建起一套详尽的指南库及输入-指南检索系统。第二步，运用检索模型将新的输入与相应指南匹配，引导LLMs在生成回应时保证安全性与高品质，更好地契合人类价值观念。此外，还有一个额外的优化阶段，即使用第二阶段生成的新对齐数据集对模型进行精细化微调。此方法能灵活地为不同输入定制指南，极大地丰富和完善了指南库的精细度和覆盖范围，并巧妙地借助轻量级检索模型吸收了安全训练LLM的专业安全知识。我们在三项基准测试中验证了该方法的有效性，大大提升了LLM的安全性和品质表现。尤为突出的是，即使参数高达130亿的Labrador模型，在对齐性能上不仅超越了GPT-3.5-turbo，甚至还优于GPT-4。

> Large Language Models (LLMs) exhibit impressive capabilities but also present risks such as biased content generation and privacy issues. One of the current alignment techniques includes principle-driven integration, but it faces challenges arising from the imprecision of manually crafted rules and inadequate risk perception in models without safety training. To address these, we introduce Guide-Align, a two-stage approach. Initially, a safety-trained model identifies potential risks and formulates specific guidelines for various inputs, thereby establishing a comprehensive library of guidelines and models for input-guidelines retrieval. Subsequently, the retrieval model correlates new inputs with pertinent guidelines, guiding LLMs in response generation to ensure safe and high-quality outputs, thus aligning with human values. An additional optional stage involves fine-tuning a model with new well-aligned datasets generated through the process implemented in the second stage. Our method customizes guidelines to accommodate diverse inputs, thereby enhancing the fine-grainedness and comprehensiveness of the guideline library. Furthermore, it incorporates safety expertise from a safety-trained LLM through a lightweight retrieval model. We evaluated our approach on three benchmarks, demonstrating significant improvements in LLM security and quality. Notably, our fine-tuned model, Labrador, even at 13 billion parameters, outperforms GPT-3.5-turbo and surpasses GPT-4 in alignment capabilities.

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x1.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x2.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x3.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x4.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x5.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x6.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x7.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x8.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x9.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x10.png)

![为确保语言模型产出既安全又高质量，我们提出一种基于指南库的方法。通过构建一套详尽的指南库策略，本研究致力于引导和规范语言模型的输出行为。](../../../paper_images/2403.11838/x11.png)

[Arxiv](https://arxiv.org/abs/2403.11838)