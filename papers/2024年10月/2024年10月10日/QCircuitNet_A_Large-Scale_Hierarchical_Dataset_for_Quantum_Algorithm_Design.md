# QCircuitNet：专为量子算法设计打造的大规模分层数据集

发布时间：2024年10月10日

`LLM应用` `量子计算` `人工智能`

> QCircuitNet: A Large-Scale Hierarchical Dataset for Quantum Algorithm Design

# 摘要

> 量子计算因其通过量子算法实现的显著加速而备受瞩目，但设计和实现这些算法因量子力学的复杂性和对量子态的精确控制而充满挑战。尽管人工智能发展迅速，但缺乏专门针对量子算法设计的数据集。为此，我们推出了 QCircuitNet，这是首个用于评估人工智能在量子电路代码形式下设计和实现量子算法能力的基准和测试数据集。与传统代码编写不同，量子算法设计因其灵活的设计空间和复杂的量子比特操作而更具挑战性。我们的贡献包括：一个为大型语言模型量身定制的量子算法设计通用框架、广泛量子算法的实现、自动验证和迭代评估功能，以及通过原语微调展示的训练潜力。实验显示，微调并非总是优于少样本学习，大型语言模型常表现出一致的错误模式。QCircuitNet 不仅为人工智能驱动的量子算法设计提供了全面基准，还揭示了大型语言模型在这一领域的一些局限性。

> Quantum computing is an emerging field recognized for the significant speedup it offers over classical computing through quantum algorithms. However, designing and implementing quantum algorithms pose challenges due to the complex nature of quantum mechanics and the necessity for precise control over quantum states. Despite the significant advancements in AI, there has been a lack of datasets specifically tailored for this purpose. In this work, we introduce QCircuitNet, the first benchmark and test dataset designed to evaluate AI's capability in designing and implementing quantum algorithms in the form of quantum circuit codes. Unlike using AI for writing traditional codes, this task is fundamentally different and significantly more complicated due to highly flexible design space and intricate manipulation of qubits. Our key contributions include: 1. A general framework which formulates the key features of quantum algorithm design task for Large Language Models. 2. Implementation for a wide range of quantum algorithms from basic primitives to advanced applications, with easy extension to more quantum algorithms. 3. Automatic validation and verification functions, allowing for iterative evaluation and interactive reasoning without human inspection. 4. Promising potential as a training dataset through primitive fine-tuning results. We observed several interesting experimental phenomena: fine-tuning does not always outperform few-shot learning, and LLMs tend to exhibit consistent error patterns. QCircuitNet provides a comprehensive benchmark for AI-driven quantum algorithm design, offering advantages in model evaluation and improvement, while also revealing some limitations of LLMs in this domain.

[Arxiv](https://arxiv.org/abs/2410.07961)