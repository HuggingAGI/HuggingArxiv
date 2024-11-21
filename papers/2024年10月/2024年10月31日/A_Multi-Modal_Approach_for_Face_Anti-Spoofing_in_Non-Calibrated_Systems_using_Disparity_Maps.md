# 一种利用视差图在未校准系统中实现人脸反欺骗的多模态手段

发布时间：2024年10月31日

`其他` `人脸识别` `反欺骗`

> A Multi-Modal Approach for Face Anti-Spoofing in Non-Calibrated Systems using Disparity Maps

# 摘要

> 人脸识别技术在各类应用中愈发常用，然而却易遭人脸欺骗攻击。这类攻击往往包含独特的 3D 结构，像打印纸或者移动设备屏幕。虽说立体深度相机能有效检测此类攻击，但其高昂成本限制了广泛运用。反之，无需外部校准的双传感器系统虽成本效益高，却无法借助立体技术计算深度。在此项工作中，我们提出一种方法，利用面部属性推导视差信息并估算相对深度以实现反欺骗，使用未校准系统来攻克这一难题。我们引入了一种多模态反欺骗模型，名为视差模型，它把创建的视差图作为第三种模态与两个原始传感器模态相结合。通过从英特尔 RealSense ID 解决方案 F455 采集的综合数据集，我们证明了视差模型应对各类欺骗攻击的有效性。我们的方法优于文献中的现有方法，在误报率为 1％时，达成了 1.71％的等错误率和 2.77％的假阴性率。这些错误分别比最佳对比方法的错误低 2.45％和 7.94％。另外，我们还引入了一个模型集合，它也能应对 3D 欺骗攻击，在误报率为 1％时，实现了 2.04％的等错误率和 3.83％的假阴性率。总之，我们的工作为缺乏深度信息的未校准系统中的反欺骗这一艰巨任务提供了前沿的解决方案。

> Face recognition technologies are increasingly used in various applications, yet they are vulnerable to face spoofing attacks. These spoofing attacks often involve unique 3D structures, such as printed papers or mobile device screens. Although stereo-depth cameras can detect such attacks effectively, their high-cost limits their widespread adoption. Conversely, two-sensor systems without extrinsic calibration offer a cost-effective alternative but are unable to calculate depth using stereo techniques. In this work, we propose a method to overcome this challenge by leveraging facial attributes to derive disparity information and estimate relative depth for anti-spoofing purposes, using non-calibrated systems. We introduce a multi-modal anti-spoofing model, coined Disparity Model, that incorporates created disparity maps as a third modality alongside the two original sensor modalities. We demonstrate the effectiveness of the Disparity Model in countering various spoof attacks using a comprehensive dataset collected from the Intel RealSense ID Solution F455. Our method outperformed existing methods in the literature, achieving an Equal Error Rate (EER) of 1.71% and a False Negative Rate (FNR) of 2.77% at a False Positive Rate (FPR) of 1%. These errors are lower by 2.45% and 7.94% than the errors of the best comparison method, respectively. Additionally, we introduce a model ensemble that addresses 3D spoof attacks as well, achieving an EER of 2.04% and an FNR of 3.83% at an FPR of 1%. Overall, our work provides a state-of-the-art solution for the challenging task of anti-spoofing in non-calibrated systems that lack depth information.

[Arxiv](https://arxiv.org/abs/2410.24031)