# 思维的审判：大型语言模型中二元逻辑推理的法庭

发布时间：2024年09月25日

`LLM应用` `信息安全`

> Judgment of Thoughts: Courtroom of the Binary Logical Reasoning in Large Language Models

# 摘要

> 本文介绍了一种名为“思维判断”（JoT）的新提示工程技术，专为二元逻辑推理任务设计。JoT 通过律师、检察官和法官三种角色，帮助模型进行更可靠和准确的推理。实验结果显示，JoT 在二元逻辑推理任务中超越了现有方法，如思维链（CoT）和自一致性（SC），并在假新闻检测和短信垃圾检测等实际任务中表现出色。JoT 不仅提升了模型的准确性和可靠性，还展现了跨领域的应用潜力。未来研究应进一步拓展 JoT 的应用范围，并优化其在实际问题解决中的表现。

> This paper proposes a novel prompt engineering technique called Judgment of Thought (JoT) that is specifically tailored for binary logical reasoning tasks. JoT employs three roles$\unicode{x2014}$lawyer, prosecutor, and judge$\unicode{x2014}$to facilitate more reliable and accurate reasoning by the model. In this framework, the judge utilizes a high$\unicode{x2010}$level model, while the lawyer and prosecutor utilize low$\unicode{x2010}$level models. This structure helps the judge better understand the responses from both the lawyer and prosecutor, enabling a more accurate judgment. Experimental results on large language model (LLM) benchmark datasets, such as BigBenchHard and Winogrande, demonstrate that JoT outperforms existing methods, including Chain of Thought (CoT) and Self$\unicode{x2010}$Consistency (SC), in binary logical reasoning tasks. Additionally, in real$\unicode{x2010}$world tasks, such as Fake News Detection and SMS Spam Detection, JoT shows comparable or improved performance compared to existing techniques. JoT significantly enhances the accuracy and reliability of models in binary reasoning tasks and show potential for practical applicability across various domains. Future research should aim to further broaden the applicability of JoT and optimize its implementation for real$\unicode{x2010}$world problem$\unicode{x2010}$solving.

[Arxiv](https://arxiv.org/abs/2409.16635)