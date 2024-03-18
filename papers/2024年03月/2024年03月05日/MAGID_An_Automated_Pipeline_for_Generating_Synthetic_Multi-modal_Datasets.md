# MAGID 是一款自动化的流水线工具，专注于创建合成型多模态数据集。

发布时间：2024年03月05日

`Agent`

> MAGID: An Automated Pipeline for Generating Synthetic Multi-modal Datasets

> 面对大型语言模型对丰富多模态对话数据的巨大需求，当前受限的数据资源制约了多模态交互系统的发展。之前的研究尝试通过检索图片补充文本对话，但往往会引发隐私、多样性及质量问题。为此，我们提出了新颖的\textbf{MAGID}框架——一种能为纯文本对话增添多样且高质量图像的多模态增强生成对话系统。该系统首先运用扩散模型生成与文本内容精准匹配的对应图像，并创造性地构建了一个包含图像描述生成模块（基于LLM）与图像质量控制模块（关注美学、图文匹配度及安全）之间的互动反馈循环，共同确保高质量、多模态对话的产出。在对MAGID与其它SOTA基准方法进行自动化及人工评估的对比实验中，我们选取了三个对话数据集作为测试平台。实验结果显示，MAGID在各项指标上均表现出与基准相当或更优的性能，尤其在针对小型图像数据库的检索式基准方法的人工评估中，优势更为明显。

> Development of multimodal interactive systems is hindered by the lack of rich, multimodal (text, images) conversational data, which is needed in large quantities for LLMs. Previous approaches augment textual dialogues with retrieved images, posing privacy, diversity, and quality constraints. In this work, we introduce \textbf{M}ultimodal \textbf{A}ugmented \textbf{G}enerative \textbf{I}mages \textbf{D}ialogues (MAGID), a framework to augment text-only dialogues with diverse and high-quality images. Subsequently, a diffusion model is applied to craft corresponding images, ensuring alignment with the identified text. Finally, MAGID incorporates an innovative feedback loop between an image description generation module (textual LLM) and image quality modules (addressing aesthetics, image-text matching, and safety), that work in tandem to generate high-quality and multi-modal dialogues. We compare MAGID to other SOTA baselines on three dialogue datasets, using automated and human evaluation. Our results show that MAGID is comparable to or better than baselines, with significant improvements in human evaluation, especially against retrieval baselines where the image database is small.

[Arxiv](https://arxiv.org/abs/2403.03194)