# [揭示真相：该系统旨在评测大型语言模型的信任度，以准确衡量其可靠程度。]

发布时间：2024年03月07日

`LLM应用`

> Tell me the truth: A system to measure the trustworthiness of Large Language Models

> 自从ChatGPT在2023年横空出世以来，LLM便成为众多新闻焦点。尽管如此，企业在采纳此类模型时犹豫不决，主要源于对其可靠性的信任程度有限。例如，一项由Baymard在2023年的研究表明，ChatGPT-4在识别网站用户体验问题时的错误判断率高达80.1%，而在JAMA Pediatrics 2024年1月的研究中，ChatGPT在诊断儿科病例时的准确率仅为17%。信任实际上是一个随文化、领域和个人差异而变的相对主观条件。那么，在确定了某一领域后，又该如何衡量系统的可信度呢？本文介绍了一种基于领域预定义事实真相的知识图谱表示法，通过人类参与的闭环校验和系统微调过程，提供一种系统性评估系统可信度的方法。这一测量方法对于诸如医疗健康、国防、金融等关键领域的所有实体至关重要，同时也对所有LLM的使用者具有重大意义。

> Large Language Models (LLM) have taken the front seat in most of the news since November 2023, when ChatGPT was introduced. After more than one year, one of the major reasons companies are resistant to adopting them is the limited confidence they have in the trustworthiness of those systems. In a study by (Baymard, 2023), ChatGPT-4 showed an 80.1% false-positive error rate in identifying usability issues on websites. A Jan. '24 study by JAMA Pediatrics found that ChatGPT has an accuracy rate of 17% percent when diagnosing pediatric medical cases (Barile et al., 2024). But then, what is "trust"? Trust is a relative, subject condition that can change based on culture, domain, individuals. And then, given a domain, how can the trustworthiness of a system be measured? In this paper, I present a systematic approach to measure trustworthiness based on a predefined ground truth, represented as a knowledge graph of the domain. The approach is a process with humans in the loop to validate the representation of the domain and to fine-tune the system.
  Measuring the trustworthiness would be essential for all the entities operating in critical environments, such as healthcare, defense, finance, but it would be very relevant for all the users of LLMs.

[Arxiv](https://arxiv.org/abs/2403.04964)