# 通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。

发布时间：2024年07月23日

`LLM应用` `人工智能` `软件开发`

> Stress-Testing Long-Context Language Models with Lifelong ICL and Task Haystack

# 摘要

> 我们提出了终身ICL，这是一个挑战长上下文语言模型通过上下文学习从一系列语言任务中学习的新设置。同时，我们引入了任务Haystack评估套件，专门用于评估长上下文LMs在终身ICL中的上下文利用能力。在这个设置中，长上下文LMs需要有效利用相关演示，避免其他任务的干扰，并保持与单任务ICL相当的测试准确性。任务Haystack借鉴了“大海捞针”评估方法，但增加了新的挑战，要求模型深入理解而非简单复制上下文，并在复杂多变的任务流中导航。此外，它还提供了工具和可视化，帮助开发者有效识别模型弱点。通过任务Haystack，我们发现即使是顶尖的封闭模型如GPT-4o也面临挑战，平均失败率达15%，而开放权重模型表现更差，失败率高达61%。分析显示，干扰和近期偏差是主要失败原因。我们还发现，任务指令的改述或ICL演示的过度重复会降低性能，这凸显了当前长上下文LMs在鲁棒性、指令理解和上下文利用方面的不足。

> We introduce Lifelong ICL, a problem setting that challenges long-context language models (LMs) to learn from a sequence of language tasks through in-context learning (ICL). We further introduce Task Haystack, an evaluation suite dedicated to assessing and diagnosing how long-context LMs utilizes contexts in Lifelong ICL. When given a task instruction and test inputs, long-context LMs are expected to leverage the relevant demonstrations in the Lifelong ICL prompt, avoid distraction and interference from other tasks, and achieve test accuracies that are not significantly worse than the Single-task ICL baseline.
  Task Haystack draws inspiration from the widely-adopted "needle-in-a-haystack" (NIAH) evaluation, but presents new and unique challenges. It demands that models (1) utilize the contexts with deeper understanding, rather than resorting to simple copying and pasting; (2) navigate through long streams of evolving topics and tasks, which closely approximates the complexities of real-world usage of long-context LMs. Additionally, Task Haystack inherits the controllability aspect of NIAH, providing model developers with tools and visualizations to identify model vulnerabilities effectively.
  We benchmark 12 long-context LMs using Task Haystack. We find that state-of-the-art closed models such as GPT-4o still struggle in this setting, failing 15% of the cases on average, while all open-weight models we evaluate further lack behind by a large margin, failing up to 61% of the cases. In our controlled analysis, we identify factors such as distraction and recency bias as contributors to these failure cases. Further, we observe declines in performance when task instructions are paraphrased at test time or when ICL demonstrations are repeated excessively, raising concerns about the robustness, instruction understanding, and true context utilization of current long-context LMs.

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x1.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x2.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x3.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x4.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x5.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x6.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x7.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x8.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x9.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x10.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x11.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x12.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x13.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x14.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x15.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x16.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x17.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x18.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x19.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x20.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x21.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x22.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x23.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x24.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x25.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x26.png)

![通过终身 ICL 和任务海斯塔克，对长上下文语言模型进行压力测试。](../../../paper_images/2407.16695/x27.png)

[Arxiv](https://arxiv.org/abs/2407.16695)