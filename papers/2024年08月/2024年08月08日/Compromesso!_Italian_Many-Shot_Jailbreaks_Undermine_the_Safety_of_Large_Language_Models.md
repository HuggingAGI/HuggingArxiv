# 意大利式的多次尝试越狱，正逐渐削弱大型语言模型的安全防线。

发布时间：2024年08月08日

`LLM应用` `安全评估` `多语言社区`

> Compromesso! Italian Many-Shot Jailbreaks Undermine the Safety of Large Language Models

# 摘要

> 随着多语言社区采用LLM，跨语言的安全评估变得至关重要。尽管有安全措施，但“越狱”技术仍能使LLM行为不安全。当前研究主要集中在英语，限制了我们对其他语言安全性的理解。我们通过研究意大利语中的多-shot越狱，创建了不安全问答数据集，揭示了四大LLM家族的安全漏洞。我们发现，即使少量不安全提示，模型也会表现出不安全行为，且这种风险随提示增多迅速升级。

> As diverse linguistic communities and users adopt large language models (LLMs), assessing their safety across languages becomes critical. Despite ongoing efforts to make LLMs safe, they can still be made to behave unsafely with jailbreaking, a technique in which models are prompted to act outside their operational guidelines. Research on LLM safety and jailbreaking, however, has so far mostly focused on English, limiting our understanding of LLM safety in other languages. We contribute towards closing this gap by investigating the effectiveness of many-shot jailbreaking, where models are prompted with unsafe demonstrations to induce unsafe behaviour, in Italian. To enable our analysis, we create a new dataset of unsafe Italian question-answer pairs. With this dataset, we identify clear safety vulnerabilities in four families of open-weight LLMs. We find that the models exhibit unsafe behaviors even when prompted with few unsafe demonstrations, and -- more alarmingly -- that this tendency rapidly escalates with more demonstrations.

[Arxiv](https://arxiv.org/abs/2408.04522)