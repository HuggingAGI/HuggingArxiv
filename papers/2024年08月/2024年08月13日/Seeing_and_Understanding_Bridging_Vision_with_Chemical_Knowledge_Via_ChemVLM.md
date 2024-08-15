# 借助 ChemVLM，我们实现了视觉与化学知识的桥梁，让看见转化为理解。

发布时间：2024年08月13日

`LLM应用` `人工智能`

> Seeing and Understanding: Bridging Vision with Chemical Knowledge Via ChemVLM

# 摘要

> 本报告中，我们推出了 ChemVLM，这是首个专为化学领域量身打造的开源多模态大型语言模型，旨在弥合化学图像理解与文本分析之间的鸿沟。依托 VIT-MLP-LLM 架构，我们以 ChemLLM-20B 为基础模型，赋予 ChemVLM 深厚的化学文本知识处理能力。同时，结合 InternVIT-6B 图像编码器，我们精心筛选了涵盖分子、反应公式及化学考试数据的高质量化学领域数据，构建了一个双语多模态问答数据集。通过在多个开源基准及三个定制评估集上的测试，实验结果显示，ChemVLM 在六个任务中五项表现卓越，达到了业界领先水平。该模型资源已公开，可访问 https://huggingface.co/AI4Chem/ChemVLM-26B 获取。

> In this technical report, we propose ChemVLM, the first open-source multimodal large language model dedicated to the fields of chemistry, designed to address the incompatibility between chemical image understanding and text analysis. Built upon the VIT-MLP-LLM architecture, we leverage ChemLLM-20B as the foundational large model, endowing our model with robust capabilities in understanding and utilizing chemical text knowledge. Additionally, we employ InternVIT-6B as a powerful image encoder. We have curated high-quality data from the chemical domain, including molecules, reaction formulas, and chemistry examination data, and compiled these into a bilingual multimodal question-answering dataset. We test the performance of our model on multiple open-source benchmarks and three custom evaluation sets. Experimental results demonstrate that our model achieves excellent performance, securing state-of-the-art results in five out of six involved tasks. Our model can be found at https://huggingface.co/AI4Chem/ChemVLM-26B.

[Arxiv](https://arxiv.org/abs/2408.07246)