# 利用大型语言模型洞察人类情绪调节策略

发布时间：2024年08月08日

`LLM应用` `心理治疗` `人工智能`

> Recognizing Emotion Regulation Strategies from Human Behavior with Large Language Models

# 摘要

> 人类情感往往通过内部过程和社会规则进行微妙调节。对于情感计算系统而言，理解这种调节机制极为关键，例如在模拟面试或心理治疗中提供精准反馈。目前，跨用户自动识别情感调节策略的方法尚属空白。最新研究显示，经过优化的LLMs在情感识别任务中表现卓越，但其能否精准解读用户内心的情感调节策略仍待探索。为此，我们采用新近的\textsc{Deep}语料库，该库详细记录了羞耻感的社会表现，并标注了七类情感调节方式。我们通过低秩优化技术，对Llama2-7B和Gemma模型进行微调，整合了言语、非言语行为、个人特质及互动后的深入访谈信息。实验结果表明，微调后的Llama2-7B模型在不依赖互动后数据的情况下，情感调节策略分类准确率高达0.84，显著超越了传统贝叶斯网络方法，凸显了言语行为在情感调节分析中的重要性。

> Human emotions are often not expressed directly, but regulated according to internal processes and social display rules. For affective computing systems, an understanding of how users regulate their emotions can be highly useful, for example to provide feedback in job interview training, or in psychotherapeutic scenarios. However, at present no method to automatically classify different emotion regulation strategies in a cross-user scenario exists. At the same time, recent studies showed that instruction-tuned Large Language Models (LLMs) can reach impressive performance across a variety of affect recognition tasks such as categorical emotion recognition or sentiment analysis. While these results are promising, it remains unclear to what extent the representational power of LLMs can be utilized in the more subtle task of classifying users' internal emotion regulation strategy. To close this gap, we make use of the recently introduced \textsc{Deep} corpus for modeling the social display of the emotion shame, where each point in time is annotated with one of seven different emotion regulation classes. We fine-tune Llama2-7B as well as the recently introduced Gemma model using Low-rank Optimization on prompts generated from different sources of information on the \textsc{Deep} corpus. These include verbal and nonverbal behavior, person factors, as well as the results of an in-depth interview after the interaction. Our results show, that a fine-tuned Llama2-7B LLM is able to classify the utilized emotion regulation strategy with high accuracy (0.84) without needing access to data from post-interaction interviews. This represents a significant improvement over previous approaches based on Bayesian Networks and highlights the importance of modeling verbal behavior in emotion regulation.

[Arxiv](https://arxiv.org/abs/2408.04420)