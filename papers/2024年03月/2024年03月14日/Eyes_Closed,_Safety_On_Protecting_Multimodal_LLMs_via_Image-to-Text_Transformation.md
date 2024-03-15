# [在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](https://arxiv.org/abs/2403.09572)

发布时间：2024年03月14日

`LLM应用`

`人工智能安全`

`多模态模型`

> Eyes Closed, Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation

> MLLMs虽拥有卓越的推理技能，却比传统的LLMs更容易受到越狱攻击。尽管仍能识别出不安全的回复，但在融合了图像特征后，预对齐LLMs在MLLMs内的安全机制变得易于规避。为此，我们创新性地提出了ECSO方案，一种无需训练即可提升模型安全性的保护策略。ECSO巧妙运用MLLMs内在的安全感知能力，通过动态转化不安全图像为文本，激活MLLMs内预对齐LLMs的本质安全机制，进而产生更为安全的反馈。实验证明，ECSO在五个尖端MLLM模型上的应用效果显著，如使MM-SafetyBench（SD+OCR）的安全性提高了37.6%，在VLSafe针对LLaVA-1.5-7B模型上更是提升了71.3%，并且始终维持了在常规MLLM基准测试中的实用性表现。不仅如此，ECSO还能作为一个数据驱动引擎，无需人工介入，自行生成用于MLLM对齐的监督微调数据。

> Multimodal large language models (MLLMs) have shown impressive reasoning abilities, which, however, are also more vulnerable to jailbreak attacks than their LLM predecessors. Although still capable of detecting unsafe responses, we observe that safety mechanisms of the pre-aligned LLMs in MLLMs can be easily bypassed due to the introduction of image features. To construct robust MLLMs, we propose ECSO(Eyes Closed, Safety On), a novel training-free protecting approach that exploits the inherent safety awareness of MLLMs, and generates safer responses via adaptively transforming unsafe images into texts to activate intrinsic safety mechanism of pre-aligned LLMs in MLLMs. Experiments on five state-of-the-art (SoTA) MLLMs demonstrate that our ECSO enhances model safety significantly (e.g., a 37.6% improvement on the MM-SafetyBench (SD+OCR), and 71.3% on VLSafe for the LLaVA-1.5-7B), while consistently maintaining utility results on common MLLM benchmarks. Furthermore, we show that ECSO can be used as a data engine to generate supervised-finetuning (SFT) data for MLLM alignment without extra human intervention.

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x1.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x2.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x3.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x4.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x5.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x6.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x7.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x8.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x9.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x10.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x11.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x13.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x14.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x15.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x16.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x17.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x18.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x19.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x20.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x21.png)

![在“闭眼”状态下保障安全：探索利用图像转文本技术来保护多模态大型语言模型（LLMs）的方案](../../../paper_images/2403.09572/x22.png)