# FakeShield：利用多模态大型语言模型，实现图像伪造的可解释检测与精准定位

发布时间：2024年10月03日

`LLM应用`

> FakeShield: Explainable Image Forgery Detection and Localization via Multi-modal Large Language Models

# 摘要

> 生成式AI的迅猛发展既助力了内容创作，也使得图像篡改变得更加隐秘。现有的图像伪造检测方法虽有效，但常面临两大难题：一是检测原理的黑箱性质，二是对多样篡改手段（如Photoshop、DeepFake、AIGC-Editing）的泛化能力不足。为此，我们推出了可解释的IFDL任务，并设计了FakeShield多模态框架，它不仅能评估图像真伪、生成篡改区域掩码，还能基于像素与图像级线索提供判断依据。我们还借助GPT-4o强化了IFDL数据集，打造了多模态篡改描述数据集（MMTD-Set），以提升FakeShield的篡改分析能力。此外，我们引入了领域标签引导的可解释伪造检测模块（DTE-FDM）与多模态伪造定位模块（MFLM），以应对各类篡改检测的解释需求，并实现由文本描述引导的伪造定位。实验证明，FakeShield在检测与定位篡改技术方面表现出色，为IFDL领域带来了可解释且更优的解决方案。

> The rapid development of generative AI is a double-edged sword, which not only facilitates content creation but also makes image manipulation easier and more difficult to detect. Although current image forgery detection and localization (IFDL) methods are generally effective, they tend to face two challenges: \textbf{1)} black-box nature with unknown detection principle, \textbf{2)} limited generalization across diverse tampering methods (e.g., Photoshop, DeepFake, AIGC-Editing). To address these issues, we propose the explainable IFDL task and design FakeShield, a multi-modal framework capable of evaluating image authenticity, generating tampered region masks, and providing a judgment basis based on pixel-level and image-level tampering clues. Additionally, we leverage GPT-4o to enhance existing IFDL datasets, creating the Multi-Modal Tamper Description dataSet (MMTD-Set) for training FakeShield's tampering analysis capabilities. Meanwhile, we incorporate a Domain Tag-guided Explainable Forgery Detection Module (DTE-FDM) and a Multi-modal Forgery Localization Module (MFLM) to address various types of tamper detection interpretation and achieve forgery localization guided by detailed textual descriptions. Extensive experiments demonstrate that FakeShield effectively detects and localizes various tampering techniques, offering an explainable and superior solution compared to previous IFDL methods.

[Arxiv](https://arxiv.org/abs/2410.02761)