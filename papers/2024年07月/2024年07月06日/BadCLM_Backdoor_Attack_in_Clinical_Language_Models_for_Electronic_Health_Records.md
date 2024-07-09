# BadCLM：电子健康记录中临床语言模型的后门攻击

发布时间：2024年07月06日

`LLM应用` `网络安全`

> BadCLM: Backdoor Attack in Clinical Language Models for Electronic Health Records

# 摘要

> 临床语言模型融入电子健康记录（EHR），助力临床决策，是一大进步。然而，这些模型的潜在弱点尚未充分探索。本文探讨了针对临床语言模型的后门攻击，引入了基于注意力的BadCLM攻击方法。该方法在模型中秘密植入后门，使其在特定触发下产生错误预测，平时则正常运作。通过MIMIC III数据集的院内死亡率预测任务，我们验证了BadCLM的威胁性。研究揭示了临床决策支持系统的安全风险，并为强化模型防御指明了方向。

> The advent of clinical language models integrated into electronic health records (EHR) for clinical decision support has marked a significant advancement, leveraging the depth of clinical notes for improved decision-making. Despite their success, the potential vulnerabilities of these models remain largely unexplored. This paper delves into the realm of backdoor attacks on clinical language models, introducing an innovative attention-based backdoor attack method, BadCLM (Bad Clinical Language Models). This technique clandestinely embeds a backdoor within the models, causing them to produce incorrect predictions when a pre-defined trigger is present in inputs, while functioning accurately otherwise. We demonstrate the efficacy of BadCLM through an in-hospital mortality prediction task with MIMIC III dataset, showcasing its potential to compromise model integrity. Our findings illuminate a significant security risk in clinical decision support systems and pave the way for future endeavors in fortifying clinical language models against such vulnerabilities.

![BadCLM：电子健康记录中临床语言模型的后门攻击](../../../paper_images/2407.05213/pic1_illustration.jpg)

![BadCLM：电子健康记录中临床语言模型的后门攻击](../../../paper_images/2407.05213/v3.png)

![BadCLM：电子健康记录中临床语言模型的后门攻击](../../../paper_images/2407.05213/fig6_att_arch.png)

![BadCLM：电子健康记录中临床语言模型的后门攻击](../../../paper_images/2407.05213/x1.png)

![BadCLM：电子健康记录中临床语言模型的后门攻击](../../../paper_images/2407.05213/fig5_cacc.png)

![BadCLM：电子健康记录中临床语言模型的后门攻击](../../../paper_images/2407.05213/fig6_auc.png)

[Arxiv](https://arxiv.org/abs/2407.05213)