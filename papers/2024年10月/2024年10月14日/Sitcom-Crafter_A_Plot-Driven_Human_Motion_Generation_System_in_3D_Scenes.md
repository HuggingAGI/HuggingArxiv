# Sitcom-Crafter：一款以情节驱动的3D场景中人类动作生成系统

发布时间：2024年10月14日

`其他` `游戏设计`

> Sitcom-Crafter: A Plot-Driven Human Motion Generation System in 3D Scenes

# 摘要

> 近期，人类运动合成技术虽在特定领域如人-场景交互、运动及人-人互动上有所突破，但缺乏一个能融合多种运动类型的统一系统。为此，我们推出了Sitcom-Crafter，一个集全面性与扩展性于一体的3D空间人类运动生成系统。该系统通过丰富的情节背景引导，旨在提升动漫与游戏设计的工作效率。系统内含八大模块，其中三者专攻运动生成，余下五者则为增强模块，确保运动序列与系统功能的无缝融合。核心生成模块中，我们创新的3D场景感知人-人互动模块，通过合成隐式3D符号距离函数（SDF）点，有效解决了运动空间内的碰撞问题，且无需额外数据支持。此外，运动与人类-场景互动模块则借助现有技术，进一步强化了系统的运动生成能力。增强模块则涵盖了情节理解以生成指令、运动同步以整合不同类型运动、手部姿势检索以提升真实感、运动碰撞修正以防止人体碰撞，以及3D重定向以确保视觉上的逼真度。实验结果表明，该系统不仅能生成高质量、多样化的运动，还能在物理层面保持真实性，极大地推动了创意工作流程的发展。

> Recent advancements in human motion synthesis have focused on specific types of motions, such as human-scene interaction, locomotion or human-human interaction, however, there is a lack of a unified system capable of generating a diverse combination of motion types. In response, we introduce Sitcom-Crafter, a comprehensive and extendable system for human motion generation in 3D space, which can be guided by extensive plot contexts to enhance workflow efficiency for anime and game designers. The system is comprised of eight modules, three of which are dedicated to motion generation, while the remaining five are augmentation modules that ensure consistent fusion of motion sequences and system functionality. Central to the generation modules is our novel 3D scene-aware human-human interaction module, which addresses collision issues by synthesizing implicit 3D Signed Distance Function (SDF) points around motion spaces, thereby minimizing human-scene collisions without additional data collection costs. Complementing this, our locomotion and human-scene interaction modules leverage existing methods to enrich the system's motion generation capabilities. Augmentation modules encompass plot comprehension for command generation, motion synchronization for seamless integration of different motion types, hand pose retrieval to enhance motion realism, motion collision revision to prevent human collisions, and 3D retargeting to ensure visual fidelity. Experimental evaluations validate the system's ability to generate high-quality, diverse, and physically realistic motions, underscoring its potential for advancing creative workflows.

[Arxiv](https://arxiv.org/abs/2410.10790)