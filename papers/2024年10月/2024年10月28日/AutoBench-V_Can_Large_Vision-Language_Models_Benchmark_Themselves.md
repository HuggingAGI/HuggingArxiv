# AutoBench-V：大型视觉语言模型能够自我评估吗？

发布时间：2024年10月28日

`LLM应用` `视觉语言模型` `自动评估`

> AutoBench-V: Can Large Vision-Language Models Benchmark Themselves?

# 摘要

> 大型视觉语言模型（LVLMs）对于推进视觉和语言信息的整合已经变得至关重要，促进了广泛的复杂应用和任务。然而，LVLMs 的评估面临着重大挑战，因为评估基准的构建总是需要大量的人力成本，并且一旦构建就保持静态，缺乏灵活性。尽管在文本模态中已经探索了自动评估，但视觉模态仍未得到充分探索。因此，在这项工作中，我们提出了一个问题：“LVLMs 能否作为自动基准测试的途径？”。我们引入了 AutoBench-V，这是一个按需服务评估的自动化框架，即根据模型能力的特定方面对 LVLMs 进行基准测试。在接收到评估能力后，AutoBench-V 利用文本到图像模型生成相关的图像样本，然后利用 LVLMs 来协调视觉问答（VQA）任务，高效灵活地完成评估过程。通过对五个需求用户输入（即评估能力）下的七个流行 LVLMs 的广泛评估，该框架显示出有效性和可靠性。我们观察到以下情况：（1）我们构建的基准准确地反映了不同的任务难度；（2）随着任务难度的增加，模型之间的性能差距扩大；（3）虽然模型在抽象层面的理解上表现出色，但在细节推理任务中表现不佳；（4）构建具有不同难度水平的数据集对于全面和详尽的评估至关重要。总的来说，AutoBench-V 不仅成功地利用 LVLMs 进行了自动基准测试，而且还揭示了 LVLMs 作为评判者在各个领域具有巨大的潜力。

> Large Vision-Language Models (LVLMs) have become essential for advancing the integration of visual and linguistic information, facilitating a wide range of complex applications and tasks. However, the evaluation of LVLMs presents significant challenges as the evaluation benchmark always demands lots of human cost for its construction, and remains static, lacking flexibility once constructed. Even though automatic evaluation has been explored in textual modality, the visual modality remains under-explored. As a result, in this work, we address a question: "Can LVLMs serve as a path to automatic benchmarking?". We introduce AutoBench-V, an automated framework for serving evaluation on demand, i.e., benchmarking LVLMs based on specific aspects of model capability. Upon receiving an evaluation capability, AutoBench-V leverages text-to-image models to generate relevant image samples and then utilizes LVLMs to orchestrate visual question-answering (VQA) tasks, completing the evaluation process efficiently and flexibly. Through an extensive evaluation of seven popular LVLMs across five demanded user inputs (i.e., evaluation capabilities), the framework shows effectiveness and reliability. We observe the following: (1) Our constructed benchmark accurately reflects varying task difficulties; (2) As task difficulty rises, the performance gap between models widens; (3) While models exhibit strong performance in abstract level understanding, they underperform in details reasoning tasks; and (4) Constructing a dataset with varying levels of difficulties is critical for a comprehensive and exhaustive evaluation. Overall, AutoBench-V not only successfully utilizes LVLMs for automated benchmarking but also reveals that LVLMs as judges have significant potential in various domains.

[Arxiv](https://arxiv.org/abs/2410.21259)