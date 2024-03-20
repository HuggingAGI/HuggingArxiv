# MELTing point：针对语言转换器在移动端性能评估的关键点探究

发布时间：2024年03月19日

`LLM应用` `机器学习` `移动设备`

> MELTing point: Mobile Evaluation of Language Transformers

> Transformer 技术已深度革新机器学习世界，让智能融入日常任务并为电脑注入智慧基因。然而，受限于运行资源需求，大型语言模型（LLM）在移动端的应用尚未普及。鉴于个人设备算力提升及即时隐私保护意识增强，我们深入探究了 LLM 在移动设备上的执行现状。为此，我们打造了一款名为 MELT 的自动化平台，它支持在各类设备（如 Android、iOS 及 Nvidia Jetson 等）上对 LLM 进行无头执行和基准测试，涵盖了多模型、多设备和多框架场景。我们评估了一系列热门指令微调的 LLM，并通过不同框架对其整体及细节性能进行度量，同时监测其内存和能耗状况。这是首次对移动设备上 LLM 执行进行系统性研究，通过对各前沿模型的性能、能效及准确性的量化分析，生动展现了超大规模模型时代设备智能的发展水平。研究揭示了目标设备间性能差异显著，且 LLMS 的推理过程深受内存制约。量化技术虽可大幅削减内存需求，使执行变为可行，却难免牺牲一定的精度。此外，LLM 持续执行仍面临挑战，因其能源消耗及散热问题均会对用户体验造成负面影响。目前来看，该领域的生态系统尚处萌芽阶段，算法与硬件层面的重大突破将有力改写执行成本格局。我们预测，NPU 加速技术和框架-硬件联合设计将成为实现高效独立执行的关键赌注，而面向边缘部署的卸载策略则作为备选路径。

> Transformers have revolutionized the machine learning landscape, gradually making their way into everyday tasks and equipping our computers with ``sparks of intelligence''. However, their runtime requirements have prevented them from being broadly deployed on mobile. As personal devices become increasingly powerful and prompt privacy becomes an ever more pressing issue, we explore the current state of mobile execution of Large Language Models (LLMs). To achieve this, we have created our own automation infrastructure, MELT, which supports the headless execution and benchmarking of LLMs on device, supporting different models, devices and frameworks, including Android, iOS and Nvidia Jetson devices. We evaluate popular instruction fine-tuned LLMs and leverage different frameworks to measure their end-to-end and granular performance, tracing their memory and energy requirements along the way.
  Our analysis is the first systematic study of on-device LLM execution, quantifying performance, energy efficiency and accuracy across various state-of-the-art models and showcases the state of on-device intelligence in the era of hyperscale models. Results highlight the performance heterogeneity across targets and corroborates that LLM inference is largely memory-bound. Quantization drastically reduces memory requirements and renders execution viable, but at a non-negligible accuracy cost. Drawing from its energy footprint and thermal behavior, the continuous execution of LLMs remains elusive, as both factors negatively affect user experience. Last, our experience shows that the ecosystem is still in its infancy, and algorithmic as well as hardware breakthroughs can significantly shift the execution cost. We expect NPU acceleration, and framework-hardware co-design to be the biggest bet towards efficient standalone execution, with the alternative of offloading tailored towards edge deployments.

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x1.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x2.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x3.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x4.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x5.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x6.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x7.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x8.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x9.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x10.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x11.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x12.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x13.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x14.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x15.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x16.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x17.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x18.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x19.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x20.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x21.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x22.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/iphone14pro_thermals_rotated.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x23.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x24.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x25.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x26.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x27.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x28.png)

![MELTing point：针对语言转换器在移动端性能评估的关键点探究](../../../paper_images/2403.12844/x29.png)

[Arxiv](https://arxiv.org/abs/2403.12844)