# E-code：借助预训练模型与专家编码器组，精通高效代码生成之道。

发布时间：2024年08月23日

`LLM应用` `软件开发` `人工智能`

> E-code: Mastering Efficient Code Generation through Pretrained Models and Expert Encoder Group

# 摘要

> 随着摩尔定律的影响减弱，软件行业正寻求替代方案以持续提升性能。近年来，软件性能优化的重要性日益凸显，特别是在大型语言模型的推动下。然而，传统性能修正策略在代码效率优化领域显得力不从心，相关研究也颇为匮乏。本研究旨在填补这一空白，提供切实可行的解决方案。我们突破传统限制，开发了专为代码效率优化设计的语言模型E-code。借鉴专家模型的成功经验，我们创新性地设计了专家编码器组，通过多个编码器针对不同输入类型提取特征。在竞争性数据集上的测试显示，E-code在代码效率上提升了54.98%，远超同类模型。消融实验进一步证实了专家编码器组及其他组件的关键作用。研究结果表明，专家编码器组能有效应对效率优化任务中的多样化输入，大幅提升模型性能。

> Context: With the waning of Moore's Law, the software industry is placing increasing importance on finding alternative solutions for continuous performance enhancement. The significance and research results of software performance optimization have been on the rise in recent years, especially with the advancement propelled by Large Language Models(LLMs). However, traditional strategies for rectifying performance flaws have shown significant limitations at the competitive code efficiency optimization level, and research on this topic is surprisingly scarce. Objective: This study aims to address the research gap in this domain, offering practical solutions to the various challenges encountered. Specifically, we have overcome the constraints of traditional performance error rectification strategies and developed a Language Model (LM) tailored for the competitive code efficiency optimization realm. Method: We introduced E-code, an advanced program synthesis LM. Inspired by the recent success of expert LMs, we designed an innovative structure called the Expert Encoder Group. This structure employs multiple expert encoders to extract features tailored for different input types. We assessed the performance of E-code against other leading models on a competitive dataset and conducted in-depth ablation experiments. Results: Upon systematic evaluation, E-code achieved a 54.98% improvement in code efficiency, significantly outperforming other advanced models. In the ablation experiments, we further validated the significance of the expert encoder group and other components within E-code. Conclusion: The research findings indicate that the expert encoder group can effectively handle various inputs in efficiency optimization tasks, significantly enhancing the model's performance.

[Arxiv](https://arxiv.org/abs/2408.12948)