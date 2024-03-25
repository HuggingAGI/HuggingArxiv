# VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。

发布时间：2024年03月21日

`LLM应用` `视频处理`

> VURF: A General-purpose Reasoning and Self-refinement Framework for Video Understanding

> 近期研究表明，大型语言模型（LLMs）在处理复杂任务时展现出强大的分解能力，尤其在处理图像的视觉推理任务时表现卓越。而今，本文提出一种新颖的视频理解和推理框架（VURF），充分利用LLMs的推理能力。我们独辟蹊径，借助LLMs在上下文环境中从少量输入输出示例中归纳学习的能力，将其应用至视频任务场景。我们通过给LLMs提供一系列指令及其对应的高级程序配对，激发其上下文学习潜能，生成可用于视频理解的可执行视觉程序。为了提升程序的精确度和稳定性，我们采取两项关键策略：一是运用GPT-3.5驱动的反馈生成技术，纠正因使用不支持函数而导致的程序错误；二是借鉴LLMs输出自我优化的最新研究成果，设计了一种迭代流程，通过调整初始输出使其贴近若不受上下文示例结构约束时LLMs所生成的理想输出，从而优化上下文示例质量。我们在视觉问答、视频预测、姿态估计和多视频问答等一系列视频专项任务上的实验结果充分验证了这些改进措施可以有效提升针对视频任务的视觉编程方法的性能。我们将会公开发布的代码和数据集为这一结论提供了有力支撑。

> Recent studies have demonstrated the effectiveness of Large Language Models (LLMs) as reasoning modules that can deconstruct complex tasks into more manageable sub-tasks, particularly when applied to visual reasoning tasks for images. In contrast, this paper introduces a Video Understanding and Reasoning Framework (VURF) based on the reasoning power of LLMs. Ours is a novel approach to extend the utility of LLMs in the context of video tasks, leveraging their capacity to generalize from minimal input and output demonstrations within a contextual framework. By presenting LLMs with pairs of instructions and their corresponding high-level programs, we harness their contextual learning capabilities to generate executable visual programs for video understanding. To enhance program's accuracy and robustness, we implement two important strategies. Firstly, we employ a feedback-generation approach, powered by GPT-3.5, to rectify errors in programs utilizing unsupported functions. Secondly, taking motivation from recent works on self refinement of LLM outputs, we introduce an iterative procedure for improving the quality of the in-context examples by aligning the initial outputs to the outputs that would have been generated had the LLM not been bound by the structure of the in-context examples. Our results on several video-specific tasks, including visual QA, video anticipation, pose estimation and multi-video QA illustrate the efficacy of these enhancements in improving the performance of visual programming approaches for video tasks. Our Codes and data will be publicly released.

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/teaser.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/VURF_pipeline.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/ref_eg.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/Funcs.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/compositionalVQA.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/fall_diag.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/qual.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/acc_iter.png)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/error-vs-iter.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/prompt.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/error_prompt.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/ref_prompt.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/sref.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/tennis.jpg)

![VURF 是一个广泛适用于视频理解的推理与自我优化框架，致力于深入理解和解析视频内容。步骤2改进后的翻译：VURF 是一款通用型视频理解推理与自适应优化框架，旨在高效地处理并深化对各类视频内容的理解与解析。](../../../paper_images/2403.14743/beaker.jpg)

[Arxiv](https://arxiv.org/abs/2403.14743)