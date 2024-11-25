# SocialGPT：借助贪婪分段优化为大型语言模型提供提示，以实现社会关系推理

发布时间：2024年10月28日

`LLM应用` `社会关系` `图像识别`

> SocialGPT: Prompting LLMs for Social Relation Reasoning via Greedy Segment Optimization

# 摘要

> 社会关系推理旨在从图像中辨别像朋友、配偶、同事之类的关系类别。当下的方法采用借助有标注的图像数据端到端训练专用网络的模式，然而在通用性和可解释性上存在局限。为应对这些问题，我们率先提出一个名为{
ame}的简单却精心打造的框架，它在模块化框架内融合了视觉基础模型（VFMs）的感知能力与大型语言模型（LLMs）的推理能力，为社会关系识别筑牢了坚实基础。具体而言，我们让VFMs把图像内容转化为文本形式的社会故事，接着借助LLMs进行基于文本的推理。{
ame}引入了系统的设计原则，分别适配VFMs和LLMs，并填补它们之间的鸿沟。无需额外的模型训练，它在两个数据库上斩获了颇具竞争力的零样本结果，同时给出了可解释的答案，因为LLMs能够为决策生成基于语言的阐释。在推理阶段为LLMs进行手动提示设计的过程颇为繁琐，故而需要一种自动提示优化方法。由于我们实质上是把视觉分类任务转变为LLMs的生成任务，自动提示优化遭遇了独特的长提示优化难题。为解决此难题，我们进一步提出了贪婪段提示优化（GSPO），它通过在段层级利用梯度信息展开贪婪搜索。实验结果显示，GSPO大幅提升了性能，我们的方法也适用于不同的图像风格。代码可在https://github.com/Mengzibin/SocialGPT获取。

> Social relation reasoning aims to identify relation categories such as friends, spouses, and colleagues from images. While current methods adopt the paradigm of training a dedicated network end-to-end using labeled image data, they are limited in terms of generalizability and interpretability. To address these issues, we first present a simple yet well-crafted framework named {\name}, which combines the perception capability of Vision Foundation Models (VFMs) and the reasoning capability of Large Language Models (LLMs) within a modular framework, providing a strong baseline for social relation recognition. Specifically, we instruct VFMs to translate image content into a textual social story, and then utilize LLMs for text-based reasoning. {\name} introduces systematic design principles to adapt VFMs and LLMs separately and bridge their gaps. Without additional model training, it achieves competitive zero-shot results on two databases while offering interpretable answers, as LLMs can generate language-based explanations for the decisions. The manual prompt design process for LLMs at the reasoning phase is tedious and an automated prompt optimization method is desired. As we essentially convert a visual classification task into a generative task of LLMs, automatic prompt optimization encounters a unique long prompt optimization issue. To address this issue, we further propose the Greedy Segment Prompt Optimization (GSPO), which performs a greedy search by utilizing gradient information at the segment level. Experimental results show that GSPO significantly improves performance, and our method also generalizes to different image styles. The code is available at https://github.com/Mengzibin/SocialGPT.

[Arxiv](https://arxiv.org/abs/2410.21411)