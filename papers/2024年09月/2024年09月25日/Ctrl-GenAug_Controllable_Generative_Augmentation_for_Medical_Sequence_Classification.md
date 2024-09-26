# Ctrl-GenAug：医学序列分类中的可控生成增强技术

发布时间：2024年09月25日

`LLM应用` `数据增强`

> Ctrl-GenAug: Controllable Generative Augmentation for Medical Sequence Classification

# 摘要

> 在医疗领域，数据稀缺和标注繁琐限制了深度模型的表现。基于扩散的生成增强方法虽有潜力，但现有技术在语义和顺序控制上不足，且忽视了合成样本的质量，导致下游任务表现受限。为此，我们推出了Ctrl-GenAug，一个创新的生成增强框架，能精准定制序列合成并过滤错误样本，助力医疗序列分类。通过多模态条件引导的生成器和顺序增强模块，我们确保了合成样本的高质量。实验证明，Ctrl-GenAug在多种医疗数据集和网络模型中表现出色，尤其在处理高风险和域外情况时更显优势。

> In the medical field, the limited availability of large-scale datasets and labor-intensive annotation processes hinder the performance of deep models. Diffusion-based generative augmentation approaches present a promising solution to this issue, having been proven effective in advancing downstream medical recognition tasks. Nevertheless, existing works lack sufficient semantic and sequential steerability for challenging video/3D sequence generation, and neglect quality control of noisy synthesized samples, resulting in unreliable synthetic databases and severely limiting the performance of downstream tasks. In this work, we present Ctrl-GenAug, a novel and general generative augmentation framework that enables highly semantic- and sequential-customized sequence synthesis and suppresses incorrectly synthesized samples, to aid medical sequence classification. Specifically, we first design a multimodal conditions-guided sequence generator for controllably synthesizing diagnosis-promotive samples. A sequential augmentation module is integrated to enhance the temporal/stereoscopic coherence of generated samples. Then, we propose a noisy synthetic data filter to suppress unreliable cases at semantic and sequential levels. Extensive experiments on 3 medical datasets, using 11 networks trained on 3 paradigms, comprehensively analyze the effectiveness and generality of Ctrl-GenAug, particularly in underrepresented high-risk populations and out-domain conditions.

[Arxiv](https://arxiv.org/abs/2409.17091)