# [ImgTrojan：仅凭一张图像即可实现对视觉-语言模型的“越狱”攻击](https://arxiv.org/abs/2403.02910)

发布时间：2024年03月05日

`Agent`

> ImgTrojan: Jailbreaking Vision-Language Models with ONE Image

> 随着 LLMS 与人类价值取向的对齐逐渐成为焦点，VLMs 结合使用时的安全隐患却鲜有深入探讨。本论文创新性地提出了针对 VLMs 的“越狱”攻击方案，该方案在接收到用户输入有害指令时，能够突破其安全防线。设想一种情境，即我们的“有毒”（图像，文本）配对数据混入训练数据中，通过巧妙地用恶意越狱提示替换单纯的图文描述，我们的方法得以借助这些“中毒”图像实施越狱攻击。并且，我们进一步研究了毒素比例及可训练参数位置对攻击成功率的影响。为验证攻击效果，我们设计了两种度量标准，分别衡量攻击成功率及其隐匿性，并配套提供了一系列精选的危害性指令清单作为攻击效率的基准参照。通过对基准方法的对比实验，有力证明了我们所提攻击方法的有效性。

> There has been an increasing interest in the alignment of large language models (LLMs) with human values. However, the safety issues of their integration with a vision module, or vision language models (VLMs), remain relatively underexplored. In this paper, we propose a novel jailbreaking attack against VLMs, aiming to bypass their safety barrier when a user inputs harmful instructions. A scenario where our poisoned (image, text) data pairs are included in the training data is assumed. By replacing the original textual captions with malicious jailbreak prompts, our method can perform jailbreak attacks with the poisoned images. Moreover, we analyze the effect of poison ratios and positions of trainable parameters on our attack's success rate. For evaluation, we design two metrics to quantify the success rate and the stealthiness of our attack. Together with a list of curated harmful instructions, a benchmark for measuring attack efficacy is provided. We demonstrate the efficacy of our attack by comparing it with baseline methods.

[Arxiv](https://arxiv.org/abs/2403.02910)