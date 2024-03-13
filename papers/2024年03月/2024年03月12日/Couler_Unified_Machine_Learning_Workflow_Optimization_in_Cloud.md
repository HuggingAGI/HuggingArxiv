# [Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](https://arxiv.org/abs/2403.07608)

发布时间：2024年03月12日

`Agent`

> Couler: Unified Machine Learning Workflow Optimization in Cloud

> 如今，ML 力量遍布各行各业，推动各类机构的数据驱动应用发展。然而现实中的 ML 工作流程往往与研究中简单的理解相悖，它们复杂繁重，耗费资源且耗时长。拓宽 ML 工作流程以适应更多样化的数据设施和数据类型，可能会带来更大规模的任务和更高的部署开销。市面上有多达数十种主流的工作流引擎可供选择，这一多样性使得用户面临掌握不同引擎 API 的难题。虽然当前的研究重点是针对特定工作流引擎优化 MLOps，但对于跨引擎的工作流程优化却鲜有关注。在此研究中，我们创新设计并实施了 Couler 系统，它专为云环境下的 ML 工作流程统一优化打造。我们独到的见解在于运用 NL 描述来构建 ML 工作流程，并将 LLMs 融入工作流程生成过程，还提供了一种适用于多种引擎的统一编程接口，极大地简化了用户对不同引擎 API 的学习难度。不仅如此，Couler 还通过引入多级自动缓存机制，实现了大型工作流程的智能并行化和自动超参数调优，显著提升了计算效率，有效减少了深度学习工作流程训练期间的重复计算成本，增强了系统的鲁棒性。Couler 已在蚂蚁集团的实际生产环境中广泛应用，日均处理近2.2万个工作流程，成功提升了 CPU 和内存利用率逾15%，并将工作流程完成率提高了大约17%。

> Machine Learning (ML) has become ubiquitous, fueling data-driven applications across various organizations. Contrary to the traditional perception of ML in research, ML workflows can be complex, resource-intensive, and time-consuming. Expanding an ML workflow to encompass a wider range of data infrastructure and data types may lead to larger workloads and increased deployment costs. Currently, numerous workflow engines are available (with over ten being widely recognized). This variety poses a challenge for end-users in terms of mastering different engine APIs. While efforts have primarily focused on optimizing ML Operations (MLOps) for a specific workflow engine, current methods largely overlook workflow optimization across different engines.
  In this work, we design and implement Couler, a system designed for unified ML workflow optimization in the cloud. Our main insight lies in the ability to generate an ML workflow using natural language (NL) descriptions. We integrate Large Language Models (LLMs) into workflow generation, and provide a unified programming interface for various workflow engines. This approach alleviates the need to understand various workflow engines' APIs. Moreover, Couler enhances workflow computation efficiency by introducing automated caching at multiple stages, enabling large workflow auto-parallelization and automatic hyperparameters tuning. These enhancements minimize redundant computational costs and improve fault tolerance during deep learning workflow training. Couler is extensively deployed in real-world production scenarios at Ant Group, handling approximately 22k workflows daily, and has successfully improved the CPU/Memory utilization by more than 15% and the workflow completion rate by around 17%.

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x1.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x2.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x3.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x4.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x5.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x6.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x7.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x8.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x9.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x10.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x11.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x12.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x13.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x14.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x15.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/workflow_example.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x16.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x17.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x18.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x19.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x20.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x21.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x22.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x23.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x24.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x25.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x26.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x27.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x28.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x29.png)

![Couler——致力于在云端实现机器学习工作流程的一体化优化，提升效率与性能。](../../../paper_images/2403.07608/x30.png)