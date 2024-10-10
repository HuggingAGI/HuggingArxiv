# 《致爱丽丝》：捕捉并物理合成钢琴演奏中的手部动作

发布时间：2024年10月08日

`LLM应用` `虚拟现实`

> FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance

# 摘要

> 钢琴演奏对手部控制的敏捷性、精确性和协调性提出了极高要求。能够准确再现这一过程的手部运动模型在角色动画、具身AI、生物力学及VR/AR等领域有着广泛应用。本文中，我们创建了一个前所未有的庞大数据集，收录了15位顶尖钢琴家演奏153首古典音乐的约10小时3D手部运动与音频资料。为捕捉演奏的自然状态，我们采用了无标记的多视角视频重建技术，并结合最先进的姿态估算模型。此外，通过逆运动学处理，我们利用高精度MIDI按键数据对运动轨迹进行了精细调整。基于此数据集，我们构建了一套系统，能生成与乐谱相符的逼真手部动作，即使面对训练集之外的音乐作品亦能应对自如。该系统融合了模仿学习与强化学习，旨在优化双手与琴键互动的物理控制策略。针对大规模数据集带来的采样难题，我们引入了扩散模型，以生成富含高级轨迹与指法信息的自然参考动作。然而，仅凭这些生成的动作尚不足以满足钢琴演奏的高精度需求。为此，我们进一步借助音乐相似性，从原始数据集中筛选出相近动作，从而提升强化学习策略的精准度。最终，我们的模型成功实现了对训练集外音乐的自然且灵巧的手部动作生成。

> Piano playing requires agile, precise, and coordinated hand control that stretches the limits of dexterity. Hand motion models with the sophistication to accurately recreate piano playing have a wide range of applications in character animation, embodied AI, biomechanics, and VR/AR. In this paper, we construct a first-of-its-kind large-scale dataset that contains approximately 10 hours of 3D hand motion and audio from 15 elite-level pianists playing 153 pieces of classical music. To capture natural performances, we designed a markerless setup in which motions are reconstructed from multi-view videos using state-of-the-art pose estimation models. The motion data is further refined via inverse kinematics using the high-resolution MIDI key-pressing data obtained from sensors in a specialized Yamaha Disklavier piano. Leveraging the collected dataset, we developed a pipeline that can synthesize physically-plausible hand motions for musical scores outside of the dataset. Our approach employs a combination of imitation learning and reinforcement learning to obtain policies for physics-based bimanual control involving the interaction between hands and piano keys. To solve the sampling efficiency problem with the large motion dataset, we use a diffusion model to generate natural reference motions, which provide high-level trajectory and fingering (finger order and placement) information. However, the generated reference motion alone does not provide sufficient accuracy for piano performance modeling. We then further augmented the data by using musical similarity to retrieve similar motions from the captured dataset to boost the precision of the RL policy. With the proposed method, our model generates natural, dexterous motions that generalize to music from outside the training dataset.

[Arxiv](https://arxiv.org/abs/2410.05791)