# 回溯用户历程：精炼历史数据，定制科学写作体验

发布时间：2024年06月20日

`LLM应用

理由：这篇论文主要探讨了如何通过“后退一步画像”策略来增强大型语言模型（LLMs）在个性化内容生成方面的能力，特别是在科学写作领域。这种方法通过精炼用户历史信息来创建个性化简洁画像，以更好地捕捉用户的核心特质与偏好。论文中提到的实验和数据集（个性化科学写作PSW数据集）以及其在通用个性化基准（LaMP）上的表现，都直接关联到LLM的实际应用，即如何改进LLM以更好地服务于特定用户群体的需求。因此，这篇论文属于LLM应用类别。` `科学写作` `个性化内容生成`

> Step-Back Profiling: Distilling User History for Personalized Scientific Writing

# 摘要

> 大型语言模型（LLMs）虽在众多自然语言处理任务中表现卓越，但在生成针对个人的个性化内容，尤其是在科学写作等实际场景中，却显得力不从心。为此，我们创新性地提出了“后退一步画像”策略，通过精炼用户历史信息，为LLMs打造个性化简洁画像，涵盖用户的核心特质与偏好。在实验环节，我们精心打造了“个性化科学写作”（PSW）数据集，旨在探索多用户个性化。PSW挑战模型根据学术背景各异的特定作者群体撰写科学论文。实验成果显著，证明了“后退一步画像”在捕捉用户特征以促进协作写作方面的有效性。我们的方法在通用个性化基准（LaMP）上，涵盖7项个性化LLM任务，超越基线模型高达3.6分。通过详尽的消融研究，我们验证了方法中各组件的贡献，并深化了对任务定义的理解。数据集与代码已公开于\url{https://github.com/gersteinlab/step-back-profiling}。

> Large language models (LLMs) excel at a variety of natural language processing tasks, yet they struggle to generate personalized content for individuals, particularly in real-world scenarios like scientific writing. Addressing this challenge, we introduce Step-Back Profiling to personalize LLMs by distilling user history into concise profiles, including essential traits and preferences of users. Regarding our experiments, we construct a Personalized Scientific Writing (PSW) dataset to study multiuser personalization. PSW requires the models to write scientific papers given specialized author groups with diverse academic backgrounds. As for the results, we demonstrate the effectiveness of capturing user characteristics via Step-Back Profiling for collaborative writing. Moreover, our approach outperforms the baselines by up to 3.6 points on the general personalization benchmark (LaMP), including 7 personalization LLM tasks. Our extensive ablation studies validate the contributions of different components in our method and provide insights into our task definition. Our dataset and code are available at \url{https://github.com/gersteinlab/step-back-profiling}.

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x1.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x2.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x3.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x4.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x5.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x6.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x7.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x8.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x9.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x10.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x11.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x12.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x13.png)

![回溯用户历程：精炼历史数据，定制科学写作体验](../../../paper_images/2406.14275/x14.png)

[Arxiv](https://arxiv.org/abs/2406.14275)