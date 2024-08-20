# FFAA：一款基于多模态大型语言模型的助手，专为开放世界中的人脸伪造分析提供可解释性支持。

发布时间：2024年08月19日

`LLM应用` `信息安全` `人工智能`

> FFAA: Multimodal Large Language Model based Explainable Open-World Face Forgery Analysis Assistant

# 摘要

> 深度伪造技术的迅猛进步引起了公众的广泛关注，尤其是面部伪造对公共信息安全构成的威胁。然而，未知且多样的伪造技术、多变的面部特征及复杂环境因素，为面部伪造分析带来了巨大挑战。现有数据集缺乏相关描述，使得模型在众多干扰因素下，仅凭视觉信息难以辨别真伪。此外，现有方法未能提供用户友好且可解释的结果，增加了理解模型决策的难度。为此，我们提出了开放世界面部伪造分析VQA（OW-FFA-VQA）任务及相应基准。我们首先构建了一个包含多样化真实与伪造面部图像的数据集，并附有详尽描述及可靠伪造推理。基于此，我们开发了FFAA：面部伪造分析助手，结合微调的多模态大型语言模型（MLLM）与多答案智能决策系统（MIDS）。通过整合假设性提示与MIDS，有效降低了模糊分类边界的影响，提升了模型鲁棒性。实验证明，我们的方法不仅提供了用户友好的可解释结果，还在准确性与鲁棒性上显著超越了以往方法。

> The rapid advancement of deepfake technologies has sparked widespread public concern, particularly as face forgery poses a serious threat to public information security. However, the unknown and diverse forgery techniques, varied facial features and complex environmental factors pose significant challenges for face forgery analysis. Existing datasets lack descriptions of these aspects, making it difficult for models to distinguish between real and forged faces using only visual information amid various confounding factors. In addition, existing methods do not yield user-friendly and explainable results, complicating the understanding of the model's decision-making process. To address these challenges, we introduce a novel Open-World Face Forgery Analysis VQA (OW-FFA-VQA) task and the corresponding benchmark. To tackle this task, we first establish a dataset featuring a diverse collection of real and forged face images with essential descriptions and reliable forgery reasoning. Base on this dataset, we introduce FFAA: Face Forgery Analysis Assistant, consisting of a fine-tuned Multimodal Large Language Model (MLLM) and Multi-answer Intelligent Decision System (MIDS). By integrating hypothetical prompts with MIDS, the impact of fuzzy classification boundaries is effectively mitigated, enhancing the model's robustness. Extensive experiments demonstrate that our method not only provides user-friendly explainable results but also significantly boosts accuracy and robustness compared to previous methods.

[Arxiv](https://arxiv.org/abs/2408.10072)