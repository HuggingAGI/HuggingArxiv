# 模型合并研究综述：探讨在协作学习中，如何通过回收和路由机制，让专门专家协同工作。

发布时间：2024年08月13日

`LLM应用` `软件工程` `人工智能`

> A Survey on Model MoErging: Recycling and Routing Among Specialized Experts for Collaborative Learning

# 摘要

> 高性能预训练模型的普及催生了大量针对特定领域或任务的微调专家模型。模型融合技术旨在整合这些专家模型，构建性能更优或泛化能力更强的综合系统。其中，关键在于设计一个智能路由器，根据输入或应用需求选择合适的专家模型。模型融合技术的潜力与多样性，推动了近年来众多新方法的涌现。然而，这些方法的快速发展和实验设置的差异，使得相互比较变得困难。为此，我们进行了一项全面调查，不仅创新性地分类了关键设计选择，还明确了各类方法的适用场景。此外，我们还梳理了利用模型融合的软件工具和应用，并探讨了模型合并、多任务学习及专家混合模型等相关领域。总体而言，我们的调查为现有模型融合方法提供了清晰概览，为该领域的未来发展奠定了坚实基础。

> The availability of performant pre-trained models has led to a proliferation of fine-tuned expert models that are specialized to a particular domain or task. Model MoErging methods aim to recycle expert models to create an aggregate system with improved performance or generalization. A key component of MoErging methods is the creation of a router that decides which expert model(s) to use for a particular input or application. The promise, effectiveness, and large design space of MoErging has spurred the development of many new methods over the past few years. This rapid pace of development has made it challenging to compare different MoErging methods, which are rarely compared to one another and are often validated in different experimental setups. To remedy such gaps, we present a comprehensive survey of MoErging methods that includes a novel taxonomy for cataloging key design choices and clarifying suitable applications for each method. Apart from surveying MoErging research, we inventory software tools and applications that make use of MoErging. We additionally discuss related fields of study such as model merging, multitask learning, and mixture-of-experts models. Taken as a whole, our survey provides a unified overview of existing MoErging methods and creates a solid foundation for future work in this burgeoning field.

[Arxiv](https://arxiv.org/abs/2408.07057)