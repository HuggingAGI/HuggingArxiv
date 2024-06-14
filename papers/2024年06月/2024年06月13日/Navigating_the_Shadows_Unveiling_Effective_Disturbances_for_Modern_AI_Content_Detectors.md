# 揭秘阴影中的导航：探索现代AI内容检测器的有效干扰策略

发布时间：2024年06月13日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在文本生成领域的应用，特别是在AI文本检测技术方面的问题和挑战。论文通过模拟真实场景，评估了现有检测器的性能，并设计了多种文本扰动方法来测试检测器的鲁棒性。这些内容直接关联到LLMs的实际应用，特别是在检测和区分人机内容方面的应用，因此属于LLM应用分类。` `知识产权` `学术诚信`

> Navigating the Shadows: Unveiling Effective Disturbances for Modern AI Content Detectors

# 摘要

> ChatGPT的问世让大型语言模型（LLMs）成为全球焦点，尤其在文章写作领域，其广泛应用引发了知识产权、隐私和学术诚信的担忧。为此，AI文本检测技术应运而生，旨在区分人机内容。但最新研究显示，这些检测系统在面对扰动文本时显得力不从心。目前，对于这些检测系统在现实世界中的表现缺乏系统评估，对扰动技术和检测器鲁棒性的全面分析也尚未出现。为了弥补这一缺失，我们模拟了非正式与专业写作的真实场景，测试了现有检测器的即用性能，并设计了12种黑盒文本扰动方法，以检验检测器在不同扰动粒度下的稳健性。通过对抗性学习实验，我们还探讨了扰动数据增强对AI文本检测器鲁棒性的影响，并将相关代码和数据公开于https://github.com/zhouying20/ai-text-detector-evaluation。

> With the launch of ChatGPT, large language models (LLMs) have attracted global attention. In the realm of article writing, LLMs have witnessed extensive utilization, giving rise to concerns related to intellectual property protection, personal privacy, and academic integrity. In response, AI-text detection has emerged to distinguish between human and machine-generated content. However, recent research indicates that these detection systems often lack robustness and struggle to effectively differentiate perturbed texts. Currently, there is a lack of systematic evaluations regarding detection performance in real-world applications, and a comprehensive examination of perturbation techniques and detector robustness is also absent. To bridge this gap, our work simulates real-world scenarios in both informal and professional writing, exploring the out-of-the-box performance of current detectors. Additionally, we have constructed 12 black-box text perturbation methods to assess the robustness of current detection models across various perturbation granularities. Furthermore, through adversarial learning experiments, we investigate the impact of perturbation data augmentation on the robustness of AI-text detectors. We have released our code and data at https://github.com/zhouying20/ai-text-detector-evaluation.

![揭秘阴影中的导航：探索现代AI内容检测器的有效干扰策略](../../../paper_images/2406.08922/x1.png)

![揭秘阴影中的导航：探索现代AI内容检测器的有效干扰策略](../../../paper_images/2406.08922/x2.png)

[Arxiv](https://arxiv.org/abs/2406.08922)