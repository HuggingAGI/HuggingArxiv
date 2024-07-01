# 提升放射诊断：融合AI与专家智慧，共同修正视觉遗漏，实现诊断协作新高度。

发布时间：2024年06月28日

`Agent` `放射学`

> Enhancing Radiological Diagnosis: A Collaborative Approach Integrating AI and Human Expertise for Visual Miss Correction

# 摘要

> 本研究首次探索了人类与AI在识别和纠正胸部X光片感知错误方面的协作。我们开发的CoRaX系统，通过融合眼动数据和放射报告，精准定位并优化诊断决策，显著提升了胸部放射学的诊断准确性。在公开数据集上，CoRaX展现了其高效性，成功纠正了模拟数据集中21%的遗漏异常，且在与放射科医生的互动中，84%的诊断准确性得分超过0.40。CoRaX不仅优化了转诊流程，更在教育和培训新手放射科医生方面展现出巨大潜力。

> Human-AI collaboration to identify and correct perceptual errors in chest radiographs has not been previously explored. This study aimed to develop a collaborative AI system, CoRaX, which integrates eye gaze data and radiology reports to enhance diagnostic accuracy in chest radiology by pinpointing perceptual errors and refining the decision-making process. Using public datasets REFLACX and EGD-CXR, the study retrospectively developed CoRaX, employing a large multimodal model to analyze image embeddings, eye gaze data, and radiology reports. The system's effectiveness was evaluated based on its referral-making process, the quality of referrals, and performance in collaborative diagnostic settings. CoRaX was tested on a simulated error dataset of 271 samples with 28% (93 of 332) missed abnormalities. The system corrected 21% (71 of 332) of these errors, leaving 7% (22 of 312) unresolved. The Referral-Usefulness score, indicating the accuracy of predicted regions for all true referrals, was 0.63 (95% CI 0.59, 0.68). The Total-Usefulness score, reflecting the diagnostic accuracy of CoRaX's interactions with radiologists, showed that 84% (237 of 280) of these interactions had a score above 0.40. In conclusion, CoRaX efficiently collaborates with radiologists to address perceptual errors across various abnormalities, with potential applications in the education and training of novice radiologists.

[Arxiv](https://arxiv.org/abs/2406.19686)