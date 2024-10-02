# VLMGuard：利用未标记数据保护 VLMs 免受恶意提示的攻击

发布时间：2024年09月30日

`LLM应用` `人工智能` `网络安全`

> VLMGuard: Defending VLMs against Malicious Prompts via Unlabeled Data

# 摘要

> 视觉-语言模型（VLMs）在理解和处理视觉与文本信息方面至关重要，但其对恶意输入的脆弱性却带来了重大风险，影响了输出质量，并引发了对其应用可靠性的担忧。因此，检测这些恶意提示对于确保 VLM 生成的可信度至关重要。然而，开发有效的提示分类器面临的一大难题是缺乏大量标记的良性与恶意数据。为此，我们推出了 VLMGuard，一个利用未标记用户提示进行恶意检测的创新框架。这些未标记提示在 VLMs 开放使用时自然产生，包含了良性和恶意信息。我们通过自动恶意估计分数来区分这些未标记数据中的良性和恶意样本，从而训练出一个高效的二元提示分类器。值得一提的是，VLMGuard 无需额外的人工注释，极大地提升了其实际应用的灵活性和实用性。实验结果显示，VLMGuard 在检测效果上显著超越了现有最先进的方法。请注意，本文可能包含一些冒犯性示例，读者需自行判断。

> Vision-language models (VLMs) are essential for contextual understanding of both visual and textual information. However, their vulnerability to adversarially manipulated inputs presents significant risks, leading to compromised outputs and raising concerns about the reliability in VLM-integrated applications. Detecting these malicious prompts is thus crucial for maintaining trust in VLM generations. A major challenge in developing a safeguarding prompt classifier is the lack of a large amount of labeled benign and malicious data. To address the issue, we introduce VLMGuard, a novel learning framework that leverages the unlabeled user prompts in the wild for malicious prompt detection. These unlabeled prompts, which naturally arise when VLMs are deployed in the open world, consist of both benign and malicious information. To harness the unlabeled data, we present an automated maliciousness estimation score for distinguishing between benign and malicious samples within this unlabeled mixture, thereby enabling the training of a binary prompt classifier on top. Notably, our framework does not require extra human annotations, offering strong flexibility and practicality for real-world applications. Extensive experiment shows VLMGuard achieves superior detection results, significantly outperforming state-of-the-art methods. Disclaimer: This paper may contain offensive examples; reader discretion is advised.

[Arxiv](https://arxiv.org/abs/2410.00296)