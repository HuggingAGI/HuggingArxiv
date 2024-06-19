# 借助大型语言模型，促进异构临时团队的协作效率

发布时间：2024年06月17日

`Agent

理由：这篇论文主要探讨了异构机器人团队中的协作问题，特别是临时机器人如何加入并有效协作。论文中使用了大型语言模型（LLM）来构建一个去中心化的协作框架，并开发了一种动态规划器和交互式思考反射（IRoT）方法，以帮助临时机器人适应不同的团队。这些内容更侧重于智能体的协作和决策制定，因此归类为Agent。` `机器人技术` `自动化`

> Leveraging Large Language Model for Heterogeneous Ad Hoc Teamwork Collaboration

# 摘要

> 相较于广泛研究的同质多机器人协作，异构机器人因其多样化的能力，能更高效灵活地应对复杂任务。本文探讨了一个更具挑战性的异构临时团队协作问题：一个临时机器人加入已有的异构团队，共同追求目标。这种情况下，临时机器人需与未知队友协作，无需预先协调，并需制定合适的合作策略以提升团队整体效率。为此，我们借助大型语言模型（LLM）的强大功能，构建了一个去中心化的异构临时团队协作框架，专注于为临时机器人制定与异构队友协作的合理策略。我们开发了一种无需训练的分层动态规划器，并结合新提出的交互式思考反射（IRoT）方法，使临时机器人能迅速适应不同团队。此外，我们还建立了一个基准测试数据集，用于评估在异构临时多机器人整理任务中提出的框架。通过广泛的比较和消融实验，我们验证了所提出框架的有效性。在现实世界的场景中，我们也已将该框架应用于物理机器人。实验视频链接为 https://youtu.be/wHYP5T2WIp0。

> Compared with the widely investigated homogeneous multi-robot collaboration, heterogeneous robots with different capabilities can provide a more efficient and flexible collaboration for more complex tasks. In this paper, we consider a more challenging heterogeneous ad hoc teamwork collaboration problem where an ad hoc robot joins an existing heterogeneous team for a shared goal. Specifically, the ad hoc robot collaborates with unknown teammates without prior coordination, and it is expected to generate an appropriate cooperation policy to improve the efficiency of the whole team. To solve this challenging problem, we leverage the remarkable potential of the large language model (LLM) to establish a decentralized heterogeneous ad hoc teamwork collaboration framework that focuses on generating reasonable policy for an ad hoc robot to collaborate with original heterogeneous teammates. A training-free hierarchical dynamic planner is developed using the LLM together with the newly proposed Interactive Reflection of Thoughts (IRoT) method for the ad hoc agent to adapt to different teams. We also build a benchmark testing dataset to evaluate the proposed framework in the heterogeneous ad hoc multi-agent tidying-up task. Extensive comparison and ablation experiments are conducted in the benchmark to demonstrate the effectiveness of the proposed framework. We have also employed the proposed framework in physical robots in a real-world scenario. The experimental videos can be found at https://youtu.be/wHYP5T2WIp0.

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/adhoc.jpg)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/overall_framework_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/comm_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/IRoT_llm.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/SubtaskPrompt.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/SubskillPrompt.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/dataset.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/suc_llm_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/different_room_1.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/suc_adhoc_abi_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/Sim1.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/real_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/Rooms.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/PhysicalFlowchart_compress.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/PhysicalValidation_compress.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/subtask_output_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/subskill_output_new.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/sim_room.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/Physical_medium.png)

![借助大型语言模型，促进异构临时团队的协作效率](../../../paper_images/2406.12224/fail_sample.png)

[Arxiv](https://arxiv.org/abs/2406.12224)